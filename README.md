# TechNews Today - Portal de Tecnologia

O **TechNews Today** é uma página web institucional simples e semântica focada na publicação de notícias e atualizações do mundo da tecnologia. O projeto conta com um artigo em destaque, exibição de conteúdo multimídia e um formulário para captura de leads via newsletter.

## 🚀 Tecnologias Utilizadas

O projeto foi construído utilizando práticas modernas de desenvolvimento web focado em semântica estrutural:

* **HTML5 Semântico:** Uso de tags estruturais apropriadas (`<header>`, `<main>`, `<article>`, `<section>`, `<footer()`) para otimização de acessibilidade e SEO.
* **CSS3:** Vinculado externamente através do arquivo `projetoa10.css` (responsável pela estilização e layout da página).

## 📋 Recursos da Página

| Componente | Tag Principal | Descrição |
| :--- | :--- | :--- |
| **Cabeçalho (`.cabecalho`)** | `<header>` | Apresenta o logotipo principal do portal e a tagline com ênfases textuais. |
| **Artigo de Destaque (`.artigo-destaque`)** | `<article>` | Notícia principal com controle de data semântica (`<time>`) e bloco de texto expansível (`<details>`). |
| **Seção de Vídeo (`.secao-video`)** | `<section>` | Incorporação de conteúdo multimídia externo através de um elemento `<iframe>` do YouTube. |
| **Formulário de Newsletter (`.secao-newsletter`)** | `<form>` | Sistema de captura com validação nativa de e-mail, seleção de área de interesse e caixa de aceite de termos. |
| **Rodapé (`.rodape`)** | `<footer>` | Exibe os direitos autorais e informações de contato usando a tag semântica `<address>`. |

## 🛠️ Como Executar o Projeto

Para visualizar a página localmente em seu navegador, siga os passos abaixo:

1. Baixe ou clone os arquivos deste repositório.
2. Certifique-se de manter os arquivos na mesma pasta (ou diretório):
   * `index.html` (o arquivo contendo este código fornecido)
   * `projetoa10.css` (seu arquivo de folhas de estilo)
3. Dê um duplo clique no arquivo `index.html` ou abra-o diretamente no navegador de sua preferência.

## 📄 Notas de Desenvolvimento

* **Validação de Formulário:** O campo de email e o checkbox de termos possuem o atributo `required`, impedindo o envio de dados em branco.
* **Destino do Formulário:** O formulário está configurado para disparar requisições do tipo `POST` apontando para um script fictício chamado `subscribe.php`.
