<template>
  <div class="top">
    <div class="container">
      <CompHeader></CompHeader>
      <CompPhoto></CompPhoto>
      <CompParallax></CompParallax>
    </div>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import CompHeader from "@/components/CompHeader.vue";
import CompPhoto from "@/components/CompPhoto.vue";
import CompParallax from "@/components/CompParallax.vue"
@Component({
  components: {
    CompHeader,
    CompPhoto,
    CompParallax
  },
})
export default class XXXComponent extends Vue {

}
</script>

<style scoped></style>
