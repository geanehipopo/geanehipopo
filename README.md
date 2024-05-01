*{
    margin: 0;
    padding: 0;
}

.cabecalho {
    background-color: #424E61;
    color: white;
    display: flex;
    justify-content: space-around;
    align-items: center;
    padding: 24px 0;
}

.cabecalho-imagem{
    width: 50%;
}

.cabecalho-lista-item{
    display: inline-block;
    margin: 0 16px;
    font-size: 24px;
}
.escola-imagem{
    width: 50%;
}

.escola{
    background-image: linear-gradient(#615e42,#b40c74);
    color:rgb(216, 0, 0);
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 24px 0;
}

.escola-div-conteudo{
    width: 60%%;
}
.escola-titulo{
    padding: 24px 0;
}



HTML:

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="Style.css">
</head>
<body>
    <header class="cabecalho">
        <img class="cabecalho-imagem" src="6ea03a92-7eab-4a44-9a71-dd0a939b7550.png" alt="logo do colégio Helena start">
        <ul class="cabecalho-lista">
            <li class="cabecalho-lista-item">Escola</li>
            <li class="cabecalho-lista-item">Estudante</li>
        </ul>
    </header>
    <section class="escola">
        <div class="escola-div-conteudo">
            <h2 class="escola-titulo">Sobre a Escola</h2>
            <p class="escola-texto-um">O colégio Helena foi fundado em 0000 e tem como objetivo ......., através .</p>
            <p class="escola-texto-dois">A turma mais estudiosa e famosa é a Segunda Série B. <span></span>Nós somos super unidos e a turma favorita por todos os professores e professoras que nos ajudam!</p>
        </div>
        <img class="escola-imagem" src="frente-colegio.jpg" alt="Professora no quadro">
    </section>
</body>
</html>
