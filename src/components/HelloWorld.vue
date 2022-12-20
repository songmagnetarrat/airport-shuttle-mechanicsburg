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
    <br>
    <div class="action-link one_fourth last">
       <a class="themebutton" href="https://relaxandridecarlisle.com/book-now/">Book Today</a>
    </div>

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
font-weight: bold;
letter-spacing: .5px;
background-color: #338ea6;
-webkit-border-radius: 35px;
-moz-border-radius: 35px;
-ms-border-radius: 35px;
-o-border-radius: 35px;
border-radius: 35px;
-webkit-transition: all .3s ease;
-moz-transition: all .3s ease;
-ms-transition: all .3s ease;
-o-transition: all .3s ease;
transition: all .3s ease;
}
.action-link a {
display: inline-block;
font-weight: bold;
padding: 10px 20px;
-webkit-box-sizing: border-box;
-moz-box-sizing: border-box;
-ms-box-sizing: border-box;
-o-box-sizing: border-box;
box-sizing: border-box;
}
a.themebutton {
color: #FFF;
font-weight: bold;
text-transform: uppercase;
-webkit-border-radius: 25px;
-moz-border-radius: 25px;
-ms-border-radius: 25px;
-o-border-radius: 25px;
border-radius: 25px;
}

a.themebutton:hover {
background-color: #1e1e1e;
color: #fff;
}
.themebutton:hover, button:hover, html input[type="button"]:hover, input[type="reset"]:hover, input[type="submit"]:hover {
-webkit-box-shadow: inset 0 0 0 30px rgba( 0, 0, 0, 0.10);
-moz-box-shadow: inset 0 0 0 30px rgba( 0, 0, 0, 0.10);
-ms-box-shadow: inset 0 0 0 30px rgba( 0, 0, 0, 0.10);
-o-box-shadow: inset 0 0 0 30px rgba( 0, 0, 0, 0.10);
box-shadow: inset 0 0 0 30px rgba( 0, 0, 0, 0.10);
}


a, a:visited {
text-decoration: none;
}
.themebutton, button, html input[type="button"], input[type="reset"], input[type="submit"] {
color: #FFF;
font-weight: bold;
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

#introaction-core .one_fourth, #outroaction-core .one_fourth, .sc-action-core .one_fourth {
float: none;
text-align: center;
width: 100%;
}

.last {
clear: right;
margin-right: 0px !important;
}

.action-link {
text-align: center;
padding: 0;
}

</style>
