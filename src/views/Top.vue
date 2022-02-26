<template>
  <div class="top">
    <CompHeader></CompHeader>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import CompHeader from "@/components/CompHeader.vue";
@Component({
  components: {
    CompHeader
  }
})
export default class XXXComponent extends Vue {

}
</script>

<style scoped>

</style>
