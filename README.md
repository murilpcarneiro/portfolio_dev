# Portfolio - Murilo Carneiro

Um portfolio moderno e responsivo de um desenvolvedor fullstack, desenvolvido com HTML semântico, CSS otimizado e design elegante.

## 🎨 Características

- **Design Responsivo** - Otimizado para todos os tamanhos de tela
- **Semântica HTML** - Código estruturado e acessível
- **CSS Otimizado** - Variáveis CSS, BEM pattern e reutilização de classes
- **Animações Suaves** - Transições fluidas e efeitos hover interativos
- **Performance** - Código limpo e bem organizado
- **Acessibilidade** - ARIA labels e atributos semânticos

## 📋 Seções

### 1. **Hero Section**

- Foto de perfil com badge
- Apresentação pessoal
- Descrição profissional
- Call-to-action para próxima seção

### 2. **Tecnologias**

- Exibição visual das skills utilizadas
- GitHub, HTML, CSS, JavaScript, React e Node.js

### 3. **Projetos**

- Grade de 6 projetos em destaque
- Imagens, títulos e descrições
- Efeito hover interativo

### 4. **Serviços**

- 3 serviços principais oferecidos
- Ícones coloridos (Phosphor Icons)
- Cards com descrições detalhadas

### 5. **Contato**

- Links para redes sociais (LinkedIn, Instagram, GitHub)
- Email direto
- Animações e efeitos hover melhorados

## 🛠️ Tecnologias Utilizadas

### Frontend

- **HTML5** - Estrutura semântica
- **CSS3** - Estilização com variáveis e BEM pattern
- **Phosphor Icons** - Biblioteca de ícones moderna

### Tipografia

- **Asap** - Títulos
- **Inconsolata** - Subtítulos (monospace)
- **Maven Pro** - Textos corpo

## 🤖 Sobre a IA neste Projeto

A inteligência artificial foi utilizada **apenas para otimizar o CSS e deixar o HTML mais semântico**. As funcionalidades, design, conteúdo e estrutura geral do portfolio foram desenvolvidos manualmente.

**Otimizações realizadas:**

- Consolidação de propriedades CSS redundantes
- Implementação de variáveis CSS e BEM pattern
- Conversão de HTML para estrutura semântica com tags apropriadas
- Criação de classes utilitárias reutilizáveis
- Remoção de código duplicado

## 📁 Estrutura do Projeto

```
portfolio_dev/
├── index.html          # Estrutura HTML principal
├── style.css          # Estilos CSS
├── assets/            # Imagens e ícones
│   ├── profile.jpg
│   ├── Code.svg
│   ├── Background_Intro.png
│   ├── Background_Contacts.png
│   ├── Thumbnail_Project-*.png
│   ├── GitHub.svg
│   ├── HTML.svg
│   ├── CSS.svg
│   ├── JavaScript.svg
│   ├── React.svg
│   ├── Node.js.svg
│   ├── CaretDoubleDown.svg
│   └── ArrowUpRight.svg
└── README.md          # Este arquivo
```

## 🎯 Otimizações CSS

### Variáveis

```css
:root {
  --red: #e3646e;
  --purple: #bb72e9;
  --blue: #3996db;
  /* ... mais cores ... */

  --title-lg: bold 56px / 120% var(--asap);
  --text-md: 400 16px / 140% var(--maven-pro);
  /* ... mais tipografias ... */
}
```

### Classes Utilitárias

- `.accent` - Destaca texto em vermelho
- `.flex-column-center` - Flex column com alinhamento central
- `.section-header` - Header reutilizável de seções
- `.grid-3-columns` - Grid com 3 colunas e espaçamento padrão

### BEM Pattern

Todas as classes seguem o padrão BEM:

```css
.section-header /* Bloco */
/* Bloco */
/* Bloco */
/* Bloco */
.hero__container /* Elemento */
.project-card__title; /* Elemento aninhado */
```

## ✨ Efeitos e Animações

### Scroll Suave

```css
scroll-behavior: smooth;
```

### Hover Effects

**Cards de Projetos**

