<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Minha apresentação</title>
    <style>

        *{
            margin: 0;
            padding: 0;
        }
        
        body{
            font-family: Arial, Helvetica, sans-serif;
            padding-top: 15px;
        }

        header > img.inicial{
            background-color: black;
            display: block;
            margin: auto;
            padding: 0.8px;
            width: 70vw;
            border: 2px solid rgba(255, 255, 255, 0.445);
        }

        header > ul > li{
            margin-top: 25px;
            text-align: center;
            font-size: 60px;
        }

        .emoji::before{
            content: attr(data-emoji);
            font-size: 60px;
        }

        header > hr{
            margin-top: 25px;
            margin-bottom: 25px;
        }

        main > p {
            text-align: center;
            font-size: 26px;
            text-decoration: underline;
        }

        main > iframe{
            width: 700px;
            height: 500px;
        }

        main > ul > li { 
            
        }

    </style>
</head>
<body>
    <header>
        <img class="inicial" src="Image/68747470733a2f2f7669736d652e636f2f626c6f672f77702d636f6e74656e742f75706c6f6164732f323031392f31302f616e696d617465642d70726573656e746174696.gif" alt="Balões animados flutuando sobre um notebook">

        <ul>
            <li> Oi <span class="emoji" data-emoji="👋" ></span>, Sou o Bruno Bertol</li>
        </ul>

        <hr>
    </header>
    <main>
        <p>Um desenvolvedor Front-end que está à procura de uma oportunidade de estágio.</p>

        <ul>
            <li> Atualmente não estou trbalhando na área da tecnologia</li>
            <li> Atualmente Aprendendo HTML5, CSS3 e JAVASCRIPT</li>
            <li> Todos os meus projetos podem ser encontrador <a href="https://github.com/BrunoBertol/">aqui</a></li>
        </ul>        
    </main>
</body>
</html>        
