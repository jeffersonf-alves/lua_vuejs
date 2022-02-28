<template>
    <button id="btn">
           <slot></slot>
    </button>
</template>

<script>
export default {
    props:['title-btn']
}
</script>

<style scoped>
#btn {
    height: 29px;
    width: 100px;
    color: white;
    margin-left: 12px;
    border: 2px solid white;
    border-radius: 10px;
}

#btn:hover {
    opacity: 0.8;
    cursor: pointer;
}

</style>