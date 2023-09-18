# Add-Elementor-Form-Event-Listner
step -1. create a new tag and name it a “eventlistner” Select tag type ” Custom HTML” and paste above code.

Step.2 – Fire the tag on every page of your website.

<script>jQuery( document ).ready(function( $ ){
jQuery( document ).on('submit_success', function(){

window.dataLayer = window.dataLayer || [];
window.dataLayer.push({
'event': 'elementorFormSubmitted'
});
});
});</script>

![image](https://github.com/xeniusdigital/Add-Elementor-Form-Event-Listner/assets/5832613/cc769e62-2b91-4671-ba9e-fd6870dcf82a)

