01////////////////////////////////////////
Caramelos e Bichanos

Site institucional da ONG Caramelos e Bichanos, dedicada ao resgate, cuidado e adoção responsável de cães e gatos em situação de vulnerabilidade.

O projeto tem como objetivo informar o público sobre as ações da ONG, incentivar a adoção e apresentar seus projetos sociais.

02////////////////////////////////////////

Visão Geral

O site é composto por uma página principal simples e responsiva, com:

Cabeçalho com o nome da ONG e logotipo;

Botão para alternar o tema (claro/escuro);

Menu de navegação para acessar páginas como Cadastro e Projetos;

Texto institucional apresentando a missão da ONG;

Rodapé com direitos autorais.

03////////////////////////////////////////

Estrutura do Projeto
/
├── index.html              # Página principal
├── css/
│   └── style.css           # Pasta que contem o estilo do site.
├── js/
│   └── app.js              Script para alternar tema e menu responsivo
├── img/
│   └── 8.png               Logotipo da ONG
├── cadastro.html           Página de cadastro de voluntários
└── projetos.html           Página que exibe os projetos da página

04////////////////////////////////////////

Conteúdo do index.html
Cabeçalho (<header>)

Contém:

O nome da ONG: Caramelos e Bichanos

Um aviso para ativar o JavaScript (<noscript>)

Um botão para alternar entre o tema Dark/Light

A logomarca da ONG

05////////////////////////////////////////

Navegação (<nav>)

Menu com:

Link para Cadastro

Link para Projetos

O menu possui uma versão hambúrguer responsiva controlada via JavaScript (menu-toggle).

06////////////////////////////////////////

Conteúdo principal (<article>)

Apresenta um texto de boas-vindas com informações sobre:

O trabalho da ONG

Resgate, cuidado e adoção de animais

A importância da adoção responsável

07////////////////////////////////////////

Rodapé (<footer>)

Inclui os direitos autorais:

08////////////////////////////////////////

O arquivo /css/style.css define:

Layout responsivo

Cores e fontes do site

Estilo do menu, botões e textos

09////////////////////////////////////////

Funcionalidades (JavaScript)

O script /js/app.js é responsável por:

Alternar o tema (modo claro/escuro) ao clicar no botão

Exibir/esconder o menu em dispositivos móveis