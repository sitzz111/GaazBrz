# Fuel Prices MVP

App React + Vite + Tailwind para comparar preços de combustível por região.
- Filtra por raio, tipo de combustível e ordena por preço/distância/atualização.
- Mock de dados + reports salvos localmente (localStorage).
- Perfeito para deploy estático (Vercel/Netlify/GitHub Pages).

## Rodar localmente
```
npm i
npm run dev
```

## Build
```
npm run build
npm run preview
```

## Deploy (Vercel - simples)
1. Faça fork/commit deste projeto em um repositório seu.
2. No Vercel, clique em **New Project** → **Import Git Repository** → selecione o repo.
3. Use **Build Command**: `npm run build` e **Output Directory**: `dist`.
4. Deploy e pronto: você terá uma URL pública.
