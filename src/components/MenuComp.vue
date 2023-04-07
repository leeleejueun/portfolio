<template>
    <div class="header">
        <router-link to="/" @click="closeMenu" class="logo">
            <div>JE</div>
        </router-link>
        <button @click="showMenu = !showMenu" class="menu">MENU</button>
        <ul v-if="showMenu" class="menuList">
            <li><router-link to="/" @click="closeMenu">Home</router-link></li>
            <li><router-link to="/works" @click="closeMenu">Works</router-link></li>
            <li><router-link to="/about" @click="closeMenu">About</router-link></li>
            <li><router-link to="/contact" @click="closeMenu">Contact</router-link></li>
        </ul>
    </div>
</template>

<script>
export default {
    data() {
        return{
            showMenu:false
        }
    },
    methods: {
        closeMenu() {
            this.showMenu = false
        }
    }
    
}
</script>
<style scoped lang="scss">
.header{
    display: flex;
    justify-content: space-between;
    padding: 50px 100px;
    position: fixed;
    top: 0;
    left: 0;
    width: 100vw;
    height: 150px;
    transition: top 0.2s ease-in-out;
    .logo{
        font-size: 50px;
        font-family: 'Bebas Neue', cursive;
        color: #252C35;
    }
}
</style>