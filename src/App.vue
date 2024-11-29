<script setup>
import coracao from "./assets/coracao.png"

</script>

<template>
  <header>
  <h1>CodeLab</h1>
  <input type="text">
  </header>
  <main>
    <section>
      <div>
      <p>17 de ago, 2024</p>
      <img :src="coracao" alt="">
      </div>
      <h2>O que é linguagem de programação? Conheça as principais</h2>
      <h3>Uma das mais populares vertentes da tecnologia da informação, a área de programação segue tendo muita demanda de trabalho justamente pela velocidade com que dispositivos tecnológicos vêm avançando.</h3>
    </section>

    <section>
      <div>
      <p>17 de ago, 2024</p>
      <img :src="coracao" alt="">
      </div>
      <h2>O que é linguagem de programação? Conheça as principais</h2>
      <h3>Uma das mais populares vertentes da tecnologia da informação, a área de programação segue tendo muita demanda de trabalho justamente pela velocidade com que dispositivos tecnológicos vêm avançando.</h3>
    </section>

    <section>
      <div>
      <p>17 de ago, 2024</p>
      <img :src="coracao" alt="">
      </div>
      <h2>O que é linguagem de programação? Conheça as principais</h2>
      <h3>Uma das mais populares vertentes da tecnologia da informação, a área de programação segue tendo muita demanda de trabalho justamente pela velocidade com que dispositivos tecnológicos vêm avançando.</h3>
    </section>
  </main>
</template>

<style scoped lang="scss">
header{
  background-color: #17171A;
  color: #E07B67;
  font-family: "Space Grotesk", sans-serif;
}

div{
  background-color: #17171A;

  p{
    color: #E07B67;
    font-family: "Inter", serif;
  }
}

section{
  background-color: #17171A;
  
  h2{
    color: white;
    font-family: "Space Grotesk", sans-serif;
  }
  
  h3{
    color: #AFABB6;
    font-family: "Inter", serif;
  }

}
</style>
