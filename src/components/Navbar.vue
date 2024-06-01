<script setup>
   import gitHubIcon from './icons/gitHubIcon.vue';
</script>

<template>
    <nav>
        <div class="navbar">
            <gitHubIcon class="github-icon" />
            <h1>Nnamuka01's Github</h1>
        </div>
    </nav>
</template>

<style scoped>

.navbar {
  display: flex;
  align-items: center;
  gap: 10px;
  color: #fff;
  justify-content: center;
  background-color: #96D6D6;
  text-align: center;
  padding: 20px;
  margin-bottom: 20px;
}

.github-icon {
  font-size: 3rem;
}

</style>