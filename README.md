# Atividade GIT UC11

### Git Clone:

* Comando utilizado para baixar uma cópia do repositório remoto para o repositório local (a máquina do usuário).\
*Ex - git clone git@github.com:nome_usuario/nome_repositorio.git*

### Git Branch:

* Comando para mexer nas branches, ramificações de um repositório, onde as branches podem ser criadas, modificadas, deletadas, etc.\
*Ex: git branch nova_branch*

### Git Push:

* Comando usado para enviar as mudanças feitas no repositório local para alguma branch no repositório remoto, vale ressaltar que para realizar o push devem ser adicionados os arquivos desejados e feito o commit deles.\
*Ex: git push*

### Git Checkout:

* Comando utilizado principalmente para alternar entre branches e commits.\
*Ex: git checkout nome_branch*\
*Ex: git checkout hash_commit*

### Git Status:

* Comando para verificar o status de um repositório local, se algum arquivo foi alterado, deletado, criado, etc. Também se existem arquivos pendentes para ser feito o commit.\
*Ex: git status*

### Git Add:

* Comando que adiciona arquivos modificados de alguma forma para a área de staging, funcionando como um buffer entre o repositório local e o histórico do projeto. Nele ficam armazenados os arquivos/diretórios que estão para ser commitados.\
*Ex: git add nome_arquivo*\
*Ex: git add nome_diretório*\
*Ex: git add .* - (adiciona todos os arquivos e pastas que foram modificadas)

### Git Commit:

* Pode ser traduzido como "enviar"/"entregar", esse comando é utilizado para pegar os arquivos na área de staging (adicionados pelo comando *add*) e prepará-lo para enviar para o repositório remoto, criando snapshots, estado de um sistema em um determinado ponto no tempo. É extremamente importante para o controle de versionamento do sistema.\
*Ex: git commit -m "mensagem_desejada"*

### Git Pull:

* Comando que baixa o conteúdo diferente entre o repositório remoto e o local, seus commits diferentes e faz o merge, a mescla, entre os arquivos caso precise.\
*Ex: git pull repositório_remoto*

### Git Revert:

* Comando mais seguro para desfazer mudanças, como commits e add. Nele, vai ser criado um novo commit revertendo essas mudanças, podendo manter outros commits que não precisam ser desfeitos.\
*Ex: git revert commit_desejado*

### Git Merge

* Comando utilizado para unificar/mesclar um branch que foi bifurcado, fazendo com que essas ramificações se tornem um único "caminho". Caso apareça conflitos de arquivos com a mesma linha sendo alterada em branches diferentes precisa ser decidido qual irá prevalecer para o merge.\
*Ex: git merge branch_alternativo*
