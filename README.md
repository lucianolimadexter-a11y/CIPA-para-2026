# Segurança em Foco — CIPA 2026

App de segurança do trabalho (AST, checagem, relatos, registro de PARE e quiz). Funciona offline e pode ser instalado no celular.

## Publicar no GitHub Pages
1. Crie um repositório no GitHub (ex.: `seguranca-em-foco`).
2. Envie **todos** os arquivos desta pasta para a raiz do repositório (Add file → Upload files).
3. Vá em **Settings → Pages**. Em *Source* escolha **Deploy from a branch**, branch **main**, pasta **/ (root)** e salve.
4. Após ~1 minuto o link aparece: `https://SEU-USUARIO.github.io/seguranca-em-foco/`.

## Instalar no celular
- **Android (Chrome):** menu ⋮ → *Instalar app* / *Adicionar à tela inicial*.
- **iPhone (Safari):** Compartilhar → *Adicionar à Tela de Início*.

## Observações
- Os dados (nome, ID, foto, registros) ficam **somente no aparelho** (localStorage). Nada é enviado a servidor.
- Ao publicar uma nova versão, altere `V` em `sw.js` (ex.: `segfoco-v23`) para forçar a atualização do cache.
- `cover.png` é a imagem de capa (prévia de link) e `` contém os ícones do app.
