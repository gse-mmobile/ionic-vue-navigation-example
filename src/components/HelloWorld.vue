<template>
  <ion-app>
    <ion-header>

        <ion-navbar>
            <ion-title>Ionic</ion-title>
        </ion-navbar>

    </ion-header>

    <ion-content>

      <ion-button @click="goToDetail">Hello</ion-button>

    </ion-content>
  </ion-app>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  methods: {
    goToDetail () {
      this.$router.push('detail')
    }
  }
}
</script>

<style scoped>

</style>
