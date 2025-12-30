# Projeto Página de Tributo - Satoru Gojo

Este projeto é um exercício do curso "HTML e CSS avançado" da B7web. O objetivo foi criar uma página de tributo estática, aplicando conceitos de HTML semântico, CSS com Flexbox e responsividade.

## 🔨 Conceitos e Tecnologias Utilizadas no Projeto

Abaixo está a lista dos principais conceitos que foram efetivamente aplicados neste projeto:

### Estrutura e Semântica (HTML)

- **HTML Semântico:** Uso de tags para dar significado e estrutura à página:
  - `<header>`: Cabeçalho principal da página.
  - `<main>`: Conteúdo principal.
  - `<footer>`: Rodapé.
  - `<section>`: Para agrupar o conteúdo da linha do tempo.
- **Meta Tag de Viewport:** Uso da tag `<meta name="viewport" ...>` para garantir que a página seja exibida corretamente em dispositivos móveis.
- **Estrutura de Arquivos CSS:** O CSS foi modularizado em arquivos distintos (`reset.css`, `header.css`, `main.css`, `footer.css`, `responsive.css`) para melhor organização e manutenibilidade.

### Estilização e Layout (CSS)

- **CSS Reset:** Aplicação de um reset básico (`* { margin: 0; padding: 0; box-sizing: border-box; }`) para remover estilos padrão dos navegadores e garantir consistência.
- **Flexbox:** O layout da página foi inteiramente construído com Flexbox, sendo o pilar principal da estilização.
  - `display: flex;`
  - `flex-direction: column;`
  - `flex-wrap: wrap;`
  - `flex-grow: 1;` e `flex: 1;` para criar um layout flexível.
  - Propriedades de alinhamento: `align-items`, `justify-content`.
- **Design Responsivo:**
  - **`@media queries`**: Utilizadas para adaptar o layout, margens e tamanhos de fonte em diferentes resoluções de tela (`max-width`).
  - **Imagens Fluidas:** A imagem principal se ajusta ao tamanho da tela usando `width: 100%` e `max-width`.
- **Fontes Customizadas:** Importação de fontes do Google Fonts através da regra `@import` no CSS.
- **Seletores CSS:** Utilização de seletores de tipo (`body`, `h1`), de classe (`.container-header`) e descendentes (`header p`) para aplicar os estilos.
