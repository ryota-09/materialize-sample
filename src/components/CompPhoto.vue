<template>
  <div class="photo-section">
    <section class="section" id="photos">
      <div class="row">
        <div class="col s12 l4">
          <img src="/img/bread-1284438_1920.jpg" alt="" class="responsive-img materialboxed">
        </div>
        <div class="col s12 l6 offset-l1">
          <h2 class="indigo-text text-darken-4">subTitle</h2>
          <p>ここにテキストが入ります。ここにテキストが入ります。ここにテキストが入ります。ここにテキストが入ります。</p>
        </div>
      </div>
      <div class="row">
        <div class="col s12 l4 push-l7 offset-l1">
          <img src="/img/bread-1284438_1920.jpg" alt="" class="responsive-img materialboxed">
        </div>
        <div class="col s12 l6 pull-l5 right-align">
          <h2 class="indigo-text text-darken-4">subTitle</h2>
          <p>ここにテキストが入ります。ここにテキストが入ります。ここにテキストが入ります。ここにテキストが入ります。</p>
        </div>
      </div>
      <div class="row">
        <div class="col s12 l4">
          <img src="/img/bread-1284438_1920.jpg" alt="" class="responsive-img materialboxed">
        </div>
        <div class="col s12 l6 offset-l1">
          <h2 class="indigo-text text-darken-4">subTitle</h2>
          <p>ここにテキストが入ります。ここにテキストが入ります。ここにテキストが入ります。ここにテキストが入ります。</p>
        </div>
      </div>
    </section>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
@Component
export default class CompPhoto extends Vue {
}
</script>
<style scoped>

</style>
