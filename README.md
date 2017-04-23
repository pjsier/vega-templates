# Templates for Vega Visualizations

Templates in Vega 3.0 for generating different data visualizations.

## Setup

* For dependencies on generating Vega png and svg files, (on Mac), run `brew install pixman cairo`
* Then run `npm install`

## Run Server

Run a server locally with `npm start`, and navigate to `localhost:3000` to see visualizations
through the `vega-embed` library. Use the dropdown to select which visualization
to display from a list populated by all files in the `viz` directory.

## Generate Images

[Pulled from Vega docs](https://vega.github.io/vega/usage/#examples)

* PNG: `./node_modules/.bin/vg2png {JSON_FILE} {PNG_OUTPUT}`
* SVG: `./node_modules/.bin/vg2svg {JSON_FILE} {SVG_OUTPUT}`
