<template>
    <div>
        <header class="header">
            <div class="logo"></div>
            <ul class="links">

                <router-link to="/home">
                    <div class="div_link">
                        <div class="icn_cogu"></div><li>Tipos de Cogumelos</li>
                    </div>
                    
                </router-link>

                <router-link to="/contato">
                    <div class="div_link">
                        <div class="icn_seta"></div><li>Contato</li>
                    </div>
                </router-link>

            </ul>
        </header>
        
    </div>
</template>

<script>
export default {
    nome:"Header"
}
</script>

<style>
.div_link{
    display: flex;
    align-items: center;
}

.icn_seta{
    height:30px;
    width: 30px;

    background: url('../assets/ssssss.svg') no-repeat;
    
}
.icn_cogu{
    height:30px;
    width: 30px;

    background: url('../assets/cccccc.svg') no-repeat;
    
}
*{
    padding: 0px;
    margin: 0px;
    box-sizing: border-box;
    list-style: none;
    outline-style: none;
    text-decoration: none;
    font-family: 'Zen Kurenaido', sans-serif;
}
body{
    background: #faf8f8;
}
.header{
    width: 100%;
    height: 250px;

    display:flex;
    align-items: center;
    justify-content: space-between;
    padding: 20px 50px;
    margin-bottom: 20px;
}
.logo{
    height: 150px;
    width: 350px;

    background: url('../assets/lh.svg') no-repeat;
}


.links li{
    font-family: 'Zen Kurenaido', sans-serif;
    padding: 20px;
    font-size: 1.8rem;
    color: #280000;
    margin: 0 20px;
    

}
.links{
    display: flex;
}

.router-link-active::after{
    content: '';
    display:block;

    width: 100%;
    height: 5px;
    background-color: #ff7777;
    margin-top: 5px;
    border-radius: 5px;

}
</style>