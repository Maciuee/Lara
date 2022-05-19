<template>
<div class="container">
Spa component<br>
<router-link :to="{ name: 'home' }" >Home</router-link>|
<router-link :to="{ name: 'login' }" >Login</router-link>|
<router-link :to="{ name: 'dashboard' }" >Dashboard</router-link><br>
<router-view></router-view>
</div>
</template>
<script>
 export default { }
</script>