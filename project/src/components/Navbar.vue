<template>
    <div class="navbar">
        <ul>
            <li>COVID CLICKER</li>
            <li>O NAS</li>
            <li>POBIERZ</li>
        </ul>
        <img src="../assets/logo.svg" alt="covid">
    </div>
</template>
<script>
export default {
    name: 'Navbar'
}
</script>
<style scoped>
.navbar {
    left: 0;
    background-color: red;
    height: 10vh;
    top: 0;
    position: fixed;
    padding: 0em;
    display: flex;
    width: 100%;
    align-items: center;
    justify-content: space-around;
}
ul{
    
    list-style: none;
    
}
ul li{
    cursor: pointer;
    color: black;
}
img{
    height: 100px;
    background-color: white;
    border-radius: 50%;
}
</style>