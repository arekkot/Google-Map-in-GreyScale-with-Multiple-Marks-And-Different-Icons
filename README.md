# Google-Map-in-GreyScale-with-Multiple-Marks-And-Different-Icons
Google Map in GreyScale with Multiple Marks And Different Icons

// Define your locations: HTML content for the info window, latitude, longitude
      var locations = [
      ['name', X, Y]
      ];
// Define featureType, elementType, stylers - with Greyscale etc.
      var style 

 // Setup the different icons and shadows
      var iconURLPrefix = prefix for href with images
      var icons - localization of images
      examples:
      'http://maps.google.com/mapfiles/kml/paddle/stop.png' or iconURLPrefix + 'stop.png'

//Predefined options for map
      var map

//Window with information
      var infowindow
      
// Add the markers and infowindows to the map

// Icon Counter. We only have a limited number of possible icon colors, so we may have to restart the counter

// function autoCenter()

// SET THE MAP TYPE - witch it's make greyscale of our map
				var mapType = new google.maps.StyledMapType(style, {name:"Grayscale"});    
				map.mapTypes.set('grey', mapType);
				map.setMapTypeId('grey');
