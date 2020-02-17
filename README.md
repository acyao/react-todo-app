### The published To-do App:<br />
https://acyao.github.io/react-todo-app/

### How to deploy React to Github:
1. npm install gh-pages --save-dev

2. Go to package.json:<br />
"homepage": "http://{username}.github.io/{repo-name}"<br />

"scripts": {<br />
  //...<br />
  "predeploy": "npm run build",<br />
  "deploy": "gh-pages -d build"<br />
  }<br />

3. git remote add origin https://github.com/{username}/{repo-name}

4. git remote set-url origin https://github.com/{username}/{repo-name}

5. npm run build

6. npm run deploy

7. push your commit to GitHub: <br />
-git add . <br />
-git commit -m "Your awesome message" <br />
-git push origin master <br />
