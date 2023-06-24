npm init -y
touch index.js
touch Dockerfile
npm install express

Criar arquivo .dockerignore

Criar imagem:docker build -t valdyrtorres/dockernode .
docker build -t valdyrtorres/dockernode .

Rodar app:
docker run -p 3000:3000 -d valdyrtorres/dockernode

git init
git add .
git commit -m "primeiro commit - usando somente dockerfile sem docker-compose"
git branch -M main
git remote add origin https://github.com/valdyrtorres/docker-node.git
git push -u origin main