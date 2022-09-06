fluxo de trabalho do git:

Diretorio de trabalho -> são os arquivos reais
Indice -> desempenha um papel de area de testes
Head -> um tipo de ponteiro para o ultimo commit

Comandos:

git init -> iniciar um novo repositorio

git clone <repositorio> -> clona um repositorio remoto

git add <nome_do_arquivo> -> alterações ou adição de arquivos são apontados ao Indice

git commit -m "Qualquer mensagem sobre o commit aqui" -> faz a mudança no Head

git remote add origin <servidor> -> estabelece uma ligação nova entre seu repositorio e o servidor remoto

git checkout -b <nome_da_branch> -> cria uma nova branch

git checkout <nome_da_branch> -> vai para a branch especificada

git branch -d <nome_da_branch> ->  deleta a branch especificada
