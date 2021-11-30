# FrontEnd1
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <link rel="stylesheet" href="estilo.css">
    <title>Document</title>
</head>

<body>

    <header>
<h1 id= "nome">Conheça Olinda</h1>
<p id= resumo>
   <strong>Olinda</strong> é um município brasileiro do estado de Pernambuco.
    Pertence à Região Metropolitana do Recife, distando seis quilômetros da capital
    pernambucana.
Fundada em 1535, Olinda é a mais antiga entre as cidades brasileiras
declaradas <strong>Patrimônio Histórico e Cultural da Humanidade</strong> pela UNESCO,
e foi o segundo centro histórico do país a receber tal título, em 1982,
após Ouro Preto. Em que pesem a descaracterização de parte do seu casario
histórico e a perda de diversos exemplares da arquitetura quinhentista com
o ataque holandês, Olinda abriga dezenas de igrejas e conventos barrocos de
inestimável valor histórico, e mantém o seu traçado urbano colonial.
É uma localidade de grande relevo na história do Brasil.
</p>
    </header>
    <main id= "linkytb">
        <iframe width="1280" height="720" src="https://www.youtube.com/embed/PxkkNQEbeMo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    <h2 class="curiosidade">Curiosidades</h2>
    <ul style="list-style: none;">
        <li>"Existe um cometa chamado Olinda"</li>
        <li>"Olinda, capital de Pernambuco"</li>
        <li>"Primeira Faculdade de direito do Brasil"</li>
        <li>"O único lugar que faliu um MC Donalds"</li>
        <li>"O homem da meia noite não é um boneco"</li>
    </ul>
    </main>
    <footer id= "links">

        <a href="https://www.instagram.com/pref_olinda/?hl=pt" target="_blank">
            <img src="img/instagram.png" class="logos">
        </a>
        <a href="https://www.facebook.com/prefeituradeolinda/" target="_blank">
            <img src="img/facebook.png" class="logos"
        </a>
    </footer>
</body>
</html>
    
    *{margin: 0}

body{
    background-image: url(img/olinda1.jpg);
    background-attachment: fixed;
    background-repeat: no-repeat;
    background-size: cover;

}
#nome {
    color:black;
    text-align: center;
    font-family:Verdana, Geneva, Tahoma, sans-serif;
    font-size: 50px;
    font-style: italic;
    font-weight: 200;
    background-color: rgb(98, 98, 241);
    padding: 12px;
} 
#resumo{
    padding: 25px;
    text-align: center;
    font-family: cursive;
    font-size: 18px;
    font-style: oblique;
}
#linkytb{
    text-align: center;
}
.curiosidade{
    color:rgb(10, 10, 10);
    text-align: center;
    font-family:Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
    font-size: 40px;
    font-style:initial;
    font-weight: 200;
    padding: 10px;
    background-color: rgba(248, 246, 233, 0.30);
}
ul{
    color: rgb(12, 11, 11) ;
    text-align: center;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    font-size: 20px;
    font-style: oblique;
    background-color: rgba(248, 246, 233, 0.30);

}
#links{
    text-align: center;
    padding: 20px;
}
.logos{
margin: 20px;
width: 70px;
height: 70px;
}
