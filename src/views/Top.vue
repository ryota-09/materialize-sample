<template>
  <div class="top">
    <div class="container">
      <CompHeader></CompHeader>
      <CompPhoto></CompPhoto>
      <CompParallax></CompParallax>
      <CompTab></CompTab>
    </div>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import CompHeader from "@/components/CompHeader.vue";
import CompPhoto from "@/components/CompPhoto.vue";
import CompParallax from "@/components/CompParallax.vue";
import CompTab from "@/components/CompTab.vue";

@Component({
  components: {
    CompHeader,
    CompPhoto,
    CompParallax,
    CompTab
  },
})
export default class XXXComponent extends Vue {

}
</script>

<style scoped></style>
