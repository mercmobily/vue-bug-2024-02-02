<script setup>
import { RouterView } from 'vue-router'
import ProjectsView from './views/ProjectsView.vue'

// Using RouterView (which will in turn render ProjectView) the problem shows.
// Using <ProjectView> directly, the problem doesn't show.
// The "Problem" is explained in ProjectsView.vuw

</script>


<template>   
  <RouterView/>
  <!--<ProjectView/>-->
</template>
