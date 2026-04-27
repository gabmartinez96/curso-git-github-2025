# Curso TMW Git & GitHub 2025

Esse é um curso para iniciantes aprenderem com versionamento de código
e repositórios remotos com GitHub

Além disso, vamos trabalhar com GitFlow ao final do curso e Visual Studio Code.

Conteúdo gratúito e de qualidade, disponível no YouTube!

A seguir vamos ver alguns fluxos de trabalho para git e github

## Fluxo de trabalho Git Local

1. git checkout -b <nova_branche>
2. Cria ou atualiza arquivos
3. git status
4. git add .
5. git status
6. git commit -m "mensagem"
7. git checkout main
8. git merge nova_branche

## Fluxo de trabalho GitHub <> Local (projeto próprio ou da empresa)

1. git clone <endereço do projeto>
2. git checkout -b <nova_branche>
3. criar ou atualizar arquivos
4. git status
5. git add .
6. git status
7. git commit -m "mensagem"
8. git status
9. git push origin <nova_branche>
10. abrir Pull request no GitHub para a main
11. excluir <nova_branche> origin
12. git checkout main
13. git branch -D <nova_branche>

## Fluxo de trabalho GitHub <> Local (projetos open source)

1. Fork do projeto para o seu proprio github
2. git clone <endereço do projeto fork>
3. git checkout -b <nova_branche>
4. criar ou alterar arquivos
5. git status
6. git add .
7. git status
8. git commit -m "mensagem"
9. git push origin <nova_branche>
10. Criar um Pull Request no GitHub
da branch fork para a main do projeto original
11. excluir <nova_branche>
12. git checkout main
13. git branch -D <nova_branche>
