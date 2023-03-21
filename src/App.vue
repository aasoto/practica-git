<script setup>
  import { ref } from "vue";

  import ContentApp from "./components/ContentApp.vue";
  import NavbarLight from "./components/NavbarLight.vue";
  import SidebarLight from "./components/SidebarLight.vue";

  const showSidebar = ref(false);

  const switchSidebar = () => {
    showSidebar.value = !showSidebar.value;
  }
</script>

<template>
  <SidebarLight :showSidebar="showSidebar" :class="showSidebar ? 'block' : 'hidden'"/>
  <NavbarLight :showSidebar="showSidebar" @switchSidebar="switchSidebar"/>
  <ContentApp :showSidebar="showSidebar"/>
</template>