- Mudança de cor da borda
- Transição suave (0.3s)

**Cards de Serviços**

- Cores de ícones específicas (roxo, amarelo, verde)
- Sem animação no estado padrão

**Links de Contato**

- Elevação do elemento (translateY)
- Sombra azul
- Ícone em destaque com scale
- Seta se move diagonalmente

## 🎨 Paleta de Cores

| Cor       | Variável              | Uso                   |
| --------- | --------------------- | --------------------- |
| Vermelho  | `--red: #e3646e`      | Destaques, subtítulos |
| Roxo      | `--purple: #bb72e9`   | Ícone serviço 1       |
| Azul      | `--blue: #3996db`     | Hover effects         |
| Verde     | `--green: #82bc4f`    | Ícone serviço 3       |
| Amarelo   | `--yellow: #eabd5f`   | Ícone serviço 2       |
| Cinza 100 | `--gray-100: #e2e4e9` | Texto principal       |
| Cinza 200 | `--gray-200: #c0c4ce` | Texto secundário      |
| Cinza 300 | `--gray-300: #878ea1` | Texto terciário       |
| Cinza 400 | `--gray-400: #292c34` | Cards/Botões          |
| Cinza 500 | `--gray-500: #16181d` | Background sections   |
| Cinza 600 | `--gray-600: #0d0e11` | Dark background       |

## 📱 Responsividade

- **Desktop**: Layout completo com grid 3 colunas
- **Tablet**: Ajustes de padding e tamanhos
- **Mobile**: Stack vertical, width 100%

Pontos de quebra recomendados:

- `768px` - Tablet
- `480px` - Mobile pequeno

## ♿ Acessibilidade

- Estrutura semântica com `<main>`, `<section>`, `<header>`, `<nav>`
- `aria-label` em navegações
- `alt` text em imagens
- `rel="noopener noreferrer"` em links externos
- Contraste adequado entre cores

## 🚀 Como Usar

1. Clone o repositório:

```bash
git clone <seu-repositorio>
cd portfolio_dev
```

2. Abra o arquivo `index.html` no navegador:

```bash
# Windows
start index.html

# macOS
open index.html

# Linux
xdg-open index.html
```

3. Para desenvolvimento, abra em um editor de código:

```bash
code .
```

## 📝 Customização

### Mudar Cores

Edite as variáveis em `:root` no `style.css`:

```css
--red: #e3646e; /* Mude para sua cor */
```

### Adicionar/Remover Projetos

Adicione um novo `<li class="project-card">` no HTML:

```html
<li class="project-card">
  <img class="project-card__image" src="./assets/novo.png" alt="Novo Projeto" />
  <div class="project-card__content">
    <h3 class="project-card__title">Título</h3>
    <p class="project-card__description">Descrição...</p>
  </div>
</li>
```

### Mudar Links de Contato

Edite os `href` em `.contact__item a`:

```html
<a href="https://seu-link.com" target="_blank" rel="noopener noreferrer"></a>
```

## 🐛 Troubleshooting

**Ícones não aparecem?**

- Verifique se o CDN do Phosphor Icons está acessível
- Confirme que as classes `ph ph-*` estão corretas

**Imagens não carregam?**

- Verifique o caminho das imagens em `./assets/`
- Certifique-se que os arquivos existem

**Fontes estranhas?**

- Limpe o cache do navegador (Ctrl+Shift+Delete)
- Verifique se o Google Fonts está acessível

## 📄 Licença

Este projeto é de uso pessoal. Sinta-se livre para usar como base para seu próprio portfolio!

## 👨‍💻 Autor

**Murilo Carneiro** - Desenvolvedor Fullstack

- 🔗 [LinkedIn](https://www.linkedin.com/in/murilo-carneiro-908b8a2b4/)
- 📸 [Instagram](https://www.instagram.com/murilopcarneiro_/)
- 💻 [GitHub](https://github.com/murilpcarneiro)
- 📧 [Email](mailto:murilpcarneiro@gmail.com)

---

Desenvolvido com ❤️ durante o curso Fullstack da Rocketseat
