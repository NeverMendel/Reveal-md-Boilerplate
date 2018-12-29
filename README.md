# Reveal-md Boilerplate

[![Build Status](https://travis-ci.com/NeverMendel/Reveal-md-Boilerplate.svg?branch=master)](https://travis-ci.com/NeverMendel/Reveal-md-Boilerplate)

Boilerplate for [reveal-md](https://github.com/webpro/reveal-md). Start writing your presentation in under 5 minutes.

The presentation will available at https://[your username].github.io/[repo name]. This one is available at https://nevermendel.github.io/Reveal-md-Boilerplate

## Get started

- Download this boilerplate:

```bash
curl https://github.com/NeverMendel/reveal-md-boilerplate/archive/master.zip --output boilerplate.zip
```

- Extract the files:

```bash
unzip ./boilerplate.zip
```

- Remove the zip you've just downloaded:

```bash
rm ./boilerplate.zip
```

- Install all the dependency by executing:

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