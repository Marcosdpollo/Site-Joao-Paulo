# JP Personal — Site

Site institucional de João Paulo, Personal Trainer (CREF 200087-G/SP).

## Como publicar

Este é um site estático de **um arquivo só** (`index.html`, com as imagens já embutidas nele). Não precisa de servidor, build ou instalação — é só hospedar.

### Publicar com GitHub Pages (grátis)

1. Crie um repositório novo no GitHub (pode ser público).
2. Faça upload do arquivo `index.html` para a raiz do repositório.
3. Vá em **Settings → Pages**.
4. Em "Branch", selecione `main` (ou `master`) e pasta `/root`, depois **Save**.
5. Aguarde 1–2 minutos. O site ficará disponível em:
   `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`

### Publicar com domínio próprio

Depois de ativar o GitHub Pages, em **Settings → Pages → Custom domain**, digite o domínio (ex: `jppersonal.com.br`) e siga as instruções de DNS do GitHub.

## Estrutura

- `index.html` — site completo (HTML + CSS + JS + imagens em base64, sem dependências externas além das fontes do Google Fonts).
