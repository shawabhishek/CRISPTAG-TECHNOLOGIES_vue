<template>
<div>
  <UpperCase/>
</div>
</template>

<script>
import UpperCase from './components/uppercase'
export default {
  name: 'App',
  components: {
    UpperCase
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=BioRhyme:wght@700&display=swap');
  *{
  width:300px;
	padding:20px;
  padding-right: 10px;
	margin:10px;
	background: #FFF;
	border-radius: 10px;
  }
  body{
    font-family: 'BioRhyme', serif;
    line-height: 1.4;
  }
</style>