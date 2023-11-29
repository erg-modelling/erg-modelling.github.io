---
layout              : page-fullwidth
header:
  image_fullwidth: FromHPRU_12_Crop.jpg
permalink           : "/2019-maps/london/"
header				: no
title				: "Test page"
---



<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Leaflet Map</title>
    <!-- Include Leaflet CSS and JavaScript files -->
    <link rel="stylesheet" href="https://unpkg.com/leaflet@0.7.7/dist/leaflet.css" />
    <script src="https://unpkg.com/leaflet@0.7.7/dist/leaflet.js"></script>
    <!-- Your custom styles or additional libraries can go here -->
    <style>
        /* Set the size of the map container */
        #map {
            height: 400px;
            width: 100%;
        }
    </style>
</head>
<body>
    <!-- Map container -->
    <div id="map"></div>

    <script>
        // Initialize the map
        var map = L.map('map').setView([51.505, -0.09], 13); // Set the initial center and zoom level

        // Add a tile layer (you can replace this with your own tiles)
        L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
            attribution: '© OpenStreetMap contributors'
        }).addTo(map);

        // Add markers, polygons, etc. as needed

    </script>
</body>




<font size="5">  
    <b>Emissions</b>
</font>  

An essential component of any air pollution model is an accurate emissions inventory.

<br>
<font size="5">  
    <b>Met Data</b>
</font>  

