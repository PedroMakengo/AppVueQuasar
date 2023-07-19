<template>
  <q-page class="flex flex-center">
    <div>
      <h5>Acesse o chat</h5>
      {{ email }}
      <q-input
        rounded
        outlined
        v-model="email"
        label="Informe o seu E-mail"
        bg-color="white"
        class="q-mb-md"
      ></q-input>
    </div>
  </q-page>
</template>

<script>
import { defineComponent } from "vue";

export default defineComponent({
  name: "IndexPage",

  data() {
    return {
      email: "",
    };
  },
});
</script>
