<template>
  <header>
    <div class="mynav">
      <ul>
        <li v-for="nav in navList"> {{ nav }}</li>
    </ul>
  </div>
    
  </header>
  <RouterView />
</template>

<script>
export default {
  data() {
    return {
      navList:['About me', 'Resume', 'Projects', 'Contact'],
    };
  },
  methods: {

  }
};
</script>

<style scoped>
.mynav{
  width: 100%;
  height: 60px;
  border: 1px solid #000;
}
</style>
