<template>
  <div>
    <div class="row">
      
      <div class="col-8">
                  
        <div class="titulo">Muscarina</div>
        <div class="desc">Com efeitos de perda de consciêcia e estimulador do sistema nervoso irreverssíveis.</div>
        <div class="desc_abaixo">esquisas da distinção do efeito autonômico dos referidos nas experiências xamânicas e de viajantes europeus apontam para presença e efeito de outras substâncias nele contidas, mais especificamente o ácido ibotênico e muscimol com propriedades psicodislépticas.</div>
        <div class="botao div_link"><div class="ico_exc"></div><p>Informações</p></div>

      </div>
      <div class="col-4">
        <div class="cogu-1"></div>
      </div>

    </div>
  </div>
</template>

<script>


export default {
  name: 'Home',
}
</script>
<style>
.ico_exc{
  width: 30px;
  height: 30px;
  background: url('../assets/icn_exc.svg') no-repeat;
}
.botao{
  margin: 20px auto;
  width: 200px;
  height: 50px;
  background-color: #77ffff;
  font-family: 'Roboto', sans-serif;
  font-size: 1.5rem;
  text-align: center;
  padding: 5px;
  border-radius: 1rem;
  box-shadow: 5px 10px 30px 0px rgba(15, 10, 10, 0.445);
  cursor: pointer;
  padding: 20px;
}
.botao:hover{
    background-color: #54d6d6;
}

.titulo{
  font-size: 4rem;
  color: rgb(255, 107, 107);
  margin-bottom: 10px;
  text-align: center;
}

.titulo::after{
  content:'';
  display: block;

  width: 20%;
  height: 2px;
  background-color: #f77;
  margin: 0 auto;

}
.desc{
  font-family: 'Roboto', sans-serif;
  font-size: 2rem;
  color: #290000;
  line-height: 100%;
  margin-bottom: 10px;
}

.desc::after{
  content:'';
  display: block;

  width: 10%;
  height: 5px;
  background-color: #290000;
  margin-top: 5px;
}


.desc_abaixo{
  font-family: 'Roboto', sans-serif;
  font-size: 1rem;
}


.cogu-1{
  width: 400px;
  height: 400px;

  background: url('../assets/cogu1.svg') no-repeat;
  margin: 10px;
}
</style>