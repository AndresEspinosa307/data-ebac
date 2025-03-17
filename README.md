# data-ebac
Projeto Ebac Github

O qué é?

Este é um projeto feito para demonstrar algumas funções do Git, a modo de exemplificar.

Tópicos
Adicionar e salvar;
Visualizar e reverter;
Persistir e atualizar.

1.2. Adicionar
O comando git add (doc) move arquivos da working para staging área. Se um arquivo for alterado/removido após ter sido adicionado, este deve ser adicionado novamente. Os usos mais comuns do comando são:

git add <nome-do-arquivo-1> <nome-do-arquivo-2> ...

git add <nome-do-dir>

1.3. Salvar
O comando git commit (doc) move arquivos da staging para repository área. A todo commit é atribuido uma chave identificadora única para rastreamento (hash). Ações nos arquivos "comitados" são salvas no repositório local dentro do diretório .git. O uso mais comum do comando é:

git commit -m "<mensagem-descrevendo-as-alterações>"

Visualizar e reverter
2.1. Visualizar
O comando git log (doc) lista os últimos commits (id, data, autor, mensagem, etc.) em ordem cronológica. Os usos mais comuns do comando são:

git log

git log <nome-do-arquivo>

2.2. Reverter
O comando git reset (doc) move arquivos da staging de volta para a working área, essencialmente desfazendo o comando git add. Os usos mais comuns do comando são:

git reset

git reset <nome-do-arquivo>

3. Persistir e atualizar
3.1. Persistir
O comando git push (doc) move arquivos da repository para remote área, salvando assim as alterações "comitadas" localmente no servidor git remoto, como o GitHub. O uso mais comum do comando é:

git push origin <nome-da-branch-remota>

3.2. Atualizar
O comando git pull (doc) faz o movimento contrátio do git push, movendo arquivos da remote para repository área, atualizando assim o projeto localmente. O uso mais comum do comando é:

git pull

