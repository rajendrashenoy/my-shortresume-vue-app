<template>
  <div class="hello">
    <img class="photograph" alt="Vue logo" src="../assets/photo.jpg">
    <h3>Rajendra Shenoy</h3>
    <p>Senior Full Stack Developer</p>
    <p>Senior Full Stack Developer with 22+ years of experience
    in designing and developing complex IT solutions leveraging
    wide array of technical skills. Looking for a position
    that offers opportunities to develop digitally transformative
    IT solutions in an agile and rapid time to market environment</p>
    <h3>Contact</h3>
    <p>Phone: +1 (905) 536 9637</p>
    <p>Email: rrajendra@yahoo.com, shenoy.rajendra@gmail.com</p>
    <a href="https://www.linkedin.com/in/raj-shenoy" target="_blank">LinkedIn Profile</a>  
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

.hello{
top: 1%;
width: 45%;
height: 85%;
left: 1%;
position: fixed;
text-align: justify;
text-justify: inter-word;
background-color: lightgrey;
padding: 10px;
overflow-x: scroll;
overflow-y: scroll;
}

.photograph {

}

h3 {
  margin: 10px 0 0;
}

</style>
