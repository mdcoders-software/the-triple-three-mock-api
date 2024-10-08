# the-triple-three-mock-api

Mock API REST to test integration.

## Steps

1. Create repository
2. Clone repository
3. Init node project

```
npm init -y
```

4. Install:

```
npm install json-server cors json-serve
```

5. Add script in package.json file:

```
"start": node index.js
```

6. Create index.js file in root
7. Add to server code to [example repository](https://github.com/UmaSahni/render-json-server/blob/main/index.js)
8. Add .gitignore file
9. Add db.json file with mock data
10. Push commit to repository

```
git add .
git commit -m "TTT-mock-api feat: add initial configuration"
git push
```

11. Deploy to [render](https://render.com/)

> - Register
> - New Web Service
> - Public GitHub repository
> - Configure deploy options
> - Deploy

12. Mock API is live in: [https://the-triple-three-mock-api.onrender.com](https://the-triple-three-mock-api.onrender.com)
