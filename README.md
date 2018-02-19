# hello-world
First repository
Voici mes premiers pas dans le monde de la programmation. 
<script src="https://aframe.io/releases/0.6.0/aframe.min.js"></script>
<script src="https://rawgit.com/jeromeetienne/ar.js/master/aframe/build/aframe-ar.js"></script>
<script>THREEx.ArToolkitContent.baseURL = ‘https://rawgit.com/jeromeetienne/ar.js/master/three.js/’</script> 
<body style='margin : 0px; overflow: hidden;'>
  <a-scene embedded arttoolkit= ‘sourceType: webcam;’>
    <a-sphere src=https://raw.githubusercontent.com/aframevr/sample-assets/master/assets/images/space/earth_atmos_4096.jpg” radius=”0.5” position=”0 0.5 0” segments-height=”53”> 

</a-scene>
    <!-- create your content here. just a box for now -->
    <a-box position='0 0.5 0' material='opacity: 0.5;'></a-box>
    <!-- define a camera which will move according to the marker position -->
    <a-marker-camera preset=’hiro’></a-marker-camera>
</a-scene>
</body>
