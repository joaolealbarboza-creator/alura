Aqui está um exemplo simples de um site em HTML sobre o Santos FC, com título, imagem e texto:

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Santos Futebol Clube</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: black;
            color: white;
            padding: 20px;
        }

        img {
            max-width: 80%;
            height: auto;
            margin-top: 20px;
            border-radius: 10px;
        }

        .conteudo {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background: white;
            border-radius: 10px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Santos Futebol Clube</h1>
    </header>

    <img src="https://upload.wikimedia.org/wikipedia/commons/1/15/Santos_Logo.png" alt="Escudo do Santos FC">

    <div class="conteudo">
        <h2>Sobre o Santos</h2>
        <p>
            O Santos Futebol Clube é um dos clubes mais tradicionais do Brasil.
            Fundado em 14 de abril de 1912 na cidade de Santos, São Paulo,
            o clube é conhecido mundialmente por ter revelado grandes jogadores,
            incluindo Pelé, considerado por muitos o maior jogador de futebol da história.
        </p>

        <p>
            O Santos conquistou diversos títulos nacionais e internacionais,
            destacando-se pela sua tradição de futebol ofensivo e pela formação
            de jovens talentos.
        </p>
    </div>

</body>
</html>
```

Salve esse código em um arquivo chamado `index.html` e abra-o no navegador para visualizar o site.
