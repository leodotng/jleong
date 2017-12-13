<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h1>{{ msg2 }}</h1>
    <img src="https://s3-us-west-2.amazonaws.com/quilt-production/logo/2017/10/Hghb4ApkwpAvSF7MJI.png">
    <h2>Essential Links</h2>
    <ul>
      <li><a href="https://talent.galvanize.com/students/1973" target="_blank">Galvanize Talent Profile</a></li>
      <li><a href="https://www.linkedin.com/in/joshleong/" target="_blank">Linkedin</a></li>
      <li><a href="https://www.twitter.com/leodotng" target="_blank">Twitter</a></li>
      <li><a href="https://www.facebook.com/leodotng" target="_blank">Facebook</a></li>
      <li><a href="https://www.github.com/leodotng" target="_blank">Github</a></li>
      <br>
    </ul>
    
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Josh Leong',
      msg2: 'http://josh.leo.ng'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
img {
    border-radius: 50%;
}
</style>
