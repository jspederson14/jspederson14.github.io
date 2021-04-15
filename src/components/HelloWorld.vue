<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      Hello. My name is Joe Pederson and I am current student at Knox College in Galesburg, Illinois. 
      I am a sophmore planning on graduating in 2023 and majoring in Computer Science as well as a minor in Polical Science.
      I am a member of the swim team at Knox as well as the captian of the water polo club team at Knox.
      I am orginally from Roswell, Georgia. 
    </p>
    <h3>Resume</h3>
    <p>
      (I don't have a proper resume so this is a place holder)
    </p>
    <h3>Past Projects</h3>
    <ul>
      <li><a href="https://github.com/jspederson14/chess" target="_blank" rel="noopener">Chess</a></li>
      <li><a href="https://github.com/jspederson14/policing_project" target="_blank" rel="noopener">Policing Project</a></li>
      <li><a href="https://github.com/jspederson14/AsciiAdventure" target="_blank" rel="noopener">Ascii Adventure</a></li>
      <li><a href="https://github.com/jspederson14/jspederson14.github.io" target="_blank" rel="noopener">This Site</a></li>
    </ul>
    <h3>Contact Information</h3>
    <p>
      Email: jspederson@knox.edu &ensp;
      Phone: 770-312-7238
    </p> 
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
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
</style>
