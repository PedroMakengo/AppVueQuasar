<template>
  <div class="container full-height">
    <div>
      <ConversationArea />
    </div>
    <div class="column" v-if="1 === 1">
      <TopBar :title="'Daniel Lopes'" />
    </div>
    <Empty v-else />
  </div>
</template>

<script setup>
import { defineComponent } from "vue";
import Empty from "../components/Empty/index.vue";
import ConversationArea from "../components/ConversationArea/index.vue";
import TopBar from "../components/TopBar/index.vue";
</script>

<style scoped lang="scss">
.container {
  display: flex;
  overflow: hidden;
  min-width: 1200px;
}
</style>
