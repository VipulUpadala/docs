# Docs for WP-Tide

We're managing the docs for the [wptide.org](http://wptide.org) site here.

This repo uses branched out Docpress which is being tweaked and stripped down to allow integrating with WordPress.

It's a very basic WP theme that takes all routes into main `index.php` file where they are resolved to pull 
the static content generated by Docpress.

## Doc Site Installation Details

To develop locally, run:
1. `git clone` to clone this repo to WordPress theme folder.
2. `npm install` to install the repo's dependencies.
3. `npm run link` to link the local docpress packages and install their dependencies.
4. `npm run dev` to build and watch assets.
5. Activate the theme and visit the homepage.

## Doc Site Activation Details

After the theme dependencies have been installed and the files have been built, you can activate "Tide Documentation Theme" just as you would any other theme in the theme menu.

## Development

`docpress` customized Docpress generator that we bundle with the theme
`docs` is the root of the content source
`src` contains all styles, scripts and layout

`_docpress` is the build folder, never place anything here as it will get overwritten

## Contributions 
Pull requests are welcome.
