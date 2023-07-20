<style lang="scss" scoped>
.top-bar {
  min-height: 59px !important;
  background: $grey-whats;
}
.container-avatar {
  width: 90%;
}

.container-action {
  width: 8%;
}
</style>

<template>
  <q-page class="top-bar row items-center justify-between">
    <div class="container-avatar q-ml-md">
      <q-avatar size="40px" class="q-mr-sm">
        <img src="https://i.pravatar.cc/40" alt="" />
      </q-avatar>
      <span>{{ title }}</span>
    </div>
    <div class="container-actions">
      <q-icon name="search" size="22px" color="grey" class="q-r-md"></q-icon>
      <q-icon name="fas fa-ellipsis-v" size="15px" color="grey"></q-icon>
    </div>
  </q-page>
</template>

<!-- filename: TopBar.index.vue -->
<script setup>
import { defineProps } from "vue";

const props = defineProps({
  title: String,
});
</script>
<script>
export default {
  name: "MessageBar",
};
</script>
