# Eilert-Forland-js-frameworks-ma-1-level-2


1. add the Following code to the <head> of your document.
<link type="text/css" rel="stylesheet" href="css/slider.css" />                  
<script src="//ajax.googleapis.com/ajax/libs/jquery/1.11.0/jquery.min.js"></script>
<script src="js/slider.js"></script>

2.Add markup to the body
  <div class="carousel">
        <img src="images/cat.jpg" alt="Caption 1" />
        <img src="images/dog.jpg" alt="Caption 2" />
        <img src="images/horse.jpg" alt="Caption 3" /> ...
    </div>
    
3.Call the plugin
$(document).ready(function() {
  $(".carousel").slider();
});
