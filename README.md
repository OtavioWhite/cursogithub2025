# Curso TMW GIT & GitHub 2025

Trablhando com Git e GitHub para iniciantes

anotações em cima de aprendizado em bloco de notas

✅ Para remover uma branch local:
bash
Copiar
Editar
git branch -d nome-da-branch
Usa -d (de delete) apenas se a branch já foi mesclada (merged).
Se ainda não foi mesclada e você quer forçar a exclusão:

bash
Copiar
Editar
git branch -D nome-da-branch
✅ Para remover uma branch remota:
bash
Copiar
Editar
git push origin --delete nome-da-branch