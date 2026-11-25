# Melhores do Ano — inscrições

Front-end do evento, publicado pelo GitHub Pages a partir da branch `main` e da pasta raiz (`/`). Alterações em `index.html` são publicadas após cada commit na `main`.

## Arquitetura

- `index.html`: interface original do evento, com chave PIX e WhatsApp configurados.
- API de inscrições: `https://gala-melhores-do-ano-2026-inscricoes.traco0061.chatgpt.site/api/inscricoes`.
- Banco online: Cloudflare D1 do Site, tabela `inscricoes`.

O GitHub Pages hospeda arquivos estáticos. O endpoint externo é necessário para gravar os cadastros. O comprovante é enviado pelo visitante no WhatsApp e a confirmação do pagamento é manual.

## Publicação inicial

Em **Settings → Pages**, escolha **Deploy from a branch**, branch **main**, pasta **/** (root), e salve. Depois disso, novos commits na `main` publicam o front automaticamente.
