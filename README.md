# Melhores do Ano — inscrições

- [Inscrição pública](https://btgforbies.github.io/Inscri-o_Melhores_do_Ano/)
- [Painel administrativo](https://btgforbies.github.io/Inscri-o_Melhores_do_Ano/admin.html)

O GitHub Pages publica o front automaticamente após commits na branch `main`. O banco online fica na API do Site em `https://gala-melhores-do-ano-2026-inscricoes.traco0061.chatgpt.site`.

O painel usa senha de administração armazenada como segredo no servidor. A senha não deve ser colocada neste repositório. Ele mostra totais de inscritos, permite buscar, editar nome e WhatsApp, marcar o pagamento como pendente, pago ou não pago e excluir inscrições. A exclusão remove o registro definitivamente.

O comprovante é enviado pelo participante no WhatsApp. Marque como pago somente após conferir o pagamento.

O formulário valida um celular brasileiro com DDD e mostra uma mensagem quando ele já está inscrito. A regra definitiva depende do índice único no banco e do Worker em `gala-inscricoes`; um commit apenas neste repositório publica o front, mas não altera a API.
