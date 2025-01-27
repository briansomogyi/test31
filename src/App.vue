<template>
  <div class="flex min-h-screen">
    <SidebarComponent />
    <div class="flex-1 flex flex-col">
      <HeaderComponent />
      <MainContent />
    </div>
  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue'
import SidebarComponent from './components/SidebarComponent.vue'
import MainContent from './components/MainContent.vue'

export default {
  name: 'App',
  components: {
    HeaderComponent,
    SidebarComponent,
    MainContent,
  },
}
</script>

<style>
@import url("./assets/tailwind.css");
</style>