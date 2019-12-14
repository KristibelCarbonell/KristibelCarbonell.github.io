# Kristibel Carbonell
<h1>Biografía</h1>

<div align="center"> <p><img src="https://scontent.fpac1-2.fna.fbcdn.net/v/t1.0-0/p480x480/80199962_471261753531026_798575673210830848_o.jpg?_nc_cat=104&_nc_ohc=0vsyPilFJSMAQloMhN3TmLUimDbHV8AbM2vpBa3ZGXhb37YWAOJtLMpYw&_nc_ht=scontent.fpac1-2.fna&oh=adaea4dc4f449f3a3dfe70f0ef4d50fd&oe=5E7E3A65" width= "250" height= "400" >
<hr>
<p><strong>Nombre Completo:</strong> Kristibel Carbonel
<p><strong>Fecha Nacimiento:</strong> 12 de febrero de 2001
<p><strong>Edad:</strong> 18 años
<p><strong>Nacionalidad:</strong> Venezolana 
<hr>
<h2>Datos Educativos</h2>
<p><strong>Escuelas:</strong><p>
<p><em>- Primaria: Juan Vicente Camacho </em>
<p><em>- Premedia y media: Juan vicente Camacho. </em>
<p><strong>Universidad:</strong>
<P><em>- Universidad Nacional de Panamá</em>
  <hr>
<h2>Redes Sociales</h2>
<p><strong>Facebook:</strong> <a href="https://www.facebook.com/valentinacarbonell">Valentina Carbonel</a>
<p><strong>Instagram:</strong> <a href="https://www.instagram.com/valentin5a/">Valentin5a</a>
<hr>
<head>
<script>
  <title>location.html</title>

  <meta charset = "UTF-8" />

  <script type = "text/javascript">

  //<![CDATA[



  function getLoc(){

    navigator.geolocation.getCurrentPosition(showMap);

  } // end getLoc



  function showMap(position){

    var lat = position.coords.latitude;

    var long = position.coords.longitude;

    var linkUrl = "http://maps.google.com?q=" + lat + "," + long;

    var mapLink = document.getElementById("mapLink");

    mapLink.href = linkUrl;

    var embedMap = document.getElementById("embedMap");

    embedMap.src = linkUrl + "&z=16&amp;output=embed";

  } // end showMap



  //]]>

  </script>

</head>



<body onload = "getLoc()">

  <h1>Geolocation</h1>



  <p>

    <a id = "mapLink"

       href = "http://maps.google.com">click for a map</a>

  </p>



<iframe id = "embedMap"

        width="800" 

        height="500" 

        frameborder="0" 

        scrolling="no" 

        marginheight="0" 

        marginwidth="0" 

        src= "">

</iframe><br />



