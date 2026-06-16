# FinOS — Gestão Financeira Pessoal

Sistema financeiro pessoal com Supabase + Vercel.

## Deploy no Vercel

### Opção 1 — Via GitHub (recomendado)

1. Crie um repositório no GitHub (ex: `finos`)
2. Faça upload dos dois arquivos: `index.html` e `vercel.json`
3. Acesse [vercel.com](https://vercel.com) → **Add New Project**
4. Importe o repositório do GitHub
5. Clique em **Deploy** — pronto!

### Opção 2 — Via Vercel CLI

```bash
npm i -g vercel
cd finos/
vercel --prod
```

## Estrutura

```
finos/
├── index.html    # App completo (HTML + CSS + JS)
└── vercel.json   # Config de deploy
```

## Banco de dados

- **Supabase project:** trzqoctkqjtdrioazkhu
- **Tabelas:** `entradas` e `despesas`
- Dados separados por mês e ano
