<template>
  <div class="signup-main">
    <SignUpForm />
  </div>
</template>

<script>  
import SignUpForm from "@/components/SignUpForm.vue";
  export default {
    components: {
      SignUpForm,
    },
    
  }
</script>

<style scoped>

.signup-main {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  background-image: linear-gradient(to right, #fbc2eb 0%, #a6c1ee 100%);
}
</style>