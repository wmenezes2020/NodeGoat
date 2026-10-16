# Verificacao do code-review autonomo

Este ficheiro existe para abrir uma PR de teste neste fork e confirmar, de
ponta a ponta, que a varredura periodica deteta uma PR aberta e que o
code-review publica o veredito nela.

Nada aqui altera o comportamento da aplicacao.

## O que esta a ser verificado

1. A varredura periodica lista as PRs abertas deste repositorio.
2. A PR entra no disparo (nao e saltada por ramo nem por marcador da plataforma).
3. A revisao corre sob a conta de quem abriu a PR.
4. O veredito e publicado como comentario na propria PR.

Criado em 2026-10-16.
