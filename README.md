# Reveal-md Boilerplate

[![Build Status](https://travis-ci.com/NeverMendel/Revealmd-Boilerplate.svg?branch=master)](https://travis-ci.com/NeverMendel/Revealmd-Boilerplate)

Boilerplate for [reveal-md](https://github.com/webpro/reveal-md). Start writing your presentation in under 5 minutes.

The presentation will available at https://[your username].github.io/[repo name]. This one is available at https://nevermendel.github.io/Revealmd-Boilerplate

## Get started

- Download this boilerplate:

```bash
git clone --depth=1 https://github.com/NeverMendel/Revealmd-Boilerplate.git <your project name>
```

- Move to the project directory:

```bash
cd <you project name>
```

- Install all the dependency:

```bash
npm install
```

- Change the name and the description in `package.json`

- Set up Travis-CI GITHUB-TOKEN variable to allow Travis to deploy the site in GitHub pages.

## Write the content

You can find a quick guide on how to write your presentation on `slides.md`.

After you've read the guide, write your presentation in `slides.md`.

## Deploy

To use the local webserver execute:

```bash
npm start
```

The local webserver will be available at http://localhost:1948

To generate the static website in the _site folder execute:

```bash
npm run build
```

To deploy on GitHub Pages make sure you've set up your GitHub token correctly in Travis-CI website.