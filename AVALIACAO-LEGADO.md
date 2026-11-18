# Controle Financeiro PHP — avaliação do legado

Este repositório é uma aplicação PHP com arquitetura MVC, rotas, modelos, views, Composer e código de terceiros em vendor/. O projeto WS atual está em controle-financeirows e utiliza Node.js/Express/PostgreSQL, portanto **não são repositórios idênticos**.

## Recomendação
- Preservar o legado como referência; não migrar nem excluir sem verificar dados e dependências.
- Não publicar código PHP antigo antes de revisar autenticação, autorização, segredos, validação e consultas.
- Não substituir o backend do WS Controle Financeiro que já existe.
- Aproveitar apenas recursos distintos e comprovadamente úteis, após comparar as telas e modelos.

## Checklist
1. Mapear funções da aplicação PHP e comparar com o WS.
2. Identificar possíveis credenciais e dados privados no código e histórico.
3. Revisar upload, SQL, sessões e tratamento de senhas.
4. Preparar relatório de diferenças antes de propor alterações no WS.

Esta documentação não indica que os sistemas foram executados ou testados.