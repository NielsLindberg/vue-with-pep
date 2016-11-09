<template>
  <div class="dragger">
    <img draggable="false" src="../assets/logo.png" class="map"></img>
  </div>
</template>

<script>
import $ from 'jquery'
import pep from 'jquery.pep'

console.log($)
console.log(pep)
export default {
  name: 'dragger',
  created: onCreate
}
function onCreate () {
  $(document).ready(() => {
    $('.map').pep({constrainTo: 'window'})
  })
}
</script>

<style>
</style>
