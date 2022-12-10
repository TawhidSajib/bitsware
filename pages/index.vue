<template>
  <div>
    <Nav/>
    <Header/>    
  </div>
</template>

<script>

import Nav from '~/components/Nav';
import Header from '~/components/Header';

export default {  
  name: 'Home',
  components: {
    Nav,
    Header
  }
}

</script>
