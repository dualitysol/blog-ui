<template>
  <v-container>
    <v-form>
      <register-form />
    </v-form>
  </v-container>
</template>

<script>
import RegisterForm from "../components/auth/RegisterForm.vue";
import { defineComponent } from "vue";

export default defineComponent({
  components: {
    RegisterForm,
  },
});
</script>
