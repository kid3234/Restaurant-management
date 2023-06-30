<template>
    <h1>Hello user ,Wellcome on home page</h1>
</template>
<script>
import Header from './Header.vue'

export default {
 name: "Home",
 mounted() {
    let user =localStorage.getItem('user_info');
if(!user){
    this.$router.push({name: 'SignUp'})
}
    
 },
}
</script>
