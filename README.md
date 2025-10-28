# 1. Entre na pasta onde está o index.html
cd /caminho/para/pasta-do-site

# 2. Inicialize o repositório local
git init

# 3. Adicione todos os arquivos
git add .

# 4. Faça o primeiro commit
git commit -m "Primeiro commit - site Studio Ark.Kon"

# 5. Crie o repositório no GitHub (se já existir, pule esta parte)
# - Vá no GitHub, clique em New repository e copie a URL do repositório (ex: git@github.com:usuario/studio-arkkon.git ou https://github.com/usuario/studio-arkkon.git)

# 6. Adicione o remote e envie (substitua pela URL do seu repo)
git remote add origin https://github.com/SEU_USUARIO/studio-arkkon.git
git branch -M main
git push -u origin main
