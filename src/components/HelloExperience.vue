<template>
  <div class="hello">
    <h3>Work Experience</h3>
    <p class="timeline">June 2010 to Present</p>
    <p class="jobtitle"><b>Senior Applications Consultant, </b><i> Stefanini Canada Ltd.</i></p>
    <p>Designs, Develops, supports, and provides technical consultancy in areas of UI/UX,
    Mobility, Web Application development, CRM, and Digital Transformation to a wide range
    of Stefanini clients</p>
    <p class="timeline">October 2008 to December 2010</p>
    <p class="jobtitle"><b>Lead Technical Consultant, </b><i> Belgacom, Brussels.</i></p>
    <p>Designed, developed, and rolled out Belgacom's first web based loyalty program.</p>
    <p class="timeline">October 2007 to September 2008</p>
    <p class="jobtitle"><b>CRM Consultant, </b><i> Accenture, Germany.</i></p>
    <p>Mapped legacy product catalog to the new product catalog.</p>
    <p class="timeline">January 2000 to June 2002, April 2004 to September 2007</p>
    <p class="jobtitle"><b>CRM Consultant, </b><i> o2, Germany.</i></p>
    <p>Developed o2 Germany's self care web application, retail product catalog, and retail customer database.</p>
    <p class="timeline">July 2002 to March 2004</p>
    <p class="jobtitle"><b>Senior Programmer, </b><i> BMW Group, Germany.</i></p>
    <p>Developed BMW groups CRM System.</p>
    <p class="timeline">June 1996 to December 1999</p>
    <p class="jobtitle"><b>Analyst Programmer, </b><i> Ramco System, Madras, India.</i></p>
    <p>Designed and developed Ramco's ERP Web application.</p>
  </div>
</template>

<script>
export default {
  name: 'HelloExperience',
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
left: 50%;
position: fixed;
text-align: justify;
text-justify: inter-word;
padding: 10px;
overflow-x: scroll;
overflow-y: scroll;
}

.timeline {
font-weight: bold;
}

.jobtitle {
text-align: left;
}

h3 {
  margin: 10px 0 0;
}

</style>
