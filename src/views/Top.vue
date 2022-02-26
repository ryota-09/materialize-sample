<template>
  <div class="top">
    <div class="container">
      <CompHeader></CompHeader>
      <CompPhoto></CompPhoto>
    </div>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import CompHeader from "@/components/CompHeader.vue";
import CompPhoto from "@/components/CompPhoto.vue";
@Component({
  components: {
    CompHeader,
    CompPhoto,
  },
})
export default class XXXComponent extends Vue {
  
}
</script>

<style scoped></style>
