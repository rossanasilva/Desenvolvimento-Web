## Web Development Notes

## Folder Structure

- `css`: the folder to maintain css files
- `html`: the folder to maintain html files
- `javascript`: the folder to maintain js files
- `php`: the folder to maintain php files
- `projects`: the folder to maintain projects
----------------------------------------------------------------------------

## Everything about Web Development

## HTML

### Html tags

- para abrir uma tag usamos os sinais de <>
----------------------------------------------------------------------------

### Tag DOCTYPE

- tag `DOCTYPE` (tipo de documento) `<!DOCTYPE html>` -> mostra para o browser o tipo de documento a ser usado, no caso aí é html
----------------------------------------------------------------------------

### Tag html

- tag `html` -> mostra para o browser que o código html ele tem começo e fim
----------------------------------------------------------------------------

### Tag head

- tag `head` (cabeça) -> onde configuramos informações que não aparecem para o usuário
----------------------------------------------------------------------------

### Tag body

- tag `body` (corpo) -> onde configuramos informações que aparecem direto para o usuário
----------------------------------------------------------------------------

### Tag title

- tag `title`  -> título da página
----------------------------------------------------------------------------

### Tag br

- tag `br` (break) ->  faz uma quebra de linha

#### Exemplo:

  `<body>`
    `Sobre a empresa <br> `
    `Essa é uma empresa tal.. `
  `</body>`

##### Console:
    Sobre a empresa
    Essa é uma empresa tal.. 
----------------------------------------------------------------------------

### Tag h

- tag `h` ou header (cabeçalho), temos:
    - `h1`
    - `h2`
    - `h3`

- vai do `h1` até o `h6`

----------------------------------------------------------------------------

### Tag p

- tag `p` -> faz um parágrafo
----------------------------------------------------------------------------

### Tag hr

- tag `hr` -> cria uma linha horizontal


### Tags de formatações de texto

- tag `bold` (negrito) `<b></b>` -> deixa um determinado texto em negrito, porém não é mais utilizada

- tag `strong` -> negrito atual 

- tag `em` -> deixa o texto em itálico

- tag `u` -> bota um underline no texto

- tag `strike` - corta o texto

#### Exemplo:

- `Minha <b>primeira página</b>`
----------------------------------------------------------------------------

### Listas Ordenadas e Não Ordenadas

#### Lista não ordenada

- usa-se a tag `ul` para fazer uma lista não ordenada
- usa-se a tag `ol` para fazer uma lista ordenada

##### unfocused:

- tag `li` (list item) -> itens da lista

#### Exemplos:

- Imagem

![listas.png](img/images_readme/listas.png)

----------------------------------------------------------------------------

### Primeiro Mini Projeto, usando os básicos aprendidos

- Imagem

![primeiro_projeto.png](img/images_readme/primeiro_projeto.png)

----------------------------------------------------------------------------

### Uso de imagens no HTML

- Quando se quer utilizar imagens no html, se usa a tag `img`, colocando o caminho de onde a imagem se encontra;
- Se caso queira utilizar a url da imagem, só colocar, porém não é muito recomendado, pois a imagem pode deixar de existir por um acaso.
- Podendo modificar a imagem usando width (largura) e height (altura)

#### Exemplos:

`<img src="/img/images/yakisoba.jpg">` <br>
`<img src="https://receitatodahora.com.br/wp-content/uploads/2021/09/yakisoba-scaled.jpg">` <br>
`<img src="/img/images/yakisoba.jpg" width="600">`

----------------------------------------------------------------------------

### Links no html

- Para colocar links na sua página você utiliza a tag `a` de anchor, que quer dizer âncora
- Pode também utilizar a anchor para interligar um outro site

#### Exemplos:

`<a href="contato.html">Contatos</a>` -> vai para página de contatos <br>
`<a href="https://www.youtube.com/">Clique aqui</a>` -> vai para o youtube
