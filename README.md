# Cours d'Angular

## Sommaire

## Installation
```
npm install -g @angular/cli
```

## Premier projet
```
ng new mon-premier-projet
ng serve
```

## PWA
```
ng add @angular/pwa
npm install lite-server --save-dev
```

Ajouter au package.json
```
"start:prod": "ng build --prod && lite-server --baseDir dist/nomDeVotreApplication",
```