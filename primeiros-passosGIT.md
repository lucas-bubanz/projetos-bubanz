# 📘 Documentação de Comandos do Git

---

## 🛠️ Comandos Básicos
- **`git init`**: Inicializa um novo repositório Git no diretório atual.
- **`git clone <url>`**: Clona um repositório remoto para o diretório local.
- **`git status`**: Exibe o status atual do repositório, incluindo arquivos modificados e não rastreados.
- **`git add <arquivo>`**: Adiciona um arquivo específico à área de stage (preparação para commit).
- **`git add .`**: Adiciona todos os arquivos modificados à área de stage.
- **`git commit -m "<mensagem>"`**: Cria um commit com as alterações na área de stage e uma mensagem descritiva.
- **`git log`**: Exibe o histórico de commits do repositório.

---

## 🌿 Trabalhando com Branches
- **`git branch`**: Lista todas as branches no repositório.
- **`git branch <nome>`**: Cria uma nova branch com o nome especificado.
- **`git checkout <branch>`**: Alterna para a branch especificada.
- **`git checkout -b <branch>`**: Cria e alterna para uma nova branch.
- **`git merge <branch>`**: Mescla a branch especificada na branch atual.

---

## 🌐 Repositórios Remotos
- **`git remote add origin <url>`**: Adiciona um repositório remoto com o nome "origin".
- **`git push -u origin <branch>`**: Envia as alterações da branch especificada para o repositório remoto.
- **`git pull`**: Puxa as alterações do repositório remoto para o local.

---

## 🔧 Outros Comandos Úteis
- **`git diff`**: Mostra as diferenças entre os arquivos modificados e o último commit.
- **`git reset <arquivo>`**: Remove um arquivo da área de stage.
- **`git stash`**: Salva temporariamente as alterações não commitadas para limpar o diretório de trabalho.
- **`git stash pop`**: Restaura as alterações salvas com `git stash`.
- **`git tag <nome>`**: Cria uma tag no commit atual.