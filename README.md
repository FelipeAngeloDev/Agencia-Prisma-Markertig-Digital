# Prisma Marketing — site institucional

React + TypeScript + Tailwind CSS (Vite).

## Rodar localmente
    npm install
    npm run dev

## O que editar
Tudo em `src/config/site.ts`: WhatsApp, Instagram, e-mail, dados da agência, serviços, portfólio e FAQ.
Textos de cada seção: `src/components/`. Cores e estilos: variáveis no topo de `src/index.css`.

## Publicar na Vercel
1. Suba esta pasta para um repositório no GitHub.
2. Em vercel.com, clique em Add New → Project e importe o repositório.
3. Mantenha as configurações detectadas (Vite, `npm run build`, saída `dist`) e clique em Deploy.
Alternativa: `npx vercel` dentro da pasta.
