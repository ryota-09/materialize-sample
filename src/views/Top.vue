<template>
  <div class="top">
    <div class="container">
      <CompHeader></CompHeader>
      <CompFixedButton></CompFixedButton>
      <CompPhoto></CompPhoto>
      <CompParallax></CompParallax>
      <CompTab></CompTab>
      <CompParallax></CompParallax>
      <section class="section">
        <div class="row">
        <div class="col s3 offset-s1">
          <CompCard></CompCard>
        </div>
        <div class="col s3 offset-s1">
          <CompCard></CompCard>
        </div>
        <div class="col s3 offset-s1">
          <CompCard></CompCard>
        </div>
      </div>
      </section>
    </div>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import CompHeader from "@/components/CompHeader.vue";
import CompPhoto from "@/components/CompPhoto.vue";
import CompParallax from "@/components/CompParallax.vue";
import CompTab from "@/components/CompTab.vue";
import CompCard from "@/components/CompCard.vue";
import CompFixedButton from "@/components/CompFixedButton.vue";

@Component({
  components: {
    CompHeader,
    CompPhoto,
    CompParallax,
    CompTab,
    CompCard,
    CompFixedButton
  },
})
export default class XXXComponent extends Vue {

}
</script>

<style scoped></style>
