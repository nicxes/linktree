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
		{ text: 'Google Review', url: 'https://dcdws.blob.core.windows.net/dws-11097653-13483-media/sites/13483/2021/04/google.png' },
		{ text: 'Facebook Review', url: 'https://dcdws.blob.core.windows.net/dws-11097653-13483-media/sites/13483/2021/04/facebook.png' },
		{ text: 'Yelp Review', url: 'https://dcdws.blob.core.windows.net/dws-11097653-13483-media/sites/13483/2021/04/yelp.png' },
		{ text: 'Cargurus Review', url: 'https://dcdws.blob.core.windows.net/dws-11097653-13483-media/sites/13483/2021/04/cargurus.png' },
		{ text: 'Cars.com Review', url: 'https://dcdws.blob.core.windows.net/dws-11097653-13483-media/sites/13483/2021/04/cars.png' },
    { text: 'BBB Review', url: 'https://i.imgur.com/XgciyyH.png' },
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