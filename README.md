Project: Static site for DevOps assignment.

How to run locally:
1. docker build -t <dockerhub-user>/static-site:v1 .
2. docker run -d -p 8080:80 <dockerhub-user>/static-site:v1
3. Open http://localhost:8080

Git commands used:
git init
git add .
git commit -m "Initial commit"
git branch feature-demo
git switch feature-demo
git switch main
git remote add origin https://github.com/<user>/<repo>.git
git push -u origin main
