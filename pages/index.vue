<template>
  <div>
    <main-menu></main-menu>
  </div>
</template>

<script>
  import MainMenu from '~/components/menu/Main.vue';
  export default {
    components: {
      MainMenu
    },

    head: {
      title: 'Dashboard'
    },
  }
</script>
