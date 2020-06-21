<script>
  import "../node_modules/bulma/css/bulma.min.css";
</script>

<style>

</style>

<main>
  <nav
    class="navbar is-fixed-top is-black"
    role="navigation"
    aria-label="main navigation">
    <div class="navbar-brand">
      <a class="navbar-item" href="https://bulma.io">
        <img src="home.png" width="112" height="28" alt="home" />
      </a>

      <a
        href="#"
        role="button"
        class="navbar-burger burger"
        aria-label="menu"
        aria-expanded="false"
        data-target="navbarBasicExample">
        <span aria-hidden="true" />
        <span aria-hidden="true" />
        <span aria-hidden="true" />
      </a>
    </div>

    <div id="navbarBasicExample" class="navbar-menu">
      <div class="navbar-start">
        <a href="#" class="navbar-item">Home</a>

        <a href="#" class="navbar-item">Blog</a>

        <div href="#" class="navbar-item has-dropdown is-hoverable">
          <a href="#" class="navbar-link">Social Media</a>

          <div class="navbar-dropdown">
            <a href="#" class="navbar-item">Facebook</a>
            <a href="#" class="navbar-item">Instagram</a>
            <a href="#" class="navbar-item">Trakteer</a>
            <a href="#" class="navbar-item">Patreon</a>
            <a href="#" class="navbar-item">Discord</a>
          </div>
        </div>
      </div>

      <!-- <div class="navbar-end">
				<div class="navbar-item">
					<div class="buttons">
						<a class="button is-primary">
							<strong>Sign up</strong>
						</a>
						<a class="button is-light">
							Log in
						</a>
					</div>
				</div>
			</div> -->
    </div>
  </nav>
</main>
