# Bem vindo ao MkDocs

Basicamente as alterações são feitas nos arquivos *.md, usando a [sintaxe Markdown](https://daringfireball.net/projects/markdown/syntax).

Isso é 'compilado' pelo Mkdocs em arquivos estaticos e são esses arquivos estáticos que serão servidos pelo servidor.

[Aqui](markdowncheatsheet.md) tem uma versão resumida dos coamndos mais utilizados.

## Utilização

Para utilizar, instale o Python e depois e execute no terminal:

```
pip install mkdocs-material
```

Depois, basta clonar esse repositório e criar sua documentação!

## Comandos

* `mkdocs serve` - Inicia o servidor com live-reloading.
* `mkdocs build` - Constroi/compila a documentação.
* `mkdocs -h` - Ajuda.
* `mkdocs new [dir-name]` - Cria um novo projeto.

## Layout do projeto

    mkdocs.yml                # O arquivo de configuração.
    docs/
        index.md              # A página inicial.
        sobre.md              # Uma página adicional.
        images/               # Imagens
        stylesheets/extra.css  # Customização do CSS

## Menu

Para adicionar um menu de navegação no tipo da página, edite o arquivo `mkdocs.yml`:

    site_name: MkLorum
    nav:
        - Inicio: index.md
        - Sobre: sobre.md

## Customização do estilo

Para customizar o CSS basta editar o arquivo [extra.css](stylesheets/extra.css).
A paleta de cores deve seguir [esse formato](https://squidfunk.github.io/mkdocs-material/getting-started/#color-palette) e usar as [variáveis do governo](http://dsgov.estaleiro.serpro.gov.br/ds/fundamentos-visuais/cores).
