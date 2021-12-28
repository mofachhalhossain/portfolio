<script>
import SidebarLink from './SidebarLink'
import { collapsed, toggleSidebar, sidebarWidth } from './state'

export default {
  props: {},
  components: { SidebarLink },
  setup() {
    return { collapsed, toggleSidebar, sidebarWidth }
  }
}
</script>

<template>

  <div class="sidebar" :style="{ width: sidebarWidth }">

    <SidebarLink to="/" icon="fas fa-home">Main</SidebarLink>
    <SidebarLink to="/projects" icon="fas fa-database">Projects</SidebarLink>
    <SidebarLink to="/skills" icon="fas fa-feather-alt">Skills</SidebarLink>
    <SidebarLink to="/learning" icon="fas fa-edit">Learning</SidebarLink>
    <SidebarLink to="/catch_me" icon="far fa-hand-point-right">Catch Me</SidebarLink>

    <span
      class="collapse-icon"
      :class="{ 'rotate-180': collapsed }"
      @click="toggleSidebar"
    >
      <i class="fas fa-angle-double-left" />
    </span>
  </div>
</template>

<style>
:root {
  --sidebar-bg-color: -moz-linear-gradient(top, #1e5799 0%, #2989d8 50%, #207cca 51%, #7db9e8 100%);
  --sidebar-item-hover: #707259;
  --sidebar-item-active: #393a39;
}
</style>

<style scoped>
.sidebar {
  color: white;
  background-color: var(--sidebar-bg-color);
  float: left;
  position: fixed;
  padding: 0.5em;
  top: 0;
  left: 0;
  bottom: 0;
  margin-top: 9rem;
  margin-bottom: 14rem;
  z-index: 1;
  display: flex;
  flex-direction: column;
  transition: .6s ease;
}

.sidebar h1 {
  height: 2.5em;
}

.collapse-icon {
  position: absolute;
  bottom: 0;
  padding: 0.75em;

  color: rgba(255, 255, 255, 0.7);

  transition: 0.2s linear;
}

.rotate-180 {
  transform: rotate(180deg);
  transition: 0.2s linear;
}
@media screen and (max-width: 768px) {
  .sidebar {
    width: 50vw;
    position: fixed;
    top: 0;
    left: 0;
    bottom: 0;
    z-index: 1;
    display: flex;
    flex-direction: column;
    transition: .6s ease;
    margin-top: 9rem;
    margin-bottom: 5rem;
  }

  .sidebar h1 {
    height: 2.5em;
  }

  .collapse-icon {
    position: absolute;
    bottom: 0;
    padding: 0.75em;

    color: rgba(255, 255, 255, 0.7);

    transition: 0.2s linear;
  }

  .rotate-180 {
    transform: rotate(180deg);
    transition: 0.2s linear;
  }
}
  
</style>
