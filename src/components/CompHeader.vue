<template>
  <div class="header">
      <!-- この部分はヘッダー -->
      <nav>
        <div class="nav-wrapper orange lighten-3">
          <a href="#" class="brand-logo">Title</a>
          <!-- この部分がハンバーガーメニュー -->
          <a href="" class="sidenav-trigger" data-target="mobile-menu"></a>
          <ul id="nav-mobile" class="right hide-on-med-and-down">
            <li><a href="#">My Page</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Contact</a></li>
          </ul>
        </div>
      </nav>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
@Component
export default class CompHeader extends Vue {}
</script>

<style scoped>
.header{
  background: url(/img/bakery-1868925_1920.jpg);
  background-size: cover;
}
</style>
