# Markdown cheat sheet
---
## Títulos

```
# Titulo 1
## Titulo 2
### Titulo 3
#### Titulo 4
##### Titulo 5
###### Titulo 6
```

----
## Listas

Não numeradas

* item 1
* item 2
* item 3

```
* item 1
* item 2
* item 3
```

Numeradas

1. item 1
1. item 2
1. item 3

```
1. item 1
1. item 2
1. item 3
```

---
## Quotação

> Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.

> Donec sit amet nisl.
Aliquam semper ipsum sit amet velit.
Suspendisse id sem consectetuer libero luctus adipiscin

```
> Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.

> Donec sit amet nisl.
Aliquam semper ipsum sit amet velit.
Suspendisse id sem consectetuer libero luctus adipiscin
```

---
## Links

```
[Aqui vai o texto](aqui vai a url)

ou

<aqui vai a url>
```


Pode fazer referência a um conteúdo local: [sobre](sobre.md)

```
[sobre](sobre.md)
```

Pode fazer referência a um link no documento: [# Títulos](#titulos)

```
[# Títulos](#titulos)
```


---
## Código
### linha

Feito com um sinal de acento grave antes e depois: `mkdir docs/stylesheets`

```
`mkdir docs/stylesheets`
```

### bloco

Feito por identação do documento, com uma linha vazia seguinda de 1 tab ou seguida de 4 espaços.
É possível também delimitar com três sinais de acento grave ` ``` ` antes e depois do bloco:

```
mkdir docs/stylesheets
touch .\docs\stylesheets\extra.css
```

---
## Destaque do texto

*um asterisco*

_um sublinhado_

**dois asteriscos**

__dois sublinhados__

---
## Imagens

![texto alternativo](images/logo_vetor_fundo_branco_recortado.png)

![texto alternativo](images/logo_vetor_fundo_branco_recortado.png "titulo opcional")

```
![texto alternativo](images/logo_vetor_fundo_branco_recortado.png)

![texto alternativo](images/logo_vetor_fundo_branco_recortado.png "titulo opcional")
```

## Tabelas

coluna 1 | coluna 2 | coluna 3
--|--|--
linha 1 | linha 1 | linha 1
linha 2 | linha 2 | linha 2
linha 3 | linha 3 | linha 3