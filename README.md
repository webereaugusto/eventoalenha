# 🧘‍♀️ Landing Page - International Pilates Heritage Congress

Uma landing page moderna e elegante criada para divulgar o International Pilates Heritage Congress, evento especial realizado na cidade natal de Joseph Pilates.

## ✨ Características

### 🎨 Design Moderno
- **Interface elegante** com gradientes suaves e tipografia premium
- **Responsivo** - funciona perfeitamente em desktop, tablet e mobile
- **Animações fluidas** com efeitos de parallax e transições suaves
- **Paleta de cores profissional** inspirada no wellness e pilates

### 🚀 Funcionalidades

#### Navegação
- **Menu fixo** com efeito glassmorphism
- **Navegação suave** entre seções
- **Menu hambúrguer** responsivo para dispositivos móveis
- **Indicadores visuais** de hover e estados ativos

#### Seções Principais
1. **Hero Section** - Apresentação impactante com animações
2. **Sobre o Evento** - Explicação da importância histórica
3. **Eventos Especiais** - Cards com programação detalhada
4. **Palestrantes** - Perfis dos instrutores renomados
5. **Inscrições** - Formulário de contato funcional

#### Interatividade
- **Contador animado** nas estatísticas
- **Efeitos hover** nos cards e botões
- **Partículas flutuantes** no background
- **Validação de formulário** em tempo real
- **Mensagens de feedback** para o usuário

## 📁 Estrutura dos Arquivos

```
eventopilates/
├── index.html          # Estrutura principal da página
├── styles.css          # Estilos e design responsivo
├── script.js           # Interatividade e animações
└── README.md           # Documentação do projeto
```

## 🛠️ Como Usar

### 1. Visualização Local
Abra o arquivo `index.html` em qualquer navegador moderno para visualizar a landing page.

### 2. Personalização

#### Alterando Conteúdo
- **Textos**: Edite diretamente no arquivo `index.html`
- **Imagens**: Substitua os placeholders por imagens reais
- **Cores**: Modifique as variáveis CSS em `:root` no arquivo `styles.css`

#### Variáveis de Cor (styles.css)
```css
:root {
    --primary-color: #2c3e50;      /* Cor principal */
    --secondary-color: #e74c3c;    /* Cor de destaque */
    --accent-color: #f39c12;       /* Cor de acento */
    --text-dark: #2c3e50;          /* Texto escuro */
    --text-light: #7f8c8d;         /* Texto claro */
}
```

### 3. Adicionando Imagens Reais
Substitua os placeholders (`.image-placeholder`) por imagens reais:

```html
<!-- Ao invés de: -->
<div class="image-placeholder">
    <i class="fas fa-yin-yang"></i>
</div>

<!-- Use: -->
<img src="caminho/para/sua/imagem.jpg" alt="Descrição da imagem">
```

## 🎯 Funcionalidades do Formulário

O formulário de contato inclui:
- ✅ Validação de campos obrigatórios
- ✅ Validação de formato de e-mail
- ✅ Feedback visual para o usuário
- ✅ Simulação de envio (2 segundos)
- ✅ Reset automático após envio

Para conectar com um backend real, modifique a função de envio em `script.js`.

## 📱 Responsividade

A página foi desenvolvida com design mobile-first e inclui:
- **Breakpoints** para tablet (768px) e mobile (480px)
- **Menu hambúrguer** para navegação em telas pequenas
- **Layout flexível** que se adapta a diferentes tamanhos
- **Texto e botões otimizados** para touch

## 🌟 Animações e Efeitos

### Implementados
- **Slide-in animations** ao fazer scroll
- **Contador animado** nas estatísticas
- **Efeito typing** no título principal
- **Partículas flutuantes** no background do hero
- **Hover effects** em cards e botões
- **Transições suaves** entre estados

### Performance
- Animações otimizadas com `requestAnimationFrame`
- Uso de `transform` ao invés de propriedades que causam reflow
- Observers para animações baseadas em scroll
- Debounce em eventos de scroll

## 🔧 Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **CSS3** - Estilos modernos com Grid e Flexbox
- **Vanilla JavaScript** - Interatividade sem dependências
- **Font Awesome** - Ícones profissionais
- **Google Fonts** - Tipografia premium (Playfair Display + Inter)

## 🎨 Paleta de Cores

| Cor | Hex | Uso |
|-----|-----|-----|
| Primary | `#2c3e50` | Textos principais, navegação |
| Secondary | `#e74c3c` | Botões de ação, destaques |
| Accent | `#f39c12` | Ícones, estatísticas |
| Light | `#ecf0f1` | Backgrounds claros |
| Gradient 1 | `#667eea → #764ba2` | Hero section, botões |
| Gradient 2 | `#f093fb → #f5576c` | Cards especiais |
| Gradient 3 | `#4facfe → #00f2fe` | Elementos de apoio |

## 🚀 Próximos Passos

Para uma implementação completa, considere:

1. **Backend Integration**
   - Conectar formulário com API de e-mail
   - Sistema de inscrições real
   - Base de dados para participantes

2. **Otimizações**
   - Compressão de imagens
   - Minificação de CSS/JS
   - Lazy loading para imagens

3. **SEO**
   - Meta tags otimizadas
   - Schema markup
   - Sitemap XML

4. **Analytics**
   - Google Analytics
   - Tracking de conversões
   - Heatmaps de usuário

## 📞 Suporte

Esta landing page foi criada especificamente para o International Pilates Heritage Congress. Para dúvidas ou personalizações adicionais, consulte a documentação ou entre em contato.

---

**🎉 Desenvolvido com ❤️ para a comunidade Pilates** 