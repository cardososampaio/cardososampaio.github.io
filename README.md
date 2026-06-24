# Rafael Cardoso Sampaio - site acadêmico

Site acadêmico pessoal em Astro estático, preparado para publicação via GitHub Pages.

## Desenvolvimento local

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

O resultado fica em `dist/`.

## GitHub Pages

O workflow em `.github/workflows/deploy.yml` publica a branch `main` no GitHub Pages usando Actions. Para repositório de projeto, o workflow define `BASE_PATH` automaticamente com o nome do repositório.

Se o repositório for `usuario.github.io`, remova a variável `BASE_PATH` do passo `Build` para publicar na raiz do domínio.
