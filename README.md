# Github Globe

## Inspiration

This project was inspired by [Github's homepage](https://github.com/home), where they display real-time Github activity on a globe map.

## Usage

This project is bundled with [Webpack](https://webpack.js.org/):

```json
"build": "webpack --config=webpack.prod.js",
"build-dev": "webpack --config=webpack.dev.js",
"start": "webpack serve webpack-dev-server --open --config=webpack.dev.js"
```

Details:

```bash
npm start        # development build in ./dist
npm run build    # static production build in ./
```

## License

[MIT](https://choosealicense.com/licenses/mit/)
