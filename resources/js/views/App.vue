<template>
    <div>
        <router-link to="/">Home</router-link>
        <router-link to="/about">About</router-link>
        <!-- Dynamic view based on routing system here -->
        <router-view></router-view>
    </div>
</template>

<script>
export default {

};
</script>
