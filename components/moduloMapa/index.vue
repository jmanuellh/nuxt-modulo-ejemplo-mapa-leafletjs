<template lang="pug">
  div
    div(id="map-wrap" style="height: 100vh")
      no-ssr
        l-map(:zoom=15 :center="[25.8682,-103.2429]" style="z-index:0")
          l-tile-layer( url="http://{s}.tile.osm.org/{z}/{x}/{y}.png")
          l-marker(:lat-lng="[25.8682,-103.2429]")
</template>
