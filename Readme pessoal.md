# 🛠️ Comandos Git úteis
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/Samyr-Dev/GitTutorial/blob/master/LICENSE)

# 💻 Trabalhando em outra máquina

git config --global user.email "usuario@gmail.com"
git config --global user.name "nome ou apelido

# 🚀 Inicializando um repositório

git status

git init

git add ./nome_arquivo

git commit -m "first commit"

git branch -M main

git remote add origin <url-do-repositório>

git remote -v

git push -u origin main

## ⚠️ Se o push gerar conflitos devido a históricos diferentes, utilize o comando abaixo para mesclar as versões:

git pull origin main --allow-unrelated-histories

# 🌿 Trabalhando com Branches
Criar e mesclar uma nova branch:

git checkout -b "nome-da-branch"  # cria e muda para a nova branch

git checkout main                 # volta para a branch principal

git merge nome-da-branch          # mescla as alterações da nova branch na main


# 🔄 Atualizando seu repositório local

git pull
Esse comando sincroniza seu repositório local com as mudanças do repositório remoto (GitHub).

# 📬 Pull Request
Um Pull Request é uma solicitação de alteração enviada para o repositório original a partir de um repositório que foi forkeado (copiado). Ele é utilizado para propor mudanças e colaborar com projetos públicos ou de outras pessoas.
