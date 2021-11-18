<template>
    <div id="divmain" >
        <h1>Make Your Burguer</h1>
    </div>
</template>

<script>
export default {
    name: "Banner"
}
</script>

<style scoped>
    #divmain{
        background-image: url('/img/burger.jpg');
        background-position: 0 -250px;
        background-size: cover;
        height: 90vh;
        display: flex;
        align-items: center;
        justify-content: flex-start;
    }
    #divmain h1 {
    color: #fff;
    text-align: center;
    font-size: 60px;
    background-color: #222;
    padding: 20px 40px;
    }
</style>