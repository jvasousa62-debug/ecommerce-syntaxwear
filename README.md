# ecommerce-syntaxwear

## 🛍️ Visão Geral

Projeto de layout responsivo de e-commerce para tênis e sneakers, chamado Syntaxwear. A página é estática (HTML + CSS) e foi desenvolvida para demonstrar grade CSS moderna, componentes modulares e experiência mobile.

## 📁 Estrutura de Pastas

- `index.html` - página principal
- `css/` - estilos em cascata
  - `variables.css` - variáveis CSS (cores, fontes, espaçamento)
  - `reset.css` - reset de estilo cross-browser
  - `base.css` - configurações globais (tipografia, botões, formulários)
  - `layout.css` - layout base, containers, grid
  - `components/`
    - `header.css`
    - `painel.css`
    - `hero.css`
    - `product-category.css`
    - `product-grid.css`
    - `footer.css`
    - `newsletter.css`
- `images/images/` - ativos de imagem
  - `banners/`, `favicons/`, `icons/`, `logo/`, `products/`

## ⚙️ Funcionalidades Implementadas

- Menu responsivo com toggle para mobile
- Hero section com overlay e CTA
- Seção de categorias com cards de estilo
- Grid de produtos com `grid-area` e backgrounds estilizados
- Footer com newsletter, redes sociais e links úteis
- Componentização CSS por área do site

## 📌 Como Usar

1. Clone o projeto ou baixe o ZIP
2. Abra `index.html` em qualquer navegador moderno
3. Não há dependências externas (sem npm, sem bundlers)

## 🔧 Pontos de Personalização

- Atualize `css/variables.css` para cores globais e dimensões
- Ajuste `grid-template-areas` em `css/components/product-grid.css` para mudar o layout de cards
- Troque URLs de imagem em `css/components/*.css` para seu repositório de mídia
- Adicione ícones/links reais em `index.html` na navegação e footer

## 🧪 Checklist de Qualidade

- [x] HTML semanticamente estruturado
- [x] CSS modular por componente
- [x] Responsivo para `max-width: 768px`
- [x] Controles de acessibilidade básica (`aria-label`, `alt`)
- [x] Elementos clicáveis com feedback (botões/links)

## 🛠️ Ajustes extras feitos hoje

- Corrigido erro de chave duplicada no arquivo `css/components/product-grid.css`
- Corrigido seletor `.sneaker-white .sneaker-purple` para `.sneaker-white, .sneaker-purple`
- Adicionado ponto-e-vírgula faltante em `grid-template-areas` dentro do `@media`

## 🚀 Próximos passos sugeridos

- Converter para projeto com Sass/SCSS para ganho de manutenção
- Adicionar scripts em JavaScript para filtros e carrinho
- Aplicar testes de layout (Percy, Backstop) se houver CI
- Documentar padrão de nomeação de CSS (BEM / ITCSS)

## 📌 Contato

Projeto de exemplo. Para dúvidas ou contribuições, abra uma issue ou PR no repositório GitHub.