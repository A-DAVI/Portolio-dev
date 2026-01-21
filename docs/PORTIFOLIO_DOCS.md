# 📋 DOCUMENTAÇÃO: Landing Page - Portfólio Davi Cassoli

## 🎯 Objetivo
Criar uma landing page profissional de portfólio pessoal para desenvolvedor backend, focada em atrair recrutadores e demonstrar competência técnica.

---

## 👤 Dados do Usuário

### Informações Pessoais
- **Nome:** Davi Cassoli Lira
- **Título:** Desenvolvedor Backend | Automação e IA | Python & Java
- **Localização:** Jandaia do Sul, PR - Brasil
- **Email:** cassolidavi603@gmail.com
- **LinkedIn:** https://linkedin.com/in/davi-cassoli-lira
- **GitHub:** https://github.com/A-DAVI
- **Disponibilidade:** Trabalho remoto

### Bio/Headline
> Desenvolvedor backend com foco em automação, IA aplicada e sistemas confiáveis. Trabalho na interseção entre código, regras de negócio e decisões críticas, usando IA como ferramenta — não como atalho.

---

## 🎨 Identidade Visual

### Cores
```css
/* Paleta Principal - Azul Acinzentado */
--primary-dark: #0f1419;      /* Fundo principal */
--primary-medium: #1e2a3a;    /* Fundo secundário */
--primary-light: #2a3a4a;     /* Cards/elementos */

--accent-blue: #7a9bb8;       /* Destaque principal */
--accent-blue-light: #8aa3b8; /* Destaque hover */

--text-primary: #e8eef3;      /* Texto principal */
--text-secondary: #6b7c8a;    /* Texto secundário */
--text-muted: #4a5a68;        /* Texto sutil */

--border-color: rgba(100, 130, 160, 0.15);
--glow-color: rgba(70, 100, 130, 0.15);
```

### Tipografia
```css
/* Fontes */
--font-display: 'Space Grotesk', sans-serif;  /* Títulos */
--font-body: 'Inter', sans-serif;              /* Corpo */
--font-mono: 'JetBrains Mono', monospace;      /* Código */

/* Tamanhos */
--text-hero: 4rem;      /* 64px - Título principal */
--text-h1: 2.5rem;      /* 40px - Seções */
--text-h2: 1.75rem;     /* 28px - Subtítulos */
--text-h3: 1.25rem;     /* 20px - Cards */
--text-body: 1rem;      /* 16px - Corpo */
--text-small: 0.875rem; /* 14px - Labels */
```

### Estilo Geral
- **Tema:** Dark mode
- **Atmosfera:** Profissional, técnico, clean
- **Elementos:** 
  - Grid sutil no background
  - Glows suaves nos cantos
  - Bordas com baixa opacidade
  - Transições suaves (0.3s ease)

---

## 📐 Estrutura da Página

### Layout Geral
```
┌─────────────────────────────────────────────────────────────┐
│                        NAVBAR                                │
│  Logo                              Links    CTA (Contato)   │
├─────────────────────────────────────────────────────────────┤
│                                                              │
│                      HERO SECTION                            │
│                                                              │
│    [Texto]                              [Imagem/Avatar]      │
│    Nome + Título                        Foto ou Ilustração   │
│    Bio curta                                                 │
│    CTAs (GitHub, LinkedIn, CV)                               │
│                                                              │
├─────────────────────────────────────────────────────────────┤
│                                                              │
│                    COMO EU PENSO                             │
│                                                              │
│    [Imagem/Ícone]                       [Texto]              │
│    Ilustração                           4 princípios         │
│                                                              │
├─────────────────────────────────────────────────────────────┤
│                                                              │
│                    O QUE EU FAÇO                             │
│                                                              │
│    [Texto]                              [Imagem/Ícones]      │
│    4 áreas de atuação                   Stack visual         │
│                                                              │
├─────────────────────────────────────────────────────────────┤
│                                                              │
│                      PROJETOS                                │
│                                                              │
│  ┌─────────────────────────────────────────────────────┐    │
│  │  FORM-AI                                             │    │
│  │  [Screenshot]              [Descrição + Stack]       │    │
│  └─────────────────────────────────────────────────────┘    │
│                                                              │
│  ┌─────────────────────────────────────────────────────┐    │
│  │  MYBUDDY                                             │    │
│  │  [Descrição + Stack]       [Screenshot]              │    │
│  └─────────────────────────────────────────────────────┘    │
│                                                              │
│  ┌─────────────────────────────────────────────────────┐    │
│  │  CENTRAL DE CONTROLE                                 │    │
│  │  [Screenshot]              [Descrição + Stack]       │    │
│  └─────────────────────────────────────────────────────┘    │
│                                                              │
├─────────────────────────────────────────────────────────────┤
│                                                              │
│                    GITHUB STATS                              │
│                                                              │
│              [Cards com estatísticas]                        │
│                                                              │
├─────────────────────────────────────────────────────────────┤
│                                                              │
│                      CONTATO                                 │
│                                                              │
│    Texto convidativo + Links (Email, LinkedIn, GitHub)       │
│                                                              │
├─────────────────────────────────────────────────────────────┤
│                        FOOTER                                │
│           © 2026 Davi Cassoli • Feito com ❤️                │
└─────────────────────────────────────────────────────────────┘
```

