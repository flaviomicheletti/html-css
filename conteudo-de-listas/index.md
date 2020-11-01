---
layout:      none
title:       Conteúdo de listas (ordenadas e não ordenadas)
capitulo:    "html-intro"
ordem:       7
---
<html>
    <head>
        <title>Conteúdo de listas (ordenadas e não ordenadas)</title>
        <meta charset="UTF-8">
    </head>
    <body>

        <h1>Conteúdo de listas (ordenadas e não ordenadas)</h1>
        <p>| <a href="../conteudo-de-links/">artigo anterior</a> | <a href="../">index</a> |</p>

        <p>As listas servem para listar itens, óbviamente!</p>
        <p>O que não é obvio é que elas são utilizadas para criar menus de navegação.</p>
        <p>
            Elas são uma marcação imporante e presente na maioria dos arquivos HTML, <br />
            por essa razão acho importante apresentá-las a você, no início de seu aprendizado.
        </p>
        <p>Temos basicamente três tags...</p>
        <pre><code>
ol = ordened list
ul = unordened list
li = list item
</code></pre>
        <p>O código abaixo...</p>
        <pre><code>&lt;ol&gt;
    &lt;li&gt;primeiro&lt;/li&gt;
    &lt;li&gt;segundo&lt;/li&gt;
    &lt;li&gt;terceiro&lt;/li&gt;
&lt;/ol&gt;
</code></pre>
        <p>...gerará o seguinte resultado:</p>
        <ol>
            <li>primeiro</li>
            <li>segundo</li>
            <li>terceiro</li>
        </ol>
        <p>O código abaixo...</p>
        <pre><code>&lt;ul&gt;
    &lt;li&gt;itme 1&lt;/li&gt;
    &lt;li&gt;itme 2&lt;/li&gt;
    &lt;li&gt;itme 3&lt;/li&gt;
&lt;/ul&gt;
</code></pre>
        <p>...gerará o seguinte resultado:</p>
        <ul>
            <li>item 1</li>
            <li>item 2</li>
            <li>item 3</li>
        </ul>

        <p>Ok, agora vamos ao último conteúdo, <a href="../conteudo-de-imagens/">as imagens</a>.</p>

    </body>
</html>
