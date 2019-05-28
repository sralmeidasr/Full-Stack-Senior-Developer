# Lista de comandos mais usados no git

1. [git status] => faz a leitura dos arquivos que não estão sendo monitorados pelo git. 
2. [git add 'nome arquido'] => adicionar arquivo por arquivo para o monitoramento do git.
3. [git add -A] => para adicionar todos os arquivos que não estão sendo monitorados.
4. [git commit -m "commit"] => para fazer um commit
5. [git log] => para saber quantos commits foram feitos naquela branch.
6. [git branch] => lista todas as branchs que tem no projeto e mostra com o '*' em qual branch você está.
7. [git commit -am "commit"] => para adicionar todos os arquivos ao monitoramento e fazer o um commit ao mesmo tempo.
8. [git reset --hard 'id'] => serve para apagar tadas as mudanças feitas no id do commit informado, caso seja preciso reverter tudo o que já foi feito no projeto.  
9. [git reset --soft 'id'] => volta para o commit informado mas não apaga os arquivos criados.
10. [git branch nome] => para criar uma nova branch, sendo que, essa nova branch pega o projeto como está e começa um novo histórico dali em diante.
11. [git checkout 'nome branch'] => para sair de uma branch e entrar em outra.
12. [git diff] => para mostrar todas as alterações feitas nos arquivos antes de fazer o commit, ou seja, aqui ele detalha exatamente o que foi feito.
13. [git diff --name-only] => para mostrar só os nomes dos arquivos que foram modificados.
14. [git diff 'nome arquivo'] => vai detalhar as mudanças feitas apenas no arquivo informado.
15. [git checkout HEAD --'nome do arquivo'] => se foram feitas várias mudanças, mas você quer voltar um único arquivo como era antes, ou seja, fez varias mudanças mas se arrependeu das alterações feitas em um único arquivo.
16. [git remote add 'nome do repositório' link] => para enviar o repositório local para o remoto.
17. [git remote] => mostra o repositório adicionado ao remoto.
18. [git remote -v] => mostra mais detalhes do repositório adicionado ao remoto.
19. [git push -u origin master] => comando para enviar o repositório local para o remoto, 'origin' foi o nome que eu deu para o repositório local e o 'master' representa a branch que eu quero enviar para o repositório remoto.
20. [git revert --no-edit] => comando para reverter sem perder todo o código e mantem o commit.
21. [git push origin :nomeBranche] => deletando branches remotos.
22. [git push origin -D nomeBranche] => deletando branches locais.
23. [git pull origin master] => puxando alterações do repositório remoto (pull).
24. [git clone link] => clonando repositórios remotos.

# Funcionalidades mais usadas no git
1 - [.gitignore] => ignorando arquivos do repositório local e remoto(gitignore). Criar um arquivo com o nome '.gitignore' e salva o nome do arquivo que se deseja omitir dentro do arquivo '.gitignore', sendo possível omitir até mesmo pastas completas.
2 - [*.js] => para omitir todos os arquivos, que por exemplo, tenham a extenção JS no final.
3 - [nomepasta/*] => para omitir todos os arquivos da pasta, ou a própria pasta com 'nomepasta/'.
4 - [fork/pull request] => contribuindo com outros repositórios, sendo 'fork' para copiar o repositório desejado para o seu repositório remoto, ao final  depois de realizadas todas as alterações, o 'pull request' enviar as alterações feitas para o dono do projeto original avaliar e aceitar.