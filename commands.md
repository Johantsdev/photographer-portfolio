# Toutes les commandes faite sur le projet

## nb :

    Ajouter dans package.json :
        "scripts": {
            "dev": "parcel src/index.html",
            "build": "parcel build src/index.html",
            "format": "prettier --write \"src/**/*.{js,jsx}\"",
            "lint": "eslint \"src/**/*.{js,jsx}\" --quiet"
        }

## Intialisation :

    ~ npm init -y

## Prettier :

    | npm install --save-dev prettier

## eslint :

    | npm i -D eslint eslint-config-prettier

## parcel :

    | npm i -D parcel

## React :

    | npm install react react-dom

## Permettre à eslint de reconnaitre jsx:

    | npm install -D eslint-plugin-import eslint-plugin-jsx-a11y eslint-plugin-react

## Règles eslint pour les hooks :

    | npm install -D eslint-plugin-react-hooks

## React router :

    | npm i react-router-dom

## React Query :

    | npm install @tanstack/react-query
