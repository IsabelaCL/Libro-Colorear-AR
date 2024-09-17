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
        <img
          id="card"
          src="https://cdn.jsdelivr.net/gh/hiukim/mind-ar-js@1.2.5/examples/image-tracking/assets/card-example/card.png"
          crossorigin="anonymous"
        />
        <a-asset-item
          id="avatarModel"
          src="https://cdn.jsdelivr.net/gh/hiukim/mind-ar-js@1.2.5/examples/image-tracking/assets/card-example/softmind/scene.gltf"
          crossorigin
          ></a-asset-item>
      </a-assets>

      <a-camera position="0 0 0" look-controls="enabled: false"></a-camera>
      <a-entity mindar-image-target="targetIndex: 0">
        <a-plane
          src="#card"
          position="0 0 0"
          height="0.552" width="1"
          rotation="0 0 0"></a-plane>
        <a-gltf-model
          rotation="0 0 0 "
          position="0 0 0.1"
          scale="0.005 0.005 0.005"
          src="#avatarModel"
          animation="property: position; to: 0 0.1 0.1; dur: 1000; easing: easeInOutQuad; loop: true; dir: alternate"></a-gltf-model>
      </a-entity>
    </a-scene>
  </div>
</template>
