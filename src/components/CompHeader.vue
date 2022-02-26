<template>
  <div class="header">
    <div class="container">
      <!-- この部分はヘッダー -->
      <nav>
        <div class="nav-wrapper blue lighten-1">
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
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
@Component
export default class CompHeader extends Vue {}
</script>

<style scoped></style>
