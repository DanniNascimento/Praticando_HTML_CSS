# Bora praticar um pouco de HTML + CSS...

Lembre-se, cada desafio é uma chance de crescer. Não se desanime com os erros; eles são degraus no caminho do aprendizado. E acima de tudo, divirta-se! 
O aprendizado mais eficaz acontece quando nos engajamos e nos interessamos pelo que estamos fazendo.

#### Boas Praticas...

1) 1) Adicionando um subtítulo à página
Imagine que você está desenvolvendo uma página web para compartilhar suas redes sociais. Você precisa adicionar um subtítulo "Acesse minhas redes:" acima dos links para Instagram e Github. Sua tarefa é editar o arquivo index.html para incluir esse subtítulo. Lembre-se de usar a tag <h2> para o subtítulo e colocá-lo dentro da <div> que já contém os links.

```html
<div class="apresentacao__links">
    <h2>Acesse minhas redes:</h2>
    <a class="apresentacao__links__link" href="https://instagram.com/">Instagram</a>
    <a class="apresentacao__links__link" href="https://github.com/">Github</a>
</div>

```

2) Alterando a disposição dos elementos com Flexbox
Agora que o subtítulo foi adicionado, você percebe que ele está alinhado à esquerda dos botões, ao invés de acima deles. Isso aconteceu porque os elementos estão dispostos horizontalmente. Sua missão é alterar a disposição dos elementos (subtítulo e botões) para uma disposição vertical. Edite o arquivo style.css, modificando a propriedade flex-direction para column dentro da classe .apresentacao__links. Isso mudará a direção do Flexbox, alinhando os elementos verticalmente.

```css
.apresentacao__links {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}

```

3) Ajustando o alinhamento e o espaçamento dos elementos
Após modificar a direção do Flexbox, você observa que os elementos (texto e botões) estão muito próximos uns dos outros e alinhados à esquerda. Para melhorar a estética da página, você precisa centralizar esses elementos verticalmente e adicionar um espaçamento entre eles. No arquivo style.css, dentro da classe .apresentacao__links, adicione a propriedade align-items: center para centralizar os elementos. Em seguida, insira a propriedade gap com o valor de 32px para adicionar o espaçamento entre cada elemento.

```css
.apresentacao__links {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    gap: 32px;
}

```



4) Criando uma classe para o subtítulo
Você está desenvolvendo uma página web e decidiu que o subtítulo "Acesse minhas redes:" precisa de uma estilização específica.
Para isso, você vai criar uma classe CSS para este subtítulo. No arquivo index.html, encontre a tag <h2></h2> que contém o subtítulo e adicione uma classe chamada apresentacao__links__subtitulo. Sua tarefa é inserir essa classe na tag <h2></h2> de forma correta.

```html
<h2 class="apresentacao__links__subtitulo">Acesse minhas redes:</h2>


```

5) Estilizando o subtítulo
Agora que você criou uma classe para o subtítulo, é hora de estilizá-lo. No arquivo style.css, adicione a classe .apresentacao__links__subtitulo e configure as propriedades de estilo. Utilize a fonte 'Krona One', com um peso de fonte (font-weight) de 400 e um tamanho de fonte (font-size) de 24px. Ajuste a fonte para ser 'sans-serif' sem aspas. Sua tarefa é escrever o código CSS para aplicar essas configurações ao subtítulo.

```css
.apresentacao__links__subtitulo {
    font-family: 'Krona One', sans-serif;
    font-weight: 400;
    font-size: 24px;
}

```

6) Modificando o estilo dos botões
Os botões da sua página precisam de um novo visual. No arquivo style.css, encontre a classe .apresentacao__links__link e faça as seguintes alterações: remova o fundo ciano, mude a cor do texto para branco (#F6F6F6), adicione uma borda sólida de 2px na cor ciano (#22D4FD), altere a largura para 378px, e ajuste o border-radius para 8px. Sua tarefa é alterar o código CSS para refletir estas mudanças, criando botões com bordas ciano, texto branco, e cantos menos arredondados.

```css
.apresentacao__links__link {
    /* background-color: #22D4FD; */ /* Código comentado */
    border: 2px solid #22D4FD;
    color: #F6F6F6;
    width: 378px;
    border-radius: 8px;
    /* Outras propriedades existentes permanecem inalteradas */
}

```

