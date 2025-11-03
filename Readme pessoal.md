# 🛠️ Comandos Git úteis
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/Samyr-Dev/GitTutorial/blob/master/LICENSE)

# 💻 Trabalhando em outra máquina

```bash
git config --global user.email "usuario@gmail.com"

git config --global user.name "nome ou apelido
```
# 🚀 Inicializando um repositório
```bash
git status

git init

git add ./nome_arquivo

git commit -m "first commit"

git branch -M main

git remote add origin <url-do-repositório>

git remote -v

git push -u origin main
```
## ⚠️ Se o push gerar conflitos devido a históricos diferentes, utilize o comando abaixo para mesclar as versões:

```bash
git pull origin main --allow-unrelated-histories
```

# 🌿 Trabalhando com Branches
## Criar e mesclar uma nova branch:

### Cria e muda para a nova branch

```bash
git checkout -b "nome-da-branch"
```

### Volta para a branch principal
```bash
git checkout main 
```

### Mescla as alterações da nova branch na main
```bash
git merge nome-da-branch          
```

# 🔄 Fluxo de Trabalho e Comandos Diários

## 1. Dicas Rápidas (Baseado no Fluxo)

| Ação | Comando | Descrição |
| :--- | :--- | :--- |
| **Baixar Projeto** | `git clone <url-do-repositório>` | Baixa o projeto pro seu PC. |
| **Criar Branch** | `git checkout -B feat/login-ui` | Cria sua branch de tarefa e muda para ela. |
| **Commit (Com Sentido)** | `git commit -m "feat: tela de login"` | Salva a versão com uma mensagem clara. |
| **Atualizar Branch** | `git pull --rebase origin main` | Atualiza sua branch local sem bagunçar o histórico. |
| **Subir Branch** | `git push -u origin feat/login-ui` | Sobe sua branch (cria no GitHub, se não existir). |

## 2. Sincronizando o Repositório Local

### Sincroniza seu repositório local com as mudanças do repositório remoto (GitHub)
```bash
git pull
```

### 📬 Pull Request (PR)

### Um Pull Request é uma solicitação de alteração enviada para o repositório original a partir de um repositório que foi forkeado (copiado). Ele é utilizado para propor mudanças e colaborar com projetos públicos ou de outras pessoas.


### 🗺️ Mapa do Fluxo do PR
* **Fluxo:** `branch` → `add` → `commit` → `pull` → `push`
* **Próximo Passo:** Abrir o PR e responder ao *review*.

### ⚠️ CUIDADO: Dicas Essenciais
* Nada de `main` (trabalhe sempre em branches de desenvolvimento).
* Nada de `.env` (arquivos de variáveis de ambiente, como senhas, não devem ser versionados).
* **Atualize antes do PR** (`git pull` ou `git pull --rebase`).

## 💡 Git hacks

![WhatsApp-Video-2025-10-30-at-23 26 55](https://github.com/user-attachments/assets/127bdcd7-8ec4-4adc-ad2b-418ccc1ffd2c)



