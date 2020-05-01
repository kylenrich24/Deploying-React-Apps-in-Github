# Deploying-React-Apps-in-Github

Add homepage to package.json

```
"homepage": "https://USERNAME.github.io/REPOSITORY_NAME"
```

Install gh-pages and add deploy to scripts in package.json

```
npm install --save gh-pages
```

```javascript
"predeploy": "npm run build",
"deploy": "gh-pages -d build"
```
