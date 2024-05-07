<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {box-sizing: border-box}

/* Set height of body and the document to 100% */
body, html {
  height: 100%;
  margin: 0;
  font-family: Arial;
}

/* Style tab links */
.tablink {
  background-color: #123B69;
  color: 000000;
  float: left;
  border: none;
  outline: none;
  cursor: pointer;
  padding: 30px 35px;
  font-size: 20px;
  width: 25%;
}

.tablink:hover {
  background-color: #B39BC8;
}

/* Style the tab content (and add height:100% for full page content) */
.tabcontent {
  color: black;
  display: none;                                                   
  padding: 100px 20px;
  height: 100%;
}

#Home {background-color: #D4A59A;}
#Introduction {background-color: #D4A59A;}
#Contact {background-color: #D4A59A;}
#About {background-color: #D4A59A;}
</style>
</head>
<body>

<button class="tablink" onclick="openPage('Home', this, '#AC3B61')">Home</button>
<button class="tablink" onclick="openPage('Introduction', this, '#AC3B61')" id="defaultOpen">Main Problem</button>
<button class="tablink" onclick="openPage('Contact', this, '#AC3B61')">Brain Storming Techniques</button>
<button class="tablink" onclick="openPage('About', this, '#AC3B61')">Main Solution</button>

<div id="Home" class="tabcontent">
<style>
p.ex1 {
  font-size: 40px;
}
p.ex2 {
  font-size: 60px;
}
</style>
</head>
<body>

<p class="ex1"><h1 style="text-align:center;"This is a bigger paragraph.</p>
<p class="ex2">LIFELABS QUARTER 4</p>
<p class="ex2">GROUP 3</p>
  </p><h1 style="text-align:center;">Group Members</h1>
  <p style="text-align:center;">Chelszy Marie S. Caudrante<br>Chad Andrew Camba<br>Jusper Gutierrez<br>Zildjian Marley Nolasco</p>
</div>

<div id="Introduction" class="tabcontent">
<style>
p.ex1 {
  font-size: 30px;
}
p.ex2 {
  font-size: 70px;
}
</style>
</head>
<body>

<p class="ex1"><h1 style="text-align:center;"This is a bigger paragraph.</p>
<p class="ex2">TYPHOONS</p>
  </p><h1 style="text-align:center;">How do we mitigate the damages of a typhoon?</h1>
  <p style="text-align:center;">

In this website, we would like to spread awareness about the damages and dangers that a typhoon can cause, as well as the ways we can mitigate it.<br> A typhoon could have a severe impact and cause damage in a country. Many people could lose their homes and livelihoods.<br>The typhoon could destroy Filipino crops and houses, resulting in significant costs to the country's agriculture and infrastructure.<br>Floods could reach levels higher than people, almost submerging their houses in water. Most people could become trapped inside their houses<br>due to the high level of flooding.</p>

<img src="typhoon.jpg" alt="Paris" style="width:35%;">

</div>

<div id="About" class="tabcontent">
  </p><h1 style="text-align:center;">PROPOSED SOLUTION</h1>
<img src="ps.jpg" alt="Paris" style="width:35%;">
</div>

<div id="Contact" class="tabcontent">
  <p style="font-size:50px;">5 WHY'S AND MINDMAP</p>

  <meta name="viewport" content="width=device-width, initial-scale=1">
  ​<p style="font-size:25px;">
<img src="bstss.jpg" alt="Paris" style="width:35%;">

<style>

img {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
</style>
</head>
<body>


<script>
function openPage(pageName,elmnt,color) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablink");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].style.backgroundColor = "";
  }
  document.getElementById(pageName).style.display = "block";
  elmnt.style.backgroundColor = color;
}

// Get the element with id="defaultOpen" and click on it
document.getElementById("defaultOpen").click();
</script>
   
</body>
</html> 
