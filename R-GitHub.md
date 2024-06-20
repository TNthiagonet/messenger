# GitHub Comandos

# Para subir atualizações

git status  # Verifica o status das mudanças no repositório local

git add .  # Adiciona todas as mudanças para o próximo commit

git commit -m "Subindo alterações do arquivo: "  # Faz o commit das mudanças com uma mensagem descritiva

git push  # Envia as alterações para o repositório remoto no GitHub

---------------------------------------

# Criou local e precisa enviar para o repositório no GitHub?

git init  # Inicializa um repositório Git local

git status  # Verifica o status das mudanças no repositório local

git add .  # Adiciona todas as mudanças para o próximo commit

git commit -m "Primeiro commit"  # Faz o primeiro commit das mudanças com uma mensagem descritiva

git config --global user.email "seu-email@exemplo.com"  # Configura o email do usuário Git globalmente

git config --global user.name "Seu Nome"  # Configura o nome do usuário Git globalmente

curl -u 'SEU_USUARIO' https://api.github.com/user/repos -d '{"name":"NOME_DO_REPOSITORIO"}'  # Cria um novo repositório no GitHub via API

git remote add origin URL_DO_REPOSITORIO_GITHUB.git  # Adiciona o repositório remoto do GitHub como origem do seu repositório local

git checkout -b main   # Cria a branch "main" localmente (certifique-se de que esta é a branch correta conforme configurado no GitHub)

git commit -m "Primeiro commit"   # Faz o primeiro commit das mudanças na branch "main" local

git push -u origin main   # Envia as mudanças da branch "main" para o repositório remoto no GitHub
