# CartoParrainages

Basé sur rollup-startup-app https://github.com/rollup/rollup-starter-app pour le déploiement (utilise rollup pour le packaging, sass pour les styles)
Les données sont découpées par département dans le dossier assets/data

## Utilisation


Dans le répertoire du projet: 

```bash
git clone https://github.com/jmlahire/CartoParrainages.git .
npm install

```

The `public/index.html` file contains a `<script src='bundle.js'>` tag, which means we need to create `public/bundle.js`. The `rollup.config.js` file tells Rollup how to create this bundle, starting with `src/js/app.js` and including all its dependencies.

`npm run build` builds the application to `public/bundle.js`, along with a sourcemap file for debugging.

`npm start` launches a server, using [serve](https://github.com/zeit/serve). Navigate to [localhost:3000](http://localhost:3000).

`npm run watch` will continually rebuild the application as your source files change.

`npm run dev` will run `npm start` and `npm run watch` in parallel.

## License

[MIT](LICENSE).
