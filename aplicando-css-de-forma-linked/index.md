---
layout:      none
title:       Aplicando o CSS de forma linked (externa)
capitulo:    "html-segundo"
ordem:       6
---
<html>
    <head>
        <title>Aplicando o CSS de forma linked (externa)</title>
        <meta charset="UTF-8">
        <!--

        Oi, tudo bem ?

        O elemento abaixo é o que eu quero que você observe.
        Clique em "arquivo.css", o navegador levará você até o arquivo css.
        Experimente !!!

        -->
        <link rel="stylesheet" type="text/css" href="arquivo.css" />
    </head>
    <body>

        <h1>Aplicando o CSS de forma linked (externa)</h1>
        <p>| <a href="../aplicando-css-de-forma-embedded">artigo anterior</a> | <a href="../">index</a> |</p>

        <img src="css-linked.jpg" title="css linked" alt="[figura css linked]" />

        <p>Neste exemplo eu vou estilizar todos os parágrafos com a cor vermelha.</p>
        <p>Só que, desta vez, vamos utilizar a forma linked (externa).</p>
        <p>
            Precisamos criar um arquivo com o nome <code>arquiv.css</code> e adicionar o código abaixo <br />
            entre a tag <code>head</code> do codumento.
        </p>

        <pre><code>&lt;link rel="stylesheet" type="text/css" href="arquivo.css" /&gt;</code></pre>

        <p>Veja o código fonte desta página para entender melhor!</p>
        <p>Agora podemos começar a <a href="../estilizando-a-fonte-do-documento">alterar a fonte do documento</a>.</p>

    </body>
</html>




