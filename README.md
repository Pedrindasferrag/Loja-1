<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" content="text/css" href="style.css">
    <title>Loja</title>
</head>
<body>
    <header class="header1">
        <div class="header1__logo">
            <a href="#">
                <h1>Lorem Ipsum</h1>
            </a>
        </div>
            <form class="header1__search">
                <input type="search" name=" pesquisa" placeholder="Procurar Roupas Aqui" required>
                <button type="submit">Procurar</button>
            </form>
            <div class="header1__direita">
                <div class="header1__login">
                 <a href="#">
                     <i class="fas fa-user-plus"></i>
                     <h2>Entrar</h2>
                 </a>
                </div>
                <div class="header1__carrinho">
                  <a href="#">
                     <i class="fas fa-shopping-cart"></i>
                        <h2>Carrinho</h2>
                    </a>
                </div>
            </div>
    </header>
    <header class="header2">
        <div class="header2__menu">
            <a href="#">
                <i class="fas fa-bars"></i>
                <h3>Menu Principal</h3>
            </a>
        </div>
        <div class="header2__calcados">
            <a href="#">
                <i class="fas fa-bars"></i>
                <h3>Calçados</h3>
            </a>
        </div>
    </header>
    <main class="main1">

    </main>
    
</body>
</html>

<style>
    *{
    margin: 0;
    padding: 0;
    text-decoration: none;
}
body{
    font-family: sans-serif;
}
/*hEADER1
========================================================================*/
.header1{
    display: flex;
    width: 100%;
    flex-direction: row;
    justify-content: space-around;
    align-items: center;
    padding-top: 1.5%;
    padding-bottom: 1.5%;
    background: #FFD11D;
    align-items: center;
}
.header1__logo{
    transition: all 120ms ease-in;
}
.header1__logo h1{
    display: flex;
    color: rgb(63, 77, 95);
    transform: scale(1);
}
.header1__logo:hover{
    transform: scale(1.1);
}
.header1__search{
    display: flex;
    align-items: center;
    margin-left: -15%;
    margin-right: -15%;
    
}
.header1__search input{
    display: flex;
    font-size: 20px ;
    width: 500px;
    height: 100%;
    border-radius:15px 0px 0px 15px ;
    border-right: none;
    text-align: center;
}
.header1__search button{
    display: flex;
    font-size: 15px;
    padding-top: 2px;
    padding-bottom: 4px;
    padding-right: 5px;
    padding-left: 5px;
    background: #fff;
    border-left: none;
    border-radius: 0px 15px 15px 0px;
    cursor: pointer;
    transition: all 120ms ease-in;
}
.header1__search button:hover{
    background: rgb(63, 77, 95);
    color: #fff;
}
.header1__direita{
    display: flex;
    flex-direction: row;
    padding-right: 1%;
}
.header1__login{
    display: flex;
    padding-right: 10%;
}
.header1__login h2{
    display: flex;
    color: rgb(63, 77, 95);
    transition: all 120ms ease-in;
}
.header1__login h2:hover{
    color: rgb(144, 165, 184);
}
.header1__carrinho{
    display: flex;
}
.header1__carrinho h2{
    display: flex;
    color: rgb(63, 77, 95);
    transition: all 120ms ease-in;
}
.header1__carrinho h2:hover{
    color: rgb(144, 165, 184);
}


/*hEADER2
========================================================================*/
.header2{
    display: flex;
    padding: 10px;
    background: rgb(63, 77, 95);
    align-items: center;
    justify-content: space-around;
    padding-right: 70%;
    padding-left: 12%;
}
.header2__menu h3{
    display: flex;
    color: #fff;
    border: none;
    transform: scale(1);
    transition: all 120ms ease-in;
}
.header2__menu h3:hover{
    transform: scale(1.1);
    border: 1px solid #fff;
    border-radius: 10px;
    padding: 5px;
}
.header2__calcados h3{
    display:  flex;
    color: #fff;
    border: none;
    transform: scale(1);
    transition: all 120ms ease-in;
}
.header2__calcados h3:hover{
    transform: scale(1.1);
    border: 1px solid #fff;
    border-radius: 10px;
    padding: 5px;
}
</style>
