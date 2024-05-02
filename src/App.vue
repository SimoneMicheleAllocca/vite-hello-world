<script>
import AppTitle from './components/'
export default{ 
  components: {AppTitle},
  
  data() {
  return{
    title:ciao
  }
}
  
}
</script>

<template>
  <AppTitle />
<h1>{{ title }}</h1>
</template>

<style></style>