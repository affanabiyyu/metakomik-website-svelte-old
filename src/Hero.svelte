<script>

</script>

<style>
  .hero {
    width: 100vw;
    height: 100vh;

    /* Flexbox stuff */
    display: flex;
    justify-content: center;
    align-items: center;

    /* Text styles */
    text-align: center;
    color: white;

    /* Background styles */
    background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)),
      url(../cover.jpg);
    background-size: cover;
    background-position: center center;
    background-repeat: no-repeat;
    background-attachment: fixed;

    padding: 0 !important;
  }

  .hero h1 {
    /* Text styles */
    font-size: 5em;
    font-weight: bold;
    text-transform: uppercase;

    /* Margins */
    margin-top: 0;
    margin-bottom: 0.5em;
  }

  .hero h2 {
    font-size: 1.5em;
    margin-top: -1.7em;
  }

  .hero .hero-inner img {
    width: 15em;
  }
</style>

<main>
  <section class="hero">
    <div class="hero-inner">
      <img src="logo.png" alt="cover" />
      <h1>Meta Studio</h1>
      <h2>sebuah studio komik cetak & web</h2>
    </div>
  </section>
</main>
