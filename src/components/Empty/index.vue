<style lang="scss" scoped>
.empty {
  height: calc(100vh);
  min-width: 800px;
  width: calc(100vw - 410px);

  background: $empty-background;
  .container {
    h4 {
      width: 350px;
      text-align: center;
      margin: 12px 0px;
      color: $font-empty;
    }

    span {
      width: 450px;
      text-align: center;
      color: $font-gray;
    }
  }
}
</style>

<template>
  <div class="empty">
    <div
      class="container full-width full-height column items-center justify-center"
    >
      <q-img
        src="../../assets/connected.png"
        height="250px"
        width="250px"
      ></q-img>
      <h4>Mantenha o celular conetado</h4>
      <span
        >O WhatsApp conecta ao seu telefone para sincronizar as mensagens. Para
        reduzir o uso de dados, conecte o seu telefone a uma rede Wi-fi.</span
      >
    </div>
  </div>
</template>

<script>
import { defineComponent } from "vue";

export default defineComponent({
  name: "EssentialLink",
});
</script>
