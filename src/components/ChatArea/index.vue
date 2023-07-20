<style lang="scss" scoped>
.chat-area {
  height: calc(100vh - 59px - 62px);
  width: calc(100vw - 410px);
  background: $grey-background;
  aut .image {
    background-image: url("../../assets/background.png");
    overflow: auto;
    display: flex;
    flex-direction: column-reverse;
  }
}
</style>

<template>
  <div class="chat-area">
    <div class="image full-width full-height"></div>
  </div>
</template>

<script>
export default {
  name: "ChatArea",
};
</script>
