<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Feefo Places</title>
<script type='text/javascript' src='https://api.feefo.com/api/assets/js-places-integration/feefo-js-places-integration.js'></script>
</head>
<body>
<div id="FPI_Destination"></div>
<script type='text/javascript'>
var feefo = new Feefo.PlacesIntegration({
debug: true,
destination: document.getElementById('FPI_Destination'),
merchantIdentifier: 'gray-line',
}); 
</body>