<template>
    <main id="section">  
        <img src="../assets/lua.jpg" alt="">
        <div class="content">
            <h2>Lua</h2>
            <p>
                A Lua é o único satélite natural da Terra e o quinto maior do Sistema Solar.
                 É o maior satélite natural de um planeta no sistema solar em relação ao tamanho 
                 do seu corpo primário, tendo 27% do diâmetro e 60% da densidade da Terra, o 
                 que representa ¹⁄₈₁ da sua massa. 
            </p>
        </div>
    </main>
    
</template>

<script>
export default {

}
</script>

<style scoped>

#section {
    width: 70vw;
    height: 80vh;
   display: flex;
   margin: auto;
   justify-content: space-around;
   align-items: center;
   color: white;
}
img {
    width: 400px;
    height: 400px;
}

.content {
    width: 400px;
    height: 50%;
}
.content h2 {
    font-size: 30px;
    border-bottom: 2px solid white;
}
.content p {
    font-size: 20px;
    padding: 15px;
}

</style>