<html lang="pt-br">
<head>
    <meta charset="utf-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>Javão escreapity</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="estilo.css" />
</head>
<body>
<header>
        <h1>Analisador de Números</h1><!--Uma brincadeira legal para ensinar seu filho as quatro operações basicas-->
</header>
<section>

    <div>
        Número (entre 1 e 100):
        <input type="number" name="fnum" id="fnum">
        <input type="button" value="adicionar" onclick="adicionar()">
        <br><br><select name="flista" id="flista" size="6"></select>
        <input type="button" value="finalizar" onclick="finalizar()" >
    </div>
    <div id="res">
        
    </div>

</section>

    <footer id="rodape">
        <p>Wentony Oliveira</p>
        <p><a href="http>//facebook.com/"> Facebook Wentony Capuleto </a> | <a href="http://twitter.com/"> Twitter</a> </p>
        </footer>
        <script src="scrypt.js"></script>
</body>
</html>
