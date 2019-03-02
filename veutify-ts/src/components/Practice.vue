<template>
  <div class="sample">
    is pug ranning? yes!!  
  </div>
</template>

<script lang="ts">
import { Vue, Component } from "vue-property-decorator";
console.log("%c here is field :", "background-color:lightpink");

@Component
export default class extends Vue {
  public created() {
    console.log("%c created!! :", "background-color:lightblue");
  }
}
</script>

<style lang="sass" scoped>
  .sample
    background-color: #ababab
</style>

