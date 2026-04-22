# Egus — Site (HTML único)

Site institucional da Egus em **um único arquivo HTML**, idêntico à visualização do preview, com todas as animações, fontes e imagens embutidas.

## Conteúdo

```
egus-site/
└── index.html   ← Tudo está aqui dentro (~10MB)
```

CSS, JavaScript, fontes (Cormorant Garamond + DM Sans) e todas as imagens/vídeos estão embutidos em base64. **Funciona 100% offline**, sem internet.

## Como abrir

Clique duas vezes no `index.html` — abre em qualquer navegador.

## Como publicar

### GitHub Pages
1. Suba `index.html` na raiz do repositório.
2. Em **Settings → Pages**, escolha branch `main` e pasta `/ (root)`.
3. Site fica em `https://seu-usuario.github.io/nome-do-repo/`.

### Netlify / Vercel (drag & drop)
- [app.netlify.com/drop](https://app.netlify.com/drop) — arraste o `index.html`.

### Hospedagem própria
Suba o `index.html` para a pasta `public_html` (ou equivalente).

## Editar

Abra em qualquer editor de texto (VS Code, Notepad++). Tudo está em um arquivo só, comentado por seções: Hero, Sobre, Audiovisual, Galeria, Prova Real, Feedbacks, CTA.

## Licença

Uso exclusivo da Egus.
