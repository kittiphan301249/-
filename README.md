<!DOCTYPE HTML>
  <html>
    <head>
        <meta charset="UTF-8">
        <title>Create Map Sample | Longdo Map</title>
        <style type="text/css">
          html{
            height:100%;
          }
          body{
            margin:0px;
            height:100%;
          }
          #map {
            height: 100%;
          }
        </style>

        <script type="text/javascript" src="https://api.longdo.com/map/?key=[YOUR-KEY-API]"></script>
        <script>
          function init() {
            var map = new longdo.Map({
              placeholder: document.getElementById('map')
            });
          }
        </script>
    </head>
    <body onload="init();">
        <div id="map"></div>
    </body>
  </html>
Next steps
ตอนนี้ท่านได้สร้างแผนที่พื้นฐานเรียบ
