<template>
  <div class="main">
    <h1>{{ msg }}</h1>
    <h2> Serving the Mechanicsburg Area</h2>
    <p>Central PA #1 Airport Shuttle Service </p> 
    <h3>Airports Served: </h3>
    <ul>
      <li>HIA</li>
      <li>Reagan National</li>
      <li>Dulles</li>
      <li>BWI</li>
      <li>JFK</li>
      <li>EWR</li>
    </ul>
    <a class="themebutton" href="https://relaxandridecarlisle.com/book-now/">Book Today</a>
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
  color: blue;
}
a.themebutton {
font-size: 13px;
text-transform: uppercase;
font-weight: 700;
letter-spacing: .5px;
background-color: #338ea6;
-webkit-border-radius: 25px;
-moz-border-radius: 25px;
-ms-border-radius: 25px;
-o-border-radius: 25px;
border-radius: 25px;
-webkit-transition: all .3s ease;
-moz-transition: all .3s ease;
-ms-transition: all .3s ease;
-o-transition: all .3s ease;
transition: all .3s ease;
}
.action-link a {
display: inline-block;
font-weight: 600;
padding: 10px 20px;
-webkit-box-sizing: border-box;
-moz-box-sizing: border-box;
-ms-box-sizing: border-box;
-o-box-sizing: border-box;
box-sizing: border-box;
}
a.themebutton {
color: #FFF;
font-weight: 400;
text-transform: uppercase;
-webkit-border-radius: 4px;
-moz-border-radius: 4px;
-ms-border-radius: 4px;
-o-border-radius: 4px;
border-radius: 4px;
}
a, a:visited {
text-decoration: none;
}
.themebutton, button, html input[type="button"], input[type="reset"], input[type="submit"] {
color: #FFF;
font-weight: 400;
text-transform: uppercase;
text-align: center;
background: #13aff0;
border: none;
-webkit-transition: all 0.3s ease;
-moz-transition: all 0.3s ease;
-ms-transition: all 0.3s ease;
-o-transition: all 0.3s ease;
transition: all 0.3s ease;
-webkit-transition: -webkit-box-shadow 0s;
-moz-transition: -moz-box-shadow 0s;
-ms-transition: -ms-box-shadow 0s;
-o-transition: -o-box-shadow 0s;
transition: box-shadow 0s;
-webkit-border-radius: 4px;
-moz-border-radius: 4px;
-ms-border-radius: 4px;
-o-border-radius: 4px;
border-radius: 4px;
}
a {
color: #13aff0;
cursor: pointer;
text-decoration: none;
outline: 0 none;
-webkit-transition: all 0.3s ease;
-moz-transition: all 0.3s ease;
-ms-transition: all 0.3s ease;
-o-transition: all 0.3s ease;
transition: all 0.3s ease;
}

</style>
