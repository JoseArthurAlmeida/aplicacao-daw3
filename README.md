# Aplicação inicial DAW 3

Este é um projeto desenvolvido com **Next.js** e **React**, com o objetivo de aprender e praticar as tecnologias (estilo um Hello World). O sistema utiliza **Material-UI (MUI)** para componentes de interface.

## Tecnologias Utilizadas

O projeto foi construído utilizando as tecnologias mais recentes do ecossistema React:

- **Framework:** [Next.js 16.1.6](https://nextjs.org/) (App Router)
- **Biblioteca:** [React 19.2.3](https://react.dev/)
- **Estilização:** [Tailwind CSS v4](https://tailwindcss.com/) & [Material-UI (MUI)](https://mui.com/)
- **Fontes:** [Geist](https://vercel.com/font) (Otimizada via `next/font`)

## Estrutura e Páginas

O aplicativo conta com as seguintes rotas principais:

| Rota | Descrição |
| :--- | :--- |
| **`/` (Home)** | **Página Principal:** Exibe a listagem de produtos e conta com uma barra de pesquisa integrada. |
| **`/admin`** | **Painel Administrativo:** Área para gerenciamento do sistema. |

### Componentes Chave
- **`TopBar`**: Barra de navegação superior global, contendo a funcionalidade de busca e compartilhada entre todas as páginas.

### Estrutura de Pastas

```text
├── app/
│   ├── admin/      # Rota da página de administração
│   ├── components/ # Componentes reutilizáveis (TopBar, etc)
│   ├── layout.js   # Layout global
│   └── page.js     # Página principal (Home)
├── public/         # Ativos estáticos
└── ...
```

## Como Rodar o Projeto

Siga os passos abaixo para executar o projeto localmente:

### 1. Instalar dependências

```bash
npm install
# ou
yarn install
# ou
pnpm install
# ou
bun install
```

### 2. Rodar o servidor de desenvolvimento

```bash
npm run dev
# ou
yarn dev
# ou
pnpm dev
# ou
bun dev
```

Abra http://localhost:3000 no seu navegador para ver o resultado.