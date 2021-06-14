<template>
<Header/>
<Content/>
<Footer/>
</template>

<script>
import { defineComponent } from "vue";
import Header from '@/components/Header.vue';
import Content from '@/components/Content.vue';
import Footer from '@/components/Footer.vue';

export default defineComponent({
  name: 'Home',
  components: {
    Header,
    Content,
    Footer

  }

})
</script>

<style>
#header{
  height: 10rem;
}

</style>