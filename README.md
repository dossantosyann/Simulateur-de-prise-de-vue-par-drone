# Simulateur-de-prise-de-vue-par-drone

# Notes perso

## Sources
https://www.youtube.com/watch?v=ctQMqqEo4G8

## Création frontend (client), projet React via Vite :
npx create-vite
-> React
-> Javascript
cd "dossier"
npm install
npm run dev

## Création backend (server), python Flask :
python3 -m venv venv
source venv/bin/activate
pip3 install flask
-> créer main.py

## Installer flask-cors :
pip3 install Flask-CORS

## Importer cors dans backend :
in main.py : from flask_cors import CORS

## Installer axios :
npm install axios

## Importer useEffect dans frontend : 
in client/src/app.jsx modify first line to : import { useState, useEffect } from 'react'
