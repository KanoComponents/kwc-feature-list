# \<kwc-feature-list\>

A formatted, responsive list of features with images and descriptive text

 - What is it called?
     - kwc-feature-list
 - What is it made out of?
     - `iron-image`
 - What variants are needed?
     - Title
     - Without title
 - How does it scale?
     - Desktop: features occupy a third of the block and sit in a horizontal row.
     - Mobile: features occupy the whole width of the block and stack in a single column
 - What style variables are in use?
     - Requires the following variables from `kano-style`:
        - `--color-porcelain`
        - `--color-black`
        - `--color-grey`
        - `--font-heading`
        - `--font-body`
      - Exposes the following style variables:
        - `--kwc-feature-list-bg-color`
        - `--kwc-feature-list-img-height`
        - `--kwc-feature-list-img-width`


## To do
This component is likely to need the specification refining and extra variants added as time goes on.

## Installation
Clone this repository.
Run `bower i`

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

## Viewing Your Element

```
$ polymer serve
```

## Running Tests

```
$ polymer test --skip-plugin junit-reporter
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
