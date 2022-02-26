<template>
  <div class="tab-area">
    <section class="section" id="services">
      <div class="row">
        <div class="col s12 l4">
          <h2 class="indigo-text text-darken4">services</h2>
          <p>ここにテキストが入ります。ここにテキストが入ります。ここにテキストが入ります。ここにテキストが入ります。</p>
          <p>ここにテキストが入ります。ここにテキストが入ります。ここにテキストが入ります。ここにテキストが入ります。</p>
        </div>
        <div class="col s12 l6 offset-l2">
        <ul class="tabs">
          <li class="tab col s6">
            <a href="#eatin" class="indigo-text text-darken4">eat in</a>
          </li>
          <li class="tab col s6">
            <a href="#takeout" class="indigo-text text-darken4">take out</a>
          </li>
        </ul>
        <div class="col s12" id="eatin">
            <p class="flow-text indigo-text text-darken4" id="eatin">EAT IN</p>
            <p>ここにテキストが入ります。ここにテキストが入ります。ここにテキストが入ります。ここにテキストが入ります。</p>
            <p>ここにテキストが入ります。ここにテキストが入ります。ここにテキストが入ります。ここにテキストが入ります。</p>
        </div>
        <div class="col s12" id="takeout">
            <p class="flow-text indigo-text text-darken4 offset-s12" id="takeout">TAKE OUT</p>
            <p>ここにテキストが入ります。ここにテキストが入ります。ここにテキストが入ります。ここにテキストが入ります。</p>
            <p>ここにテキストが入ります。ここにテキストが入ります。ここにテキストが入ります。ここにテキストが入ります。</p>
        </div>
      </div>
      </div>
    </section>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
@Component
export default class CompTab extends Vue {

}
</script>

<style>
.tabs .indicator{
  background-color: brown;
}
.tabs .tab a:focus, .tabs .tab a:focus.active{
  background-color: transparent;
}
</style>