---

## 📑 Seções Detalhadas

### 1. Navbar
```
Componentes:
- Logo/Nome: "DC" ou "Davi Cassoli" (clicável, volta pro topo)
- Links de navegação: Sobre | Projetos | Contato
- CTA Button: "Fale Comigo" (scroll pro contato)

Comportamento:
- Sticky no topo
- Background blur quando scrollar
- Mobile: hamburger menu
```

### 2. Hero Section
```
Layout: Flex, imagem à direita, texto à esquerda

Conteúdo Esquerda:
- Tag: "Desenvolvedor Backend"
- Título: "Davi Cassoli"
- Subtítulo: "Automação, IA Aplicada e Sistemas Confiáveis"
- Bio: "Trabalho na interseção entre código, regras de negócio e decisões críticas, usando IA como ferramenta — não como atalho."
- Botões:
  - [GitHub] (ícone + texto)
  - [LinkedIn] (ícone + texto)
  - [Download CV] (secundário)

Conteúdo Direita:
- Avatar/Foto profissional OU
- Ilustração abstrata de código/terminal OU
- Placeholder estilizado com iniciais "DC"

Efeitos:
- Texto com fade-in da esquerda
- Imagem com fade-in da direita
- Typing effect no subtítulo (opcional)
```

### 3. Como Eu Penso (Filosofia)
```
Layout: Flex, imagem à esquerda, texto à direita

Conteúdo Esquerda:
- Ilustração representando "pensamento/processo"
- Pode ser ícone grande ou imagem abstrata

Conteúdo Direita:
- Título: "Como eu penso software"
- 4 cards/bullets com ícones:
  
  🧠 "IA não substitui entendimento"
     Uso LLMs e agents com limites claros, validações e regras 
     determinísticas quando necessário.
  
  ⚡ "Automação é responsabilidade"
     Reduzir esforço humano também significa reduzir riscos.
  
  🎯 "Simplicidade escala melhor"
     Do que abstrações frágeis.
  
  🔍 "Sistemas observáveis"
     Prefiro sistemas explicáveis e fáceis de manter.
```

### 4. O Que Eu Faço
```
Layout: Flex, texto à esquerda, imagem à direita

Conteúdo Esquerda:
- Título: "O que eu faço na prática"
- 4 áreas com ícones:
  
  </> APIs e Serviços Backend
      Desenvolvimento de sistemas robustos e escaláveis
  
  🔄 Automação de Processos
      Integração entre sistemas e eliminação de tarefas manuais
  
  🤖 Projetos com IA
      LLMs, agents e arquiteturas híbridas
  
  📋 Tradução de Regras de Negócio
      Transformar requisitos complexos em código confiável

Conteúdo Direita:
- Stack visual (ícones das tecnologias)
- Python, Java, Spring Boot, FastAPI, Docker, Git, LangChain
- Pode usar skillicons.dev ou ícones customizados
```

