
<br>

<h1 align="center">Markdown Syntax</h1>

<br><br>

### Tamanho dos Cabeçalhos.
```ruby
 Markdown | HTML
------------------------------------
# H1      | <h1>Heading level 1</h1>
## H2     | <h2>Heading level 2</h2>
### H3    | <h3>Heading level 3</h3>
#### H4   | <h4>Heading level 4</h4>
##### H5  | <h5>Heading level 5</h5>
###### H6 | <h6>Heading level 6</h6>
------------------------------------
```
<br>

### Texto centralizado
```html
<h1 align="center">Lorem ipsum</h1>

<h2 align="center">Lorem ipsum</h2>

<h3 align="center">Lorem ipsum</h3>
```
### Texto a direita
```html
<h1 align="right">Lorem ipsum</h1>

<h2 align="right">Lorem ipsum</h2>

<h3 align="right">Lorem ipsum</h3>
```
### Texto a esquerda
```html
<h1 align="left">Lorem ipsum</h1>

<h2 align="left">Lorem ipsum</h2>

<h3 align="left">Lorem ipsum</h3>
```
<br>

### Citações
```
> Lorem ipsum
```
<br>

### Citações com vários parágrafos
```
> Lorem ipsum
>
> Consectetur adipiscing elit.
```
<br>

### Imagem
```html

<img src="https://url_da_imagem" title="Imagem">
          |-------------------|         |-----|  
                     |                     |
                     |                     |--- Título da imagem
                     |--- URL da imagem
```
```html

<img width="922" height="455" src="https://url_da_imagem">
     |---------------------|       |--------------------|
                |                             |
                |                             |--- URL da imagem
                |
                |--- Tamanho da imagem "width" largura e "height" altura.
```



### Imagem centralizada
```html
<p align="center">
  <img width="922" height="455" src="https://url_da_imagem">
</p>
```

### Imagem a direita
```html
<p align="right">
  <img width="410" height="300" src="https://url_da_imagem">
</p>
```
### Imagem a esquerda
```html
<p align="left">
  <img width="410" height="300" src="https://url_da_imagem">
</p>
```
### Imagem pequena lado a lado centralizada
```html
<p align="center">
  <img src="LINK_DA_IMAGEM" width="350" title="TEXTO">
  <img src="LINK_DA_IMAGEM" width="350" alt="TEXTO">
</p>
```
<br>

### Link
```
[GitHub](https://github.com)
```
<br>

### Parágrafos
```
<p>Lorem ipsum.</p>
```
<br>

### Quebra de linha HTML
```html
<p>Lorem ipsum.<br>
Consectetur adipiscing elit.</p>
```
<br>

### Tabela
```
 Cabeçalho 1 | Cabeçalho 2
------------ | -------------
Texto 1 | Texto 2
Texto 1 | Texto 2
```
### Tabela centralizada
```
Cabeçalho 1 | Cabeçalho 2 | Cabeçalho 3
:------: | :------: | :------:
Texto 1 | Texto 2 | Texto 3
Texto 1 | Texto 2 | Texto 3
```
### Tabela a direita
```
Cabeçalho 1 | Cabeçalho 2 | Cabeçalho 3
------: | ------: | ------:
Texto 1 | Texto 2 | Texto 3
Texto 1 | Texto 2 | Texto 3
```
### Tabela a esquerda
```
Cabeçalho 1 | Cabeçalho 2 | Cabeçalho 3
:------ | :------ | :------
Texto 1 | Texto 2 | Texto 3
Texto 1 | Texto 2 | Texto 3
```
### Tabela lado a lado
```
<table>
<tr><th> TABELA 01 </th><th> TABELA 02 </th></tr>
<tr><td>

|LISTA 01 | LISTA 01  | LISTA 01 |
|--|--|--|
|Nome 01 | 01 | 01 |

</td><td>
  
|LISTA 02 | LISTA 02  | LISTA 02 |
|--|--|--|
|Nome 02 | 02 | 02 |

</td></tr> </table>
```
<br>

### Listas de tarefas
```
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item
```
<br>

### Listas não ordenada
```
* Lorem ipsum
* Lorem ipsum
* Lorem ipsum
```

### Listas não ordenada com URL
```
#### Nome da Lista
* [Nome](https://odiegoduarte.github.io)
* [Nome](https://odiegoduarte.github.io)
* [Nome](https://odiegoduarte.github.io)
```

### Listas
```
* Item 1
* Item 2
  * Item 2a
  * Item 2b
```

### Listas ordenadas por números
```
1. Lorem ipsum
2. Lorem ipsum
3. Lorem ipsum
```

### Listas aninhadas
```
1. Primeiro item da lista
   - Primeiro item da lista aninhada
     - Segundo item da lista aninhada
```
<br>

### Linha horizontal
```
---
```
<br>

### Ênfase
```html
                Markdown         |         HTML
----------------------------------------------------------------------------------------
*texto em itálico*               | <em>texto em itálico</em>
**texto em negrito**             | <strong>texto em negrito</strong>.
***texto em negrito e itálico*** | <strong><em>texto em negrito e itálico</em></strong>
----------------------------------------------------------------------------------------
```
<br>

### Citar código
```
~~~javascript
Esta é uma linha de código em Javascript.
~~~
~~~php
Esta é uma linha de código em PHP.
~~~
~~~html
Esta é uma linha de código em HTML.
~~~
```
<br>

### Mencionar pessoas e equipes
```
@odiegoduarte Novo update.
```
<br>

### Formatação de links
```
Lorem ipsum. **[NomeSite](https://odiegoduarte.github.io)**.

Lorem ipsum. *[NomeSite](https://odiegoduarte.github.io)*.

Lorem ipsum. [`code`](#code).
```
<br>

### URLs e email
```
<https://odiegoduarte.github.io>
<email@example.com>
```
<br>

### Ignorar formatação markdown
```
Vamos renomear \*project\* para \*new-project\*.
```
<br>

### Espaçamento
```html
<br>
```
<br><br>




