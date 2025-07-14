# Bootcamp_LogicadeProgramacao

✅ Git + GitHub - Comandos Essenciais (Resumo Rápido)

🔧 Configuração
git config --global user.name "Seu Nome"
git config --global user.email "seu@email.com"
git config --global init.defaultBranch main

📁 Repositório
git init                                 # Inicializa repositório
git clone URL                            # Clona repositório remoto

📝 Commits
git add .                                # Adiciona todas mudanças
git commit -m "mensagem"                 # Commit com mensagem
git commit --amend                       # Edita último commit

🌿 Branches
git branch                               # Lista branches
git branch nova-branch                   # Cria nova branch
git switch nome-da-branch                # Troca de branch
git merge nome-da-branch                 # Junta outra branch
git rebase nome-da-branch                # Reaplica commits

🌐 Repositório Remoto
git remote -v                            # Lista remotos
git push origin nome-da-branch           # Envia para GitHub
git pull origin nome-da-branch           # Puxa do GitHub
git fetch                                # Baixa sem aplicar

🧹 Limpeza
git stash                                # Guarda alterações
git stash pop                            # Recupera stash
git reset --hard HEAD                    # Desfaz tudo local
git clean -fd                            # Remove arquivos não rastreados

🔍 Histórico
git log                                  # Histórico completo
git log --oneline --graph                # Log visual resumido
git diff                                 # Mostra diferenças

📌 Outros
git tag -a v1.0 -m "versão 1.0"          # Cria uma tag
gh pr create                             # Cria Pull Request (via GitHub CLI)
