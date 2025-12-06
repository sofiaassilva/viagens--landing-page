# TripMe: Descubra Vilarejos Europeus

Landing Page estática criada como parte de um projeto de estudo em desenvolvimento web. O objetivo é simular uma página de captura ("catch the fish" / Landing Page) focada em destinos de viagem charmosos e remotos.

## Visão Geral do Projeto

Este projeto demonstra o uso de **HTML semântico** e **CSS** para construir uma Landing Page limpa e responsiva. Ele cumpre requisitos mínimos de navegação interna e aplicação de efeitos visuais (`:hover` e `transition`).

### Requisitos Cumpridos

* **HTML Semântico:** Utilização de tags como `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, e `<footer>`.
* **Banner Principal:** Contém um banner no `<main>` com uma imagem de fundo (Hallstatt, Áustria) e um texto *overlay* (`<h1>`).
* **Navegação Interna:** O `<nav>` principal e os links "Voltar ao Topo" utilizam âncoras (`<a href="#id">`) para navegação suave dentro da mesma página.
* **Seções Mínimas:** O site possui três seções principais:
    1.  `#minhaviagem`
    2.  `#nosencontre`
    3.  `#conselhos`
* **Efeitos de Interação:** Links e botões (`<a>`) mudam de aparência ao passar o mouse (`:hover`) e utilizam `transition` para uma mudança suave.

## Tecnologias Utilizadas

| Tecnologia | Descrição |
| :--- | :--- |
| **HTML5** | Estrutura semântica da página. |
| **CSS3** | Estilização, layout (Flexbox) e aplicação de efeitos de transição. |
| **Imagens Externas** | Imagem do banner principal carregada via URL no CSS. |

## Como Executar o Projeto

Como este projeto é puramente estático (HTML e CSS), a execução é muito simples:

1.  **Salve o Código:** Copie o código HTML completo (que inclui o CSS embutido na tag `<style>`).
2.  **Crie o Arquivo:** Salve-o em um arquivo chamado `index.html`.
3.  **Abra no Navegador:** Dê um clique duplo no arquivo `index.html`. Ele será aberto automaticamente no seu navegador padrão.


> ⚠️ Certifique-se de copiar o código corretamente para executar os testes.


## Licença

Este projeto está licenciado sob os termos da MIT License.


## Agradecimentos

Obrigado por conferir este projeto! Fique à vontade para contribuir, sugerir melhorias ou utilizar como base para seus próprios estudos.


## Imagem do Banner

A imagem utilizada para o banner principal (Hallstatt, Áustria) foi carregada através do seguinte link no arquivo CSS:

```css
background-image: url('[https://worldby2.com.br/wp-content/uploads/2025/01/hallstatt.jpg](https://worldby2.com.br/wp-content/uploads/2025/01/hallstatt.jpg)');