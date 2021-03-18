<template>
  <div class="container">
    <div>
      <Logo />
      <h1 class="title">
        Yán Jiā Huī
      </h1>
      <div class="links">
        <a
          href="http://blog.lovemysoul.vip/"
          rel="noopener noreferrer"
          class="button--green"
        >
          <a-icon type="form" /> Blog
        </a>
        <a
          href="https://github.com/crazymryan"
          rel="noopener noreferrer"
          class="button--grey"
        >
          <a-icon type="github" /> GitHub
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  /* background-image: url('http://img.lovemysoul.vip/images/Filedata-1616057385234.jpeg'); */
  /* background-image: url('http://img.lovemysoul.vip/images/Filedata-1616057717027.jpeg'); */
  background-image: url('http://img.lovemysoul.vip/images/Filedata-1616070295941.jpeg');
  background-size: 100% 100%;
  background-repeat: no-repeat;
  /* background-color: rgba(255,255 ,255, .5); */
}

.title {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 300;
  font-size: 4em;
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

.links {
  padding-top: 15px;
}
</style>
