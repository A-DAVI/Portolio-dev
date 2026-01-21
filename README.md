# Portfolio - Davi Cassoli

Landing page profissional de portfolio pessoal para desenvolvedor backend.

## Estrutura do Projeto

```
portfolio/
├── index.html          # Pagina principal
├── css/
│   └── style.css       # Estilos
├── js/
│   └── main.js         # JavaScript (animacoes, menu mobile)
├── assets/
│   └── images/         # Imagens do projeto
├── Docs/
│   └── PORTIFOLIO_DOCS.md  # Documentacao detalhada
└── README.md           # Este arquivo
```

## Tecnologias

- HTML5
- CSS3 (Dark mode, responsivo)
- JavaScript (vanilla)
- [Lucide Icons](https://lucide.dev/)
- Google Fonts (Inter, Space Grotesk, JetBrains Mono)

## Como Rodar Localmente

### Opcao 1: Abrir direto no navegador
Basta abrir o arquivo `index.html` no navegador.

### Opcao 2: Usar servidor local (recomendado)

**Com Python:**
```bash
# Python 3
python -m http.server 8000

# Acesse: http://localhost:8000
```

**Com Node.js:**
```bash
# Instalar live-server globalmente
npm install -g live-server

# Rodar
live-server
```

**Com VS Code:**
Instale a extensao "Live Server" e clique em "Go Live" no canto inferior direito.

## Deploy

### GitHub Pages (Recomendado)

1. Suba o codigo para o GitHub:
```bash
git add .
git commit -m "feat: versao inicial do portfolio"
git push origin master
```

2. No GitHub, va em **Settings** > **Pages**

3. Em "Source", selecione:
   - Branch: `master`
   - Folder: `/ (root)`

4. Clique em **Save**

5. O site estara disponivel em: `https://A-DAVI.github.io/Portfolio-dev/`

### Vercel (Alternativa)

1. Acesse [vercel.com](https://vercel.com)
2. Conecte sua conta GitHub
3. Importe o repositorio
4. Clique em **Deploy**

### Netlify (Alternativa)

1. Acesse [netlify.com](https://netlify.com)
2. Arraste a pasta do projeto para o dashboard
3. Ou conecte via GitHub para deploys automaticos

## Personalizacao

### Trocar foto/avatar
Substitua o placeholder em `assets/images/` e atualize o caminho no `index.html`.

### Adicionar novos projetos
Adicione um novo bloco `<div class="project-card">` na secao de projetos seguindo o padrao existente.

### Alterar cores
Edite as variaveis CSS em `css/style.css`:
```css
:root {
    --primary-dark: #0f1419;
    --accent-blue: #7a9bb8;
    /* ... */
}
```

## Contato

- **Email:** cassolidavi603@gmail.com
- **LinkedIn:** [/davi-cassoli-lira](https://linkedin.com/in/davi-cassoli-lira)
- **GitHub:** [/A-DAVI](https://github.com/A-DAVI)

---

Desenvolvido por Davi Cassoli - 2026
