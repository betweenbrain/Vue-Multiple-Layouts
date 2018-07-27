<script>
import NavBar from '@/components/NavBar';
import FooterBar from '@/components/FooterBar';

export default {
  components: {
    NavBar,
    FooterBar,
  }
};
</script>

<template>
<div>
    <nav-bar/>
    <section>
        <slot/>
    </section>
    <footer-bar/>
</div>
</template>
