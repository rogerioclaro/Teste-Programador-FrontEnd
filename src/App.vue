<template>
  <div>
    <sidebar-menu-AgroCP
      @busca-input-emit="busca"
    />
  </div>
  
</template>

<script>
import SidebarMenuAgroCP from "../src/Componentes/Menu.vue"

export default {
  name: "App",
  components: {
    SidebarMenuAgroCP,
  },
  methods: {
    busca(val) {
      
    }
  }
}
</script>

<style></style>

