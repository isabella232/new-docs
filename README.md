# npm new-docs
> a manifest for the npm guides

## up and running

1. fork and clone this project
2. `cd new-docs/`
3. `npm install`
4. `npm run build`
5. `npm start`

## scripts

- `npm start`: starts a server using [`live-server`]
- `npm run build`: builds styles and scripts (see below)
- `npm run build:styles`: uses [`@npmcorp/dr-frankenstyle`] to build
  `public/styles/components.css`
- `npm run build:scripts`: uses [`browserify`] to build `public/scripts/bundle.js`

[`live-server`]: https://www.npmjs.com/package/live-server
[`@npmcorp/dr-frankenstyle`]: https://www.npmjs.com/package/@npmcorp/dr-frankenstyle
[`browserify`]: http://browserify.org/
