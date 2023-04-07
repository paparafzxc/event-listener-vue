<template>
<Nav />
<div class="container-fluid">
  <div class="row"> 
<Menu />
    <main class="col-md-9 ms-sm-auto col-lg-10 px-md-4">
        <router-view></router-view>
    </main>
  </div>
</div>
</template>

<script>
import Menu from '@/components/Menu.vue';
import Nav from '@/components/Nav.vue';
export default{
    // eslint-disable-next-line vue/multi-word-component-names
    name: "Admin",
    components: { 
        Menu,
        Nav
    }
   
}
</script>