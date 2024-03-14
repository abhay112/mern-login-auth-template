npm init -y
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/abhay112/react-auth-app.git
git remote set-url origin https://github.com/abhay112/react-auth-app.git
git push -u origin HEAD:master
git push -u origin HEAD:master --force
git push -u origin main