### 5. Projetos
```
Layout: Cards grandes, alternando posição da imagem

=== PROJETO 1: Form-AI ===
Layout: Imagem à esquerda, texto à direita

Imagem:
- Screenshot do sistema OU
- Mockup/ilustração representativa
- Placeholder: ícone 🧠 grande com fundo gradiente

Texto:
- Tag: "Projeto Principal"
- Título: "Form-AI"
- Subtítulo: "Sistema de Diagnóstico Tributário"
- Descrição: "Sistema de consultoria tributária automatizada para 
  a Reforma Tributária brasileira (LC 214/2025). Arquitetura híbrida 
  combinando LLMs e regras determinísticas para garantir precisão 
  nos cálculos."
- Highlights (com ícones):
  • Agents + regras determinísticas
  • Controle de alucinação numérica
  • API Receita Federal
  • 19 fontes legais
- Stack: Python, LangChain, MCP, Tauri, React
- Quote: "IA usada onde faz sentido. Regras usadas onde precisão 
  é obrigatória."
- Link: [Ver no GitHub] (se público) ou [Projeto Privado]


=== PROJETO 2: MyBuddy ===
Layout: Texto à esquerda, imagem à direita

Imagem:
- Screenshot da plataforma OU
- Placeholder: ícone 🐾 grande com fundo gradiente

Texto:
- Tag: "Projeto Acadêmico"
- Título: "MyBuddy"
- Subtítulo: "Plataforma de Adoção de Pets"
- Descrição: "Plataforma desenvolvida em ambiente colaborativo 
  durante imersão profissional. APIs REST completas com autenticação 
  e trabalho real em equipe."
- Highlights:
  • APIs REST com Spring Boot
  • Autenticação JWT
  • Git Flow e code review
  • 11 PRs mergeados
- Stack: Java, Spring Boot, Spring Security, MySQL
- Link: [Ver no GitHub]


=== PROJETO 3: Central de Controle ===
Layout: Imagem à esquerda, texto à direita

Imagem:
- Screenshot do sistema desktop OU
- Placeholder: ícone 📊 grande com fundo gradiente

Texto:
- Tag: "Projeto Profissional"
- Título: "Central de Controle de Despesas"
- Subtítulo: "Sistema Desktop Empresarial"
- Descrição: "Sistema para registro e gestão de despesas empresariais 
  com interface moderna e geração de relatórios PDF profissionais."
- Highlights:
  • Interface CustomTkinter
  • Relatórios em PDF
  • Arquitetura modular
  • Em uso real
- Stack: Python, CustomTkinter, ReportLab
- Link: [Ver no GitHub]
```

### 6. GitHub Stats
```
Layout: Centralizado, cards lado a lado

Componentes:
- GitHub Stats Card (github-readme-stats)
- Streak Stats (opcional)
- Top Languages (opcional)

Alternativa se não quiser usar APIs externas:
- Cards estáticos com:
  - Repositórios: 31
  - Contribuições: X
  - PRs: 11+ mergeados
  - Linguagem principal: Python/Java
```

### 7. Contato
```
Layout: Centralizado

Título: "Vamos conversar?"
Subtítulo: "Aberto a oportunidades em backend, automação e IA aplicada"

Cards de contato (3 colunas):
┌─────────────┐  ┌─────────────┐  ┌─────────────┐
│   📧        │  │   💼        │  │   🐙        │
│   Email     │  │  LinkedIn   │  │   GitHub    │
│  cassolid.. │  │  /davi-cas..│  │  /A-DAVI    │
└─────────────┘  └─────────────┘  └─────────────┘

Ou botão grande:
[✉️ Enviar Email] (mailto:cassolidavi603@gmail.com)
```

### 8. Footer
```
Layout: Simples, centralizado

Conteúdo:
- "© 2026 Davi Cassoli"
- "Feito com ❤️ e muito ☕"
- Links: GitHub | LinkedIn | Email (ícones pequenos)
```

---

## 🖼️ Assets Necessários

### Imagens (por prioridade)
1. **Avatar/Foto** (opcional)
   - Se não tiver: usar placeholder com iniciais "DC"
   - Tamanho: 400x400px mínimo

2. **Screenshots dos projetos** (opcional)
   - Form-AI: tela principal
   - MyBuddy: tela de listagem de pets
   - Central de Controle: dashboard
   - Se não tiver: usar placeholders estilizados

3. **Ilustrações** (pode gerar ou usar de biblioteca)
   - Hero: ilustração de código/terminal
   - Filosofia: ilustração de processo/pensamento

### Ícones
- Usar Lucide Icons ou Heroicons
- Tecnologias: skillicons.dev ou devicons

---

## 📱 Responsividade

### Breakpoints
```css
/* Mobile First */
--mobile: 320px;
--tablet: 768px;
--desktop: 1024px;
--wide: 1280px;
```

### Comportamento por Seção

**Navbar:**
- Mobile: hamburger menu
- Desktop: links visíveis

**Hero:**
- Mobile: stack vertical (texto em cima, imagem embaixo)
- Desktop: lado a lado

**Seções alternadas:**
- Mobile: sempre stack vertical
- Desktop: alterna esquerda/direita

**Projetos:**
- Mobile: cards empilhados, imagem em cima
- Desktop: lado a lado alternando

**Contato:**
- Mobile: cards empilhados
- Desktop: 3 colunas

---

## ⚡ Interações e Animações

