<template>
    <div id="game-environment">
        <a-scene>
            <a-entity camera="userHeight: 1.6" look-controls></a-entity>
            <a-sphere position="0 1.25 -5" :radius="radius" color="#EF2D5E"></a-sphere>
            <a-box position="-1 0.5 -3" rotation="0 45 0" width="1" height="1" depth="1" color="#4CC3D9"></a-box>
            <a-cylinder position="1 0.75 -3" radius="0.5" height="1.5" color="#FFC65D"></a-cylinder>
            <a-sky color="#ECECEC"></a-sky>
        </a-scene>
    </div>
</template>

<script>

</script>
