# Guia de Sintaxe Markdown :thinking:

<img src="https://shields.io/badge/Estudo-Markdown-brightgreen?logo=markdown&style=plastic">

<p>Guia feito para estudo rápido do Markdown. Para informação mais completa, veja o <a href="https://daringfireball.net/projects/markdown/">Site oficial da linguagem Markdown</a> ou outros links escritos na seção de <a href="#-Links">Link úteis</a>.</p>

### Títulos (Headers)

```markdown
# Título 1
## Título 2
### Título 3
#### Título 4
##### Tíutlo 5
###### Título 6
```

### Formatação

```markdown
**Negrito** ou também __Negrito__
*itálico* ou também _itálico_
```

### Listas

```markdown
##### lista não ordenada:

- Item
- Item2
  - Item2.1
  - Item2.2
    - Item 2.2.1
- Item3
- Item4

##### lista numerada:

1. Item1
1. Item2
1. Item3
1. Item4
```

###### lista não ordenada:

- Item
- Item2
  - Item2.1
  - Item2.2
    - Item 2.2.1
- Item3
- Item4

######  lista numerada:

1. Item1
1. Item2
1. Item3
1. Item4

### Trechos de códigos

````markdown
```
let numero1 = 123
let string1 = "Hello World!"
```js
````

```js
let numero1 = 123
let string1 = "Hello World!"
```

### Citação

```markdown
> Se o porco inteiro fosse perfeito, não haveria cachorro quente :hotdog:
> ~ Greg universo
```

> Se o porco inteiro fosse perfeito, não haveria cachorro quente :hotdog:
> ~ Greg universo

### Hyperlinks

```markdown
[Acessar google](https://google.com)
https://google.com
```

[Acessar google](https://google.com)

https://google.com

### Imagens

```markdown
![texto alt](url_da_imagem_aqui)
![imagem do logo do markdown](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg)
```

![imagem do logo do markdown](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg)

### Tabelas

```markdown
| ID   | Nome do Produto      | Preço     |
| ---- | -------------------- | --------- |
| 1    | Geladeira Frost-Free | R$1280.00 |
| 2    | Micro-ondas 250      | R$891.00  |

<!-- Também suporta Tags HTML -->
<p align=right>Tabela feita em Markdown</p>
```

| ID   | Nome do Produto      | Preço     |
| ---- | -------------------- | --------- |
| 1    | Geladeira Frost-Free | R$1280.00 |
| 2    | Micro-ondas 250      | R$891.00  |

<p align=right>Tabela feita em Markdown</p>

# Links úteis

:page_facing_up: https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet

:page_facing_up: https://docs.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax

:page_facing_up: https://typora.io/ :arrow_right: software ​utilizado para escrever esse arquivo Markdown

## Extras

para fazer badges, muito comum em arquivos README:

:page_facing_up: https://shields.io/

```markdown
<img src="https://shields.io/badge/Estudo_Markdown-black?logo=markdown&style=plastic">
```

<img src="https://shields.io/badge/Estudo_Markdown-black?logo=markdown&style=plastic">

:page_facing_up: https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md guia de icones para markdown (muito utilizado para mensagens de commits)​

```markdown
:rocket: :smile: :pancakes: :egg: :cookie:
```

:rocket: :smile: :pancakes: :egg: :cookie:

