<template>
  <div class="card-area">
     <div class="row">
    <div class="col s12 m6">
      <div class="card">
        <div class="card-image">
          <img src="/img/bread-1284438_1920.jpg">
          <span class="card-title">Title</span>
          <a class="btn-floating halfway-fab waves-effect waves-light red accent-2 pulse"><i class="material-icons">favorite</i></a>
        </div>
        <div class="card-content ">
          <p>ここにテキストが入ります。</p>
        </div>
      </div>
    </div>
  </div>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
@Component
export default class CompCard extends Vue {

}
</script>

<style scoped>

</style>
