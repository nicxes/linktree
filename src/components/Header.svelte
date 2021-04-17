<header>
  <div class="Logo">
    <img
      src="https://dcdws.blob.core.windows.net/dws-11097653-13483-media/sites/13483/2020/09/logo-web.png"
      height="85"
      alt="Sport Cars"
    >
  </div>

  <div class="Metadata">
    <h1>{title}</h1>
    <h2>@{username}</h2>
  </div>
</header>

<script>
  export let title, username;
</script>

<style>
	header {
		display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;

    margin-bottom: 40px;
  }
  .Logo {
    margin-bottom: 20px;
  }
  .Metadata {
    text-align: center;
  }
  .Metadata h1 {
    color: #fff;
    font-size: 26px;
  
    margin-bottom: 5px;
  }
  .Metadata h2 {
    color: #ddd;
    font-size: 16px;
    margin: 0;
  }
</style>