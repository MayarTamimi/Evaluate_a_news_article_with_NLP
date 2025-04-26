# Udacity Project:

# Evaluate a news article with Natural Language Processing

## Build Tools

- HTML
- SASS
- Node js
- Webpack
- Aylien API
- Jest

## Run project

Below shows how to run in development and production mode.

### run in development mode

To start the webpack dev server at port 8080

` $ npm run build-dev`

### run in production mode

Generate the dist files and then start server at port 3000

` $ npm run build-prod`

` $ npm run start`

## Configs

Here, we have two webpack config files for both development mode(`webpack.config.dev.js`) and production mode(`webpack.config.prod.js` )

We also have a `package.json` to manage dependencies

## API

The project uses the Text Analysis SDKs from [aylien](https://aylien.com/text-api/sdks/), which provides a powerful and flexible AI-driven content analysis solutions.

## Testing

Testing is done with Jest. To run test, use the command

`npm run test`.
