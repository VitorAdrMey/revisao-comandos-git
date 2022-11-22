# Branchs

São ramificações do projeto, o qual permite vários desenvolvedores, trabalharem em diferentes funcionares, em bugar a versão estável.





## Principais branchs



Branchs main -> que é a branchs principal, ou seja, a branch estável da aplicação. versão que é disponibilizada aos clientes.



Branch developer -> é branch utilizada pelo testers. os quis vão testar as novas funcionalidades, correções de bugs, etc.



## Outras branchs

Para cada nova funcionalidade ou correções de bugs é criada uma nova branch



Para correção de bugs : fix_identificacao_do_bug

Exemplo : fix_integração_da_nova_funcionalidade



para novas funcionalidades:

feat_identificacao_da_nova_funcionalidade

exemplo : feat_integracao_com_google, feat_nova_tela_de_contato



Para atualizar documentação : doc_identificação_da_alteracao

Exemplo : doc_adicionada_nova_imagem



Para criação/alteração de tarefas que não interfere no código:

chore_identificacao_da_modificacao

Exemplo : chore_atualizada_a_versao_do_banco



## Criação de novas branchs

git checkout -b nome_da_nova_branch

Exempo : git checkout -b fix_botao_da_tela_login

Obs : o ideal é sempre criar as branchd a partir da main.



## Listar as branchs existentes

git Branch list



### Trocar de brachs

git switch nome_da_branchs_que_deseja_entrar

Exemplo 01 : git switch fix_botao_da_tela_login

Exemplo 02 : git switch main



### Excluir uma branch

git branch -D nome_da_branch_que_deseja_excluir

Exemplo : git branch -D fix_botao_tela_login