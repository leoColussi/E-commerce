# Trabalho E-commerce

Aplicação front-end de e-commerce construída com React, Vite e Tailwind CSS.

## Resumo
- Projeto de loja online com páginas de `Home`, `Admin`, `Login` e `Register`.
- Componentes reutilizáveis na pasta `src/componentes/ui` e integração com API via `src/api`.

## Tecnologias
- **Frontend:** React + Vite
- **Estilos:** Tailwind CSS + PostCSS
- **Tooling:** Node.js, npm/yarn

## Scripts úteis
Execute os comandos no diretório do projeto.

- Instalar dependências: `npm install`
- Rodar em desenvolvimento: `npm run dev`
- Build para produção: `npm run build`
- Servir build localmente: `npm run preview`

(Os scripts estão definidos em [package.json](package.json).)

## Estrutura do projeto (resumo)
- `src/` — código fonte
  - `components/` — componentes React genéricos
  - `componentes/ui/` — biblioteca de componentes UI (botões, inputs, dialogs)
  - `pages/` — páginas da aplicação (`Home.jsx`, `Admin.jsx`, `Login.jsx`, `Register.jsx`)
  - `api/` — cliente HTTP e chamadas a endpoints
  - `lib/` — utilitários e helpers
- `index.html` — entrada HTML
- `package.json`, `vite.config.js`, `tailwind.config.js`, `postcss.config.js`

## Variáveis de ambiente
- Crie um arquivo `.env` para variáveis de configuração (ex.: `VITE_API_BASE_URL`).

## Executando localmente
1. `npm install`
2. `npm run dev`
3. Abra `http://localhost:5173` (ou a porta indicada pelo Vite)

## Como contribuir
- Abra uma branch com seu feature/fix e envie um Pull Request.
- Siga o padrão de componentes existentes em `src/componentes/ui`.

## Licença
Este repositório está licenciado sob a licença MIT.

---

Se quiser, eu atualizo o README com instruções de deploy, exemplos de `.env` ou badges CI.
