<template>
  <div class="fixed-button">
     <div class="fixed-action-btn">
  <a class="btn-floating btn-large red">
    <i class="large material-icons">chat</i>
  </a>
  <ul>
  <p class="btn-floating red">ここにテキストが入ります。</p>
  </ul>
</div>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
@Component
export default class CompFixedButton extends Vue {

}
</script>

<style scoped>

</style>
