```
git clone https://github.com/craigmckeachie/microbloglite
cd microbloglite/microbloglite-backend
npm install
cp .env.example .env
cd ../..
rm -rf .git
git config --global init.defaultBranch main
git init
git add .
git commit -m "initial commit"
git push origin main
code . #if this doesn't work just open the microbloglite folder in vscode
```


