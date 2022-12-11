<template>
  <div>
    <Nav/>
    <Header/>
    <WeProvide/>    
  </div>
</template>

<script>

import Nav from '~/components/Nav';
import Header from '~/components/Header';
import WeProvide from '~/components/Home/WeProvide';

export default {  
  name: 'Home',
  components: {
    Nav,
    Header,
    WeProvide
  }
}

</script>
