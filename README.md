# Projeto de Portfólio Pessoal

Bem vindo! Este é um projeto de portfólio pessoal desenvolvido por mim Mikael Pereira, este é o meu primeiro contato com HTML e CSS. O objetivo deste projeto é apresentar minhas habilidades, registrar o meu desenvolvimento e crescimento ao longo do tempo e experiências como desenvolvedor Front-end, bem como fornecer links para minhas redes sociais e futuros trabalhos.

## Estrutura do Projeto

## Arquivo HTML <code><img height="25" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/html/html.png" alt="HTML5"/></code>

### Home (index.html) 
Esta é a página principal do portfólio. Ela contém uma breve introdução e links para as minhas redes sociais.

### Sobre mim (about.html)
Esta página fornece detalhes sobre as minhas experiencias iniciais e caracteristicas pessoas.

## Arquivo CSS <code><img height="25" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/css/css.png" alt="CSS"/></code>
O estilo do projeto é definido no arquivo estilos/styles.css. Aqui estão alguns detalhes sobre a estrutura do CSS:

### Variáveis CSS 🗒️
O projeto utiliza variáveis CSS para cores e fontes:

    :root {
        --cor-primaria: #000000;
        --cor-secundaria: #f6f6f6;
        --cor-terciaria: #22D4FD;
        --cor-hover: #272727;
        --font-krona-one: "Krona One", sans-serif;
        --font-mont-serrat: "Montserrat", sans-serif;
    }

### Estilos Globais 🌍
Estilos globais são aplicados a todos os elementos para remover margens e preenchimentos padrão:

    {
        margin: 0;
        padding: 0;
    }

### Corpo da Página 📃
Definição de estilo para o corpo da página:

body {
    box-sizing: border-box;
    background-color: var(--cor-primaria);
    color: var(--cor-secundaria);
}

### Classes de Estilo 📚
- **.destaque_titulo_azul:** Estilo para textos destacados em azul.
- **.apresentacao:** Estilo para a seção de apresentação, incluindo padding, display flex, alinhamento e espaçamento.
- **.apresentacao__conteudo:** Estilo para o conteúdo da apresentação, utilizando flexbox e espaçamento.
- **.apresentacao__conteudo__titulo:** Estilo para o título da apresentação.
- **.apresentacao__conteudo__texto:** Estilo para o texto da apresentação.
- **.apresentacao_imagem:** Estilo para a imagem de apresentação.
- **.estilo__subtitulo__botoes:** Estilo para o subtítulo dos botões.
- **.grupo__botoes:** Estilo para o grupo de botões, incluindo display flex e alinhamento.
- **.estilo__botoes:** Estilo para os botões de redes sociais, incluindo padding, borda, cor e hover.
- **.cabeçalho__header:** Estilo para o cabeçalho da página.
- **.cabeçalho__nav:** Estilo para a navegação do cabeçalho.
- **.cabeçalho__links:** Estilo para os links do cabeçalho.
- **.rodape:** Estilo para o rodapé da página.

## Media Queries 🪄
Estilos responsivos para dispositivos com largura **máxima** de 1250px:

    @media (max-width: 1250px) {
        .apresentacao {
            flex-direction: column-reverse;
            padding: 4% 10%;
        }
        .apresentacao__conteudo {
            width: auto;
        }
        .apresentacao_imagem {
            width: 80%;
        }
        .cabeçalho__header {
            padding: 10%;
        }
        .cabeçalho__nav {
            justify-content: center;
        }
    }

## Estrutura de Diretórios 📂
O projeto segue a seguinte estrutura de diretórios:

    /
    |-- index.html
    |-- about.html
    |-- estilos/
    |   |-- styles.css
    |-- assets/
    |   |-- Logo Instagran.png
    |   |-- Logo Github.png
    |   |-- Logo linkedin.png
    |   |-- Mikael PB.jpg

- **index.html:** Página principal do portfólio.
- **about.html:** Página "Sobre mim" com mais detalhes sobre o desenvolvedor.
- **estilos/styles.css:** Arquivo CSS contendo os estilos utilizados nas páginas.
- **assets/:** Diretório contendo as imagens e logos utilizados no projeto.

## Para visualizar o projeto acesse 🔗
**Vercel:** [first-html-css-template](https://first-html-css-template.vercel.app)

# Autor
Mikael Pereira.

### Minhas redes:
**Instagram:** [@astrolight_ika](https://www.instagram.com/astrolight_ika/) <br>
**Github:** [Astrolight22](https://github.com/Astrolight22) <br>
**LinkedIn:** [Mikael Pereira](https://github.com/Astrolight22)