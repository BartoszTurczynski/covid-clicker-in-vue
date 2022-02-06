<template>
    <div class="navbar">
        <ul>
            <li>COVID CLICKER</li>
            <li>O NAS</li>
            <li>POBIERZ</li>
        </ul>
        <img class="moon" src="../assets/moon-solid.svg" alt="moon">
        <img class="covid" src="../assets/logo.svg" alt="covid">
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
    flex-direction: row;
}
ul li{
    cursor: pointer;
    color: black;
    display: inline-block;
    margin: 4vw;
    font-weight: 600;
    font-size: 1.5em;
}
.covid {
    height: 4em;
    background-color: black;
    border-radius: 50%;
}
.moon{
    height: 3.5em;
    outline: solid black;
    border-radius: 50%;
    outline-offset: 0.5em;
}
</style>