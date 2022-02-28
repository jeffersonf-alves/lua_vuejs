<template>
    <div id="header">
        <Button>Home</Button>
        <Button>Sobre</Button>
    </div>
</template>

<script>
import Button from '../components/Button.vue'

export default {
    components: {
        Button
    }
}
</script>

<style>

#header {
    margin: 0;
    padding: 0;
    background-color:black;
    height: 10vh;
    display: flex;
    align-items: center;
}


</style>
