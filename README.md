This is a Firefox OS App that uses the following external libraries  
Brick.js https://developer.mozilla.org/en-US/Apps/Developing/Web_components  
Three.js http://threejs.org/  
A modified version of the Google Globe.js WebGl Experiment - https://github.com/dataarts/webgl-globe/tree/master/globe  
and Cordova http://cordova.apache.org/  

If you want to run this you will need to have Cordova installed and a project created  

    $ cordova create test com.example.test TestApp  
cd to the test directory and delete the www folder      
checkout the code into this directory.  

    git clone https://github.com/JasonWeathersby/cordovasample www     

The Geolocation example uses Three.js and Globe.js and functions better on later versions of Firefox OS 1.2>  

See Hacks Blog Post for more details  