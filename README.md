# 🎮 Portfólio Pixel Art 2D

Portfólio profissional para artista de Pixel Art 2D com foco em games, com design retrô-moderno inspirado nos anos 90 e paleta de cores do Super Mario World.

## ✨ Características

- 🎨 Design retrô-moderno com inspiração dos anos 90
- 🌈 Paleta de cores vibrante inspirada em Super Mario World
- 📱 Totalmente responsivo
- ⚡ Animações suaves e interativas
- 🎯 Filtros de portfólio por categoria
- 📧 Formulário de contato integrado
- 🚀 Pronto para deploy no GitHub Pages

## 🎨 Paleta de Cores

O portfólio utiliza uma paleta de cores inspirada em Super Mario World:

- **Vermelho Mario**: `#E52521`
- **Azul Mario**: `#5C94FC`
- **Amarelo Mario**: `#FBD000`
- **Verde Mario**: `#39B54A`
- **Laranja**: `#FF6B35`
- **Roxo**: `#9B59B6`
- **Rosa**: `#FF69B4`
- **Fundo Claro**: `#FFF8E7`

## 📁 Estrutura do Projeto

```
portfolio/
│
├── index.html          # Página principal
├── styles.css          # Estilos e animações
├── script.js           # Interatividade e funcionalidades
├── README.md           # Este arquivo
│
└── assets/             # Pasta para seus assets
    ├── images/         # Imagens do portfólio
    │   ├── characters/ # Sprites de personagens
    │   ├── environments/ # Tilesets e cenários
    │   ├── animations/ # Animações
    │   └── ui/         # UI e ícones
    └── icons/          # Ícones adicionais
```

## 🚀 Como Usar

### 1. Personalização

1. **Substitua os placeholders de imagens**:
   - Adicione suas imagens de pixel art na pasta `assets/images/`
   - Atualize os caminhos no `index.html` ou substitua os elementos `.pixel-art-placeholder`

2. **Atualize as informações pessoais**:
   - Edite o texto em `index.html` com suas informações
   - Atualize os links de redes sociais na seção de contato

3. **Configure o formulário de contato**:
   - Para usar um serviço real, descomente e configure o EmailJS no `script.js`
   - Ou use outro serviço como Formspree, Netlify Forms, etc.

### 2. Deploy no GitHub Pages

#### Método 1: Interface do GitHub

1. Crie um repositório no GitHub (ex: `portfolio` ou `seu-usuario.github.io`)
2. Faça upload dos arquivos do projeto
3. Vá em **Settings** > **Pages**
4. Selecione a branch `main` como source
5. Seu site estará disponível em `https://seu-usuario.github.io/portfolio`

#### Método 2: Via Git (Recomendado)

```bash
# 1. Inicialize o repositório Git
git init

# 2. Adicione os arquivos
git add .

# 3. Faça o commit
git commit -m "Initial commit: Portfólio Pixel Art"

# 4. Adicione o repositório remoto do GitHub
git remote add origin https://github.com/seu-usuario/seu-repositorio.git

# 5. Envie para o GitHub
git branch -M main
git push -u origin main
```

Depois, ative o GitHub Pages nas configurações do repositório.

### 3. Nome do Repositório Especial

Se você quiser que seu site seja acessível em `https://seu-usuario.github.io` (sem o nome do repositório), crie um repositório com o nome exato `seu-usuario.github.io`.

## 🎯 Funcionalidades

### Filtros de Portfólio
- Filtre trabalhos por categoria: Todos, Personagens, Ambientes, Animações, UI/Icons
- Animações suaves ao filtrar

### Navegação
- Menu fixo no topo
- Scroll suave entre seções
- Destaque automático da seção ativa

### Formulário de Contato
- Validação de campos
- Feedback visual ao enviar
- Pronto para integração com serviços de email

### Animações
- Efeitos de hover nos cards
- Animações ao scroll
- Efeitos de texto pixel art
- Grid animado no hero

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica
- **CSS3**: Estilização moderna com variáveis CSS, Grid e Flexbox
- **JavaScript (Vanilla)**: Interatividade sem dependências
- **Google Fonts**: Fonte "Press Start 2P" para texto pixel art

## 📝 Personalização Avançada

### Adicionar Novas Categorias

1. Adicione um botão de filtro em `index.html`:
```html
<button class="filter-btn" data-filter="nova-categoria">Nova Categoria</button>
```

2. Adicione o atributo `data-category` nos itens do portfólio:
```html
<div class="portfolio-item" data-category="nova-categoria">
```

### Modificar Cores

Edite as variáveis CSS no início do arquivo `styles.css`:

```css
:root {
    --mario-red: #E52521;
    --mario-blue: #5C94FC;
    /* ... outras cores ... */
}
```

### Adicionar Mais Seções

1. Adicione a seção no HTML
2. Adicione o link no menu de navegação
3. Estilize conforme necessário no CSS

## 📱 Responsividade

O portfólio é totalmente responsivo e se adapta a:
- 💻 Desktops
- 📱 Tablets
- 📱 Smartphones

## 🎨 Dicas para Melhorar

1. **Otimize suas imagens**: Use formatos como PNG para pixel art, mas comprima para web
2. **Adicione mais conteúdo**: Inclua descrições detalhadas dos seus trabalhos
3. **Integre redes sociais**: Adicione mais links e widgets
4. **Adicione um blog**: Compartilhe seu processo criativo
5. **SEO**: Adicione meta tags e descrições para melhor indexação

## 📄 Licença

Este projeto é de código aberto e está disponível para uso pessoal e comercial.

## 🙏 Créditos

- Design inspirado nos anos 90 e Super Mario World
- Fonte "Press Start 2P" do Google Fonts

## 📧 Suporte

Se tiver dúvidas ou sugestões, sinta-se à vontade para abrir uma issue no repositório!

---

**Feito com ❤️ e pixels!** 🎮✨

