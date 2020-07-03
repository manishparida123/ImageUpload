<template>
  <div id="app">
    <img id="logo" src="https://cloudcomputingassignment0407.s3.ap-south-1.amazonaws.com/768px-Image_upload-tango.svg.png">
    <s3uploader/>
  </div>
</template>

<script>
import s3uploader from './components/s3uploader'

export default {
  name: 'App',
  components: {
    s3uploader
  }
}
</script>

<style>
#logo {
  width: 100px
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
