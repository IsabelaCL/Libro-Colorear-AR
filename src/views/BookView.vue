<script setup>
  import 'aframe'
  import '@ar-js-org/ar.js/aframe/build/aframe-ar'
</script>
<template>
  <div style="height: 100vh; width: 100vw;">
    <a-scene embedded arjs>
      <a-assets>
        <a-asset-item
          id="avatarModel"
          src="./scene.gltf"
          crossorigin
          ></a-asset-item>
      </a-assets>
      <a-marker id="arMarker" preset="hiro">
        <a-gltf-model
          rotation="0 0 0 "
          position="0 0 0.1"
          src="#avatarModel"
        ></a-gltf-model>
      </a-marker>
      <a-entity camera></a-entity>
    </a-scene>
  </div>
</template>
