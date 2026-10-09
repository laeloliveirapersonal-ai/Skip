========================================================================
XADREZ ATIVAMENTE - PLATAFORMA DE JOGOS COGNITIVOS E EDUCACIONAIS
========================================================================

Este arquivo contém o código-fonte completo da plataforma Xadrez Ativamente
(React 19 + TypeScript + Vite + Tailwind CSS + Radix UI / Shadcn).

------------------------------------------------------------------------
COMO EXECUTAR LOCALMENTE
------------------------------------------------------------------------

1. Pré-requisitos:
   - Node.js versão 18 ou superior (recomendado Node 20 LTS)
   - npm versão 9 ou superior (ou pnpm / yarn)

2. Instalação das dependências:
   npm install

3. Iniciar o servidor de desenvolvimento:
   npm run dev
   ou
   npm start

   Acesse no navegador: http://localhost:5173

4. Gerar build de produção:
   npm run build

5. Pré-visualizar o build localmente:
   npm run preview

------------------------------------------------------------------------
ESTRUTURA DE PASTAS E ARQUIVOS
------------------------------------------------------------------------

- src/
  - components/       Componentes da UI, layout (Navbar, Footer, badges)
  - components/games/ Jogos interativos (Xadrez, Damas, Termo, Trava-Letras,
                      Genius Square, Fábrica de Palavras, Labirinto, etc.)
  - components/ui/    Biblioteca Shadcn UI (Radix UI acessíveis)
  - contexts/         Contexto de autenticação (AuthContext)
  - hooks/            Custom hooks (som, responsividade, realtime)
  - lib/              PocketBase client, utilitários de áudio, offlineSync
  - pages/            Páginas da plataforma (Início, Catálogo, Jogar,
                      Progresso, Minhas Crianças, Perfil, Login, Sobre)
  - types/            Tipagens TypeScript e schemas

- public/             Ícones PWA, manifest, service worker e assets estáticos
- pocketbase/         Migrações de banco SQLite e hooks backend
- scripts/            Scripts de automação (build do ZIP, testes)
- vite.config.ts      Configurações do Vite e bundler
- tailwind.config.ts  Configurações de cores, fontes e design system

------------------------------------------------------------------------
DESENVOLVIDO COM DEDICAÇÃO PARA ESTIMULAR O DESENVOLVIMENTO COGNITIVO
========================================================================
