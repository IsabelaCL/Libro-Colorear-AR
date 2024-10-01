<script setup>
  import 'mind-ar/dist/mindar-image.prod'
  import 'aframe'
  import 'mind-ar/dist/mindar-image-aframe.prod'

</script>
<template>
  <div style="height: 100vh; width: 100vw;">
    <a-scene
      mindar-image="
        imageTargetSrc: ./targets.mind;
        uiScanning: no
      "
      embedded
      vr-mode-ui="enabled: false"
      device-orientation-permission-ui="enabled: false"
    >
      <a-assets>
        <a-asset-item
          id="avatarModel"
          src="./scene.gltf"
          crossorigin
          ></a-asset-item>
      </a-assets>

      <a-camera position="0 0 0" look-controls="enabled: false"></a-camera>
      <a-entity mindar-image-target="targetIndex: 0">
        <a-gltf-model
          rotation="0 0 0 "
          position="0 0 0.1"
          src="#avatarModel"
        ></a-gltf-model>
      </a-entity>
    </a-scene>
  </div>
</template>
