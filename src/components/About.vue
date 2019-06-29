<template>
  <div class="about">
    <h1>Hello {{ their_name }}, this is an about page</h1>
    <p>This is Sujana’s To Do list developed in Vue.Js to learn Vue.Js</p>
  </div>
</template>

<script>
export default {
  name: 'About',
  data() {
    return {
      their_name: this.$route.params.name
    }
  }
}
</script>