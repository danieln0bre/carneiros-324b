# Guia do Hóspede — Max Carneiros Suítes 324 B

Página estática (HTML puro, sem build) com o guia do hóspede do apartamento.

## Estrutura

```
guia-hospede/
├── index.html        # a página em si
├── fotos/             # imagens usadas na página
│   ├── sala-cozinha.jpg
│   ├── entrada-cozinha.jpg
│   └── sofa-cama.jpg
└── README.md
```

## Como publicar no GitHub Pages

1. Crie um repositório novo no GitHub (ex.: `guia-hospede`).
2. Suba todo o conteúdo desta pasta para a raiz do repositório (mantendo `index.html` na raiz, não dentro de uma subpasta).
3. No repositório, vá em **Settings → Pages**.
4. Em "Source", selecione a branch `main` (ou `master`) e a pasta `/ (root)`.
5. Salve. Em alguns minutos o GitHub mostra o link público, algo como:
   `https://SEU-USUARIO.github.io/guia-hospede/`

## Como editar depois

Basta abrir o `index.html` em qualquer editor de texto. Os textos ficam direto no HTML — não há nenhum sistema de build ou dependência para instalar.

Para trocar uma foto, coloque o novo arquivo em `fotos/` e ajuste o `src` da tag `<img>` correspondente em `index.html`.

## Alternativa: Vercel

O mesmo repositório também pode ser importado direto no [vercel.com](https://vercel.com) ("Add New → Project"), sem nenhuma configuração adicional — é uma página estática.
