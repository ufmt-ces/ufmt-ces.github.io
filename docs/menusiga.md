# Acesso aos Menus dos Sistemas Acadêmicos

Alguns navegadores podem apresentar problemas em exibir de forma satisfatória os sistemas acadêmicos de graduação e pós-graduação da UFMT,
respectivamente o **SIGA** e o **SIPG**.

![Tela do SIGA](images/siga.png "SIGA com menu com erro")
![Tela do SIPG](images/sipg.png "SIPG com menu com erro")

A CES, não medindo esforços em melhorar o ambiente digital da comunidade acadêmica, esta voltando seu corpo de trabalho no desenvolvimento
de uma nova versão do Portal Acadêmico, mais adequado com as novas tecnologias e menos suscetível à falhas de interface.

Com isso, é recomendado uma medida paliativa, configurando-se o navegador para que este possa exibir corretamente o conteúdo dos sistemas acadêmicos atuais.

Aqui constam as instruções para o [Chrome](#chrome), [Firefox](#firefox) e [Opera](#opera)

## Chrome

### Método 1

Na barra de endereço do Chrome, localize e clique no texto 'inseguro' do lado esquerdo. No painel que se expandir, clique em 'Definições de sites'.

![Tela 01 do Chrome](images/chrome_01.png "Chrome com a opção de definição do site")

Na tela de configurações que for aberta, localize no final da página a opção 'Conteúdo inseguro' e escolha a opção 'Permitir'.

![Tela 02 do Chrome](images/chrome_02_cortado.png "Definições do site academico")

### Método 2

No menu do Chrome, expanda as opções (**⋮**) e clique em 'Definições'

![Tela 03 do Chrome](images/chrome_03.png "Menu Definições")

Na tela apresentada, digite 'definições de sites' e clique na opção encontrada

![Tela 04 do Chrome](images/chrome_04.png "Definições de sites")

No final da página encontre e clique na opção 'Conteúdo inseguro'

![Tela 05 do Chrome](images/chrome_05.png "Opção conteúdo inseguro")

Nas opções expandidas, adicione os endereços `https://academico-siga.ufmt.br:443` e `https://academico-siga.ufmt.br:80`

![Tela 05 do Chrome](images/chrome_06.png "Permitir conteúdo")


## Firefox

### Método 1

Na barra de endereço do Firefox, localize e clique no icone do cadeado.
Depois clique no sinal **>** para expandir as opções

![Tela 01 do Firefox](images/erro_01_firefox_cortado.png "Firefox com informações do site")

Na informação expandida clique em 'Desativar proteção por enquanto'

![Tela 02 do Firefox](images/erro_02_firefox.png "Firefox com informações do site")


### Método 2

No campo de endereço, digite about:config

Clique no botão Serei cuidadoso, prometo

No campo de pesquisa, digite block_active

Defina o valor de security.mixed_content.block_active_content para falso

## Opera