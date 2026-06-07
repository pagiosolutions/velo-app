# Velo — Landing Page

Template de landing page dark, em português, inspirado no Appie React.

## Estrutura

```
velo/
├── index.html     # Página completa (HTML + CSS + JS inline)
├── vercel.json    # Configuração de deploy
└── README.md
```

## Deploy na Vercel

### Opção 1 — Vercel CLI (recomendado)

```bash
# Instale a CLI da Vercel (se não tiver)
npm i -g vercel

# Entre na pasta do projeto
cd velo

# Faça o deploy
vercel

# Para produção
vercel --prod
```

### Opção 2 — Deploy via GitHub

1. Crie um repositório no GitHub e faça push dos arquivos
2. Acesse [vercel.com](https://vercel.com) → **New Project**
3. Importe o repositório
4. Clique em **Deploy** — a Vercel detecta o `vercel.json` automaticamente

### Opção 3 — Drag & Drop

1. Acesse [vercel.com/new](https://vercel.com/new)
2. Arraste a pasta `velo/` direto para o site
3. Deploy pronto em segundos

## Customização rápida

Todas as variáveis de cor ficam no topo do `<style>` em `:root`:

```css
--v:   #00E5FF;   /* cor principal (cyan) */
--v2:  #0070F3;   /* azul elétrico */
--v3:  #7928CA;   /* roxo */
```

Para trocar o nome da marca, busque por `VELO` e `VEL<em>O</em>` no HTML.
