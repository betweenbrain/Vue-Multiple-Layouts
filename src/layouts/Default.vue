<script>
import NavBar from '@/components/NavBar';
import SideBar from '@/components/SideBar';
import FooterBar from '@/components/FooterBar';

export default {
  components: {
    NavBar,
    SideBar,
    FooterBar,
  },
};
</script>

<template>
<div>
    <section>
        <slot/>
    </section>
    <side-bar/>
        <nav-bar/>

    <footer-bar/>
</div>
</template>