### Scroll Animations
```css
/* Fade in from left */
.fade-left {
  opacity: 0;
  transform: translateX(-30px);
  transition: all 0.6s ease;
}
.fade-left.visible {
  opacity: 1;
  transform: translateX(0);
}

/* Fade in from right */
.fade-right {
  opacity: 0;
  transform: translateX(30px);
  transition: all 0.6s ease;
}
.fade-right.visible {
  opacity: 1;
  transform: translateX(0);
}

/* Fade in up */
.fade-up {
  opacity: 0;
  transform: translateY(30px);
  transition: all 0.6s ease;
}
.fade-up.visible {
  opacity: 1;
  transform: translateY(0);
}
```

### Hover Effects
```css
/* Cards */
.card:hover {
  transform: translateY(-5px);
  border-color: var(--accent-blue);
  box-shadow: 0 10px 40px rgba(70, 100, 130, 0.2);
}

/* Botões */
.button:hover {
  background: var(--accent-blue);
  transform: translateY(-2px);
}

/* Links */
.link:hover {
  color: var(--accent-blue);
}
```

### Efeitos Especiais (opcional)
- Cursor glow que segue o mouse
- Partículas no background do hero
- Typing effect no subtítulo
- Parallax suave nas imagens

---

## 🛠️ Tecnologias Sugeridas

### Opção 1: HTML/CSS/JS Puro
- Mais simples
- Fácil de hospedar (GitHub Pages, Netlify, Vercel)
- Um arquivo HTML, um CSS, um JS

### Opção 2: React + Tailwind
- Mais organizado
- Componentes reutilizáveis
- Fácil de expandir depois

### Opção 3: Next.js
- SSG (Static Site Generation)
- Ótimo para SEO
- Mais complexo, mas mais profissional

**Recomendação:** Começar com HTML/CSS/JS puro. Simples, rápido, e você pode converter pra React depois se quiser.

---

## 📁 Estrutura de Arquivos (HTML/CSS/JS)

```
portfolio/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── main.js
├── assets/
│   ├── images/
│   │   ├── avatar.png (opcional)
│   │   ├── form-ai-screenshot.png (opcional)
│   │   ├── mybuddy-screenshot.png (opcional)
│   │   └── central-screenshot.png (opcional)
│   └── icons/
│       └── (se usar locais)
└── README.md
```

---

## ✅ Checklist de Implementação

### Fase 1: Estrutura
- [ ] Criar HTML base com todas as seções
- [ ] Adicionar meta tags (SEO, Open Graph)
- [ ] Estruturar semanticamente (header, main, section, footer)

### Fase 2: Estilo
- [ ] Configurar variáveis CSS
- [ ] Estilizar navbar
- [ ] Estilizar hero
- [ ] Estilizar seções alternadas
- [ ] Estilizar cards de projetos
- [ ] Estilizar contato e footer
- [ ] Responsividade mobile

### Fase 3: Interatividade
- [ ] Scroll suave
- [ ] Animações de entrada (Intersection Observer)
- [ ] Navbar com background no scroll
- [ ] Mobile menu toggle

### Fase 4: Polish
- [ ] Adicionar imagens reais (se tiver)
- [ ] Testar em diferentes dispositivos
- [ ] Otimizar performance
- [ ] Validar HTML/CSS

### Fase 5: Deploy
- [ ] Subir no GitHub
- [ ] Configurar GitHub Pages ou Vercel
- [ ] Testar URL final
- [ ] Adicionar link no LinkedIn e currículo

---

## 📝 Notas Adicionais

### SEO
```html
<title>Davi Cassoli | Desenvolvedor Backend | Python & Java</title>
<meta name="description" content="Desenvolvedor backend com foco em automação, IA aplicada e sistemas confiáveis. Python, Java, Spring Boot, LangChain.">
<meta name="keywords" content="desenvolvedor backend, python, java, automação, IA, RPA, spring boot">
```

### Open Graph (para compartilhamento)
```html
<meta property="og:title" content="Davi Cassoli | Desenvolvedor Backend">
<meta property="og:description" content="Automação, IA Aplicada e Sistemas Confiáveis">
<meta property="og:image" content="URL_DA_IMAGEM_DE_PREVIEW">
<meta property="og:url" content="URL_DO_SITE">
```

### Performance
- Usar fontes do Google Fonts com display=swap
- Lazy loading nas imagens
- Minificar CSS/JS em produção
- Comprimir imagens

---

## 🚀 Comando para Iniciar

Quando for implementar, pode usar este prompt no Claude Code:

```
Crie uma landing page de portfólio seguindo a documentação em PORTFOLIO_DOCS.md. 
Comece pelo HTML estrutural, depois CSS, depois JS.
Use HTML/CSS/JS puro.
Siga a paleta de cores, tipografia e layout definidos.
```

---

**Documentação criada em:** Janeiro/2026
**Autor:** Davi Cassoli + Claude
**Versão:** 1.0
