<main>
  <ul>
    {#each links as link}
      <li>
        <a href="{link.url}">
          {link.text}
        </a>
      </li>
    {/each}
  </ul>
</main>

<script>
  const links = [
		{ text: 'Google Review', url: 'https://i.imgur.com/o3jhYDl.png' },
		{ text: 'Facebook Review', url: 'https://i.imgur.com/Lt64QB5.png' },
		{ text: 'Yelp Review', url: 'https://i.imgur.com/gZr6UXH.png' },
		{ text: 'Cargurus Review', url: 'https://i.imgur.com/sav6kQk.png' }
	]
</script>

<style>
  main {
    padding: 0 12px;
    max-width: 680px;
    margin: 0 auto;
  }
  ul li {
    margin-bottom: 25px;
  }
  ul li a {
    color: #fff;
    font-weight: 500;
    text-align: center;
    text-decoration: none;

    display: block;
    padding: 16px 20px;

    background: transparent;
    border: 1px solid;
    border-color: #fff;
  
    transition: 300ms;
  }
  ul li a:hover {
    color: #fff;
    background: #d91200;
    border-color: #d91200;
  }
</style>