# Fluxo de desenvolvimento em 10 fases

Cada fase termina com o relatório padrão (realizado, arquivos, testes reais, problemas, custos, próxima ação). Nunca marque uma fase como concluída sem evidência.

| Fase | Nome | Saída verificável |
|---|---|---|
| 1 | Entendimento do problema | Resumo confirmado pelo usuário |
| 2 | Especificação técnica | Arquivos em docs/ cobrindo os 20 itens |
| 3 | Revisão e aprovação do plano | Aprovação escrita do usuário |
| 4 | Repositório e dependências | Projeto cria, instala e roda "olá mundo"; .gitignore bloqueia .env; lint e formatação configurados |
| 5 | Implementação do MVP | Fluxos principais funcionando conforme critérios do item 20 |
| 6 | Banco de dados e APIs | Migrações aplicadas em ambiente de desenvolvimento (nunca produção sem autorização); RLS testada com usuários diferentes |
| 7 | Testes e revisão de segurança | Testes executados; checklist: segredos, validação de entrada, autorização, dependências (npm audit), CORS, limites de taxa |
| 8 | Correção dos problemas | Falhas da fase 7 resolvidas e testes repetidos |
| 9 | Build e implantação | Build real concluído; URL ou artefato verificado; plano de rollback |
| 10 | Documentação e manutenção | README, guia de execução, variáveis de ambiente (sem valores), rotina de atualização e backup |

## Salvaguardas

- Commits pequenos e descritivos, em branch de trabalho. Não envie para a branch principal sem pedido do usuário.
- Pare e peça autorização antes de: gastar dinheiro, criar contas, alterar banco de produção, apagar dados, publicar nas lojas, enviar e-mails reais.
- Distinga sempre protótipo de demonstração de aplicação pronta para produção e diga qual dos dois foi entregue.
- Indique quando algo exigir computador, dispositivo físico, emulador ou conta externa.
