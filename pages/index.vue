<template>
  <div class="container is-fluid">
    <div>
      <Logo />
      <h1 class="title">
        Un artisan à votre service.
        <br />
        <span class="cta">Dépannage & travaux</span>
      </h1>
      <div class="contact">
        <p>
          <a href="mailto:carlierphilipp@gmail.com">Contactez-moi !</a>
        </p>
        <p>
          <a href="tel:+33686838806">Cliquez ici pour appelez le 06 86 83 88 06</a>
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.container {
  width: 100%;
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  background: rgba(26, 25, 25, 0.151);
}
.container a {
  color: #101111;
  text-decoration: none;
  text-transform: uppercase;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  display: block;
  font-weight: 300;
  /* font-size: 100px; */
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}
.cta {
  text-decoration-line: underline;
}
.contact{
  margin-top: 2em;
  display: flex;
  justify-content: space-around;
  align-items: center;
  text-align: center;
}
</style>
