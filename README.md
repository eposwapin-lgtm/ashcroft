# Ashcroft & Co. Furniture

Single-page furniture website. Heroku-ready.

## Open offline
Double-click `public/index.html`.

## Run locally
```
npm install
npm start
```
Open http://localhost:3000

## Deploy to Heroku
```
heroku login
heroku create ashcroft-furniture
git init && git add . && git commit -m "init"
heroku git:remote -a ashcroft-furniture
git push heroku main
heroku open
```

## Files
- `public/index.html` — full single-page site
- `public/hero.jpg`, `public/about.jpg` — the 2 images
- `server.js`, `package.json`, `Procfile` — Heroku stack
