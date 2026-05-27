git clone https://github.com/YOUR_USERNAME/project-gbp.git
cd project-gbp
mkdir frontend backend database docs
mkdir frontend/public frontend/src frontend/src/styles
touch frontend/package.json frontend/public/index.html frontend/src/App.jsx frontend/src/index.jsx
touch backend/package.json backend/server.js backend/.env.example
touch database/schema.sql
touch vercel.json render.yaml .gitignore
git add .
git commit -m "Initial commit"
git push -u origin main
