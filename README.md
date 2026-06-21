# 💼 Williams Rodrigues - Portfólio Profissional

Um portfólio online moderno e responsivo que apresenta expertise em **Data Science**, **Business Intelligence** e **Desenvolvimento Full Stack**.

![Badge Versão](https://img.shields.io/badge/versão-1.0-blue)
![Badge Status](https://img.shields.io/badge/status-ativo-brightgreen)
![Badge Licença](https://img.shields.io/badge/licença-MIT-green)

## 🎯 Sobre o Projeto

Este é um portfólio profissional desenvolvido com **HTML5** e **CSS3** puro, apresentando um design moderno, elegante e totalmente responsivo. O projeto destaca a expertise profissional em:

- 📊 **Ciência de Dados e Analytics**
- 📈 **Business Intelligence**
- 💻 **Desenvolvimento Full Stack**

## ✨ Características Principais

### 🎨 Design Moderno
- Interface elegante com paleta de cores moderna (tons de azul/verde)
- Animações suaves e fluidas
- Efeitos visuais sofisticados (gradientes, blur, hover effects)
- Totalmente responsivo (mobile, tablet, desktop)

### 📱 Seções Incluídas

1. **Hero Section**
   - Apresentação principal com call-to-action
   - Estatísticas profissionais
   - Botões interativos

2. **Expertise**
   - Cards descritivos das áreas de especialização
   - Listas de competências
   - Ícones visuais

3. **Projetos**
   - Portfólio de projetos realizados
   - Tags de tecnologias utilizadas
   - Descrições detalhadas

4. **Experiência**
   - Timeline interativa
   - Histórico profissional
   - Períodos e empresas

5. **Contato**
   - Formulário de contato
   - Links para redes sociais
   - Informações de contato direto

### 🚀 Funcionalidades

- **Navegação Fixa**: Header sticky com menu navegável
- **Animações CSS**: Transições suaves e efeitos hover
- **Background Animado**: Efeitos de gradiente e movimento
- **Responsividade**: Design adaptativo para todos os tamanhos de tela
- **Performance Otimizada**: Código CSS eficiente e minimalista

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **CSS3** - Estilos e animações
  - Flexbox
  - CSS Grid
  - Media Queries
  - Gradientes
  - Animações keyframes
- **Google Fonts** - Tipografia profissional
  - Bebas Neue
  - Playfair Display
  - Work Sans

## 📋 Estrutura do Projeto

```
Profissional_apresenta-o-main/
├── index.html              # Arquivo principal HTML
├── README.md              # Este arquivo
└── 1517312655916.jpg      # Imagem de perfil
```

## 🎨 Paleta de Cores

| Cor | Hexadecimal | Uso |
|-----|-------------|-----|
| Primary | #028090 | Cor principal do tema |
| Secondary | #00A896 | Cor secundária |
| Accent | #02C39A | Destaque e interações |
| Dark | #1A202C | Texto escuro |
| Darker | #0D1117 | Fundo |
| Light | #F7FAFC | Texto claro |
| Gray | #718096 | Texto secundário |

## 📖 Como Usar

### Visualizar o Portfólio

1. Abra o arquivo `index.html` em um navegador web
2. Navegue pelas seções usando o menu no topo
3. Interaja com os elementos para ver as animações

### Personalizar Conteúdo

Para editar as informações do portfólio, abra o arquivo `index.html` e procure pelos seguintes elementos HTML:

```html
<!-- Nome e Título -->
<h1>Williams Rodrigues</h1>
<p class="subtitle">Especialista em Ciência de Dados</p>

<!-- Descrição -->
<p class="description">Sua descrição aqui</p>

<!-- Áreas de Expertise -->
<div class="expertise-card">
  <!-- Edite o conteúdo das seções de expertise -->
</div>

<!-- Projetos -->
<div class="project-card">
  <!-- Edite informações dos projetos -->
</div>

<!-- Experiência -->
<div class="timeline-item">
  <!-- Edite histórico profissional -->
</div>
```

### Adicionar/Alterar Imagem de Perfil

1. Substitua a imagem `1517312655916.jpg` por sua foto
2. Ou altere a referência no HTML:

```html
<img src="seu-arquivo-de-imagem.jpg" class="profile-img" alt="Perfil">
```

## 🎯 Principais Seções do HTML

### Header/Navegação
- Menu fixa no topo
- Links para as diferentes seções
- Logo com efeito gradiente

### Hero Section
- Grande titulo introdutório
- Estatísticas principais
- Botões de ação (CTA)
- Imagem/Card de perfil

### Expertise Cards
- Áreas de especialização
- Descrições detalhadas
- Listas de habilidades
- Efeitos hover interativos

### Projects Grid
- Cards para cada projeto
- Informações do projeto
- Tags de tecnologias
- Ano/período de realização

### Experience Timeline
- Linha do tempo vertical
- Histórico profissional
- Períodos e empresas
- Descrições de responsabilidades

### Contact Section
- Formulário (estrutura pronta)
- Links de contato
- Redes sociais

## 🔧 Personalizações Comuns

### Mudar Cores do Tema

No CSS, dentro da tag `<style>`, localize `:root` e altere as variáveis:

```css
:root {
    --primary: #sua-cor-aqui;
    --secondary: #sua-cor-secundaria;
    --accent: #sua-cor-destaque;
    /* ... outras cores */
}
```

### Adicionar Novas Seções

1. Crie um novo `<section>` com classe apropriada
2. Copie o padrão de CSS de uma seção similar
3. Adapte para o novo conteúdo

### Ajustar Tamanho de Fontes

Localize as classes CSS de títulos e textos, exemplo:

```css
.section-title {
    font-size: 3.5rem; /* Altere este valor */
}
```

## 📱 Responsividade

O portfólio foi desenvolvido com abordagem mobile-first e utiliza **Media Queries** para adaptação em diferentes tamanhos de tela:

- **Desktop**: Experiência completa com grid de 2+ colunas
- **Tablet**: Layout otimizado com colunas reduzidas
- **Mobile**: Single column com elementos stackados verticalmente

## ✅ Checklist de Customização

- [ ] Atualizar nome e título profissional
- [ ] Substituir imagem de perfil
- [ ] Atualizar descrição profissional
- [ ] Adicionar/editar áreas de expertise
- [ ] Adicionar projetos realizados
- [ ] Atualizar histórico profissional
- [ ] Adicionar links de redes sociais
- [ ] Configurar email de contato
- [ ] Testar em diferentes dispositivos
- [ ] Validar links e formulários

## 🚀 Deploy

### Opções de Hospedagem

Este projeto pode ser hospedado gratuitamente em:

- **GitHub Pages** - Acesso em: seu-usuario.github.io
- **Netlify** - Deploy automático via Git
- **Vercel** - Plataforma moderna para projetos estáticos
- **GitLab Pages** - Alternativa ao GitHub Pages
- **000webhost** - Hospedagem gratuita com domínio

### Deploy no GitHub Pages

1. Faça push do repositório para GitHub
2. Nas configurações do repositório, vá para "Pages"
3. Selecione a branch main como source
4. Seu portfólio estará em: `https://seu-usuario.github.io/Profissional_apresenta-o-main`

## 📊 Estatísticas do Código

- **Linhas de HTML**: ~800
- **Linhas de CSS**: ~500+
- **Animações**: 5+ animações principais
- **Tamanho da página**: ~50KB (otimizado)
- **Tempo de carregamento**: < 1s (depende da hospedagem)

## 🐛 Troubleshooting

### Imagem não aparece
- Verifique o caminho correto do arquivo
- Certifique-se que o arquivo está na mesma pasta ou use caminho absoluto

### Animações muito rápidas/lentas
- Ajuste o valor de `animation-duration` no CSS

### Problema de responsividade
- Abra as ferramentas de desenvolvedor (F12)
- Verifique a meta tag viewport
- Teste em diferentes breakpoints

## 📝 Licença

Este projeto está disponível sob a licença **MIT**. Sinta-se livre para usar, modificar e distribuir conforme necessário.

## 👤 Autor

**Williams Rodrigues**
- 📊 Especialista em Ciência de Dados
- 📈 Business Intelligence Professional
- 💻 Full Stack Developer

## 🤝 Contribuições

Sugestões de melhorias são bem-vindas! Faça um fork do projeto e envie um pull request com suas mudanças.

## 📚 Recursos Úteis

- [MDN Web Docs](https://developer.mozilla.org/) - Documentação HTML/CSS
- [CSS Tricks](https://css-tricks.com/) - Tutoriais CSS avançados
- [Can I Use](https://caniuse.com/) - Compatibilidade de navegadores
- [Google Fonts](https://fonts.google.com/) - Tipografia gratuita

## 📞 Contato e Redes Sociais

*Adicione seus links de contato aqui*

- 📧 Email: seu-email@exemplo.com
- 🔗 LinkedIn: linkedin.com/in/seu-perfil
- 💼 GitHub: github.com/seu-usuario
- 🐦 Twitter: @seu-usuario

---

**Última atualização**: 2026
**Versão**: 1.0
**Status**: ✅ Produção
# Portif-lio-Williams-Rodrigues
