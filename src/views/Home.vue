<template>
  <div class="home">
      <Top />
      <Main />
      <Footer />
  </div>
</template>

<script>
import Top from '../components/Top/Top';
import Main from '../components/Main/Main';
import MyFooter from '../components/MyFooter/MyFooter';


export default {
  name: 'home',
  components: {
      Top,
      Main,
      Footer : MyFooter
  }
}
</script>
