# Site

Este site possui duas releases, ou branches, cada uma com uma alteração diferente. A branch master reflete a release número dois.

## Objetivo

O objetivo é criar o deploy - com aplicação, serviço, rota - da versão **release-1** com duas réplicas e mais tarde uma segunda versão *somente com a aplicação e rota* da **release-2** também com duas réplicas.

Feito isso, a rota deve ser alterada para apontar para a **release-2**, criando uma transição **Blue/Green**.

## Versão 1 e Versão 2

As diferenças da versão 1 e versão 2 é apenas a frase da página inicial.
