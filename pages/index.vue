<template>
 <div>
  <h1>Hello World of Programming!</h1>
  <NLink to="/about">
   About Page
  </NLink>
  <br>
  <NLink to="/profile">
   Profile
  </NLink>
 </div>
</template>

<script>
import Logo from '~/components/Logo.vue'
import VuetifyLogo from '~/components/VuetifyLogo.vue'

export default {
  components: {
    Logo,
    VuetifyLogo
  }
}
</script>
