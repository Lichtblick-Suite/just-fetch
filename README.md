# @lichtblick/just-fetch

Isomorphic ponyfill wrapping native browser fetch and node-fetch.

[![npm version](https://img.shields.io/npm/v/@lichtblick/just-fetch.svg?style=flat)](https://www.npmjs.com/package/@lichtblick/just-fetch)

### Usage

```ts
import fetch from "@lichtblick/just-fetch";
```

Usage is the same whether you are targeting browsers or node.js. The browser
target returns the native `window.fetch` implementation, and in node.js the
`node-fetch` library is returned.

## License

@lichtblick/just-fetch is licensed under the [MIT License](https://opensource.org/licenses/MIT).

## Releasing

1. Run `yarn version --[major|minor|patch]` to bump version
2. Run `git push && git push --tags` to push new tag
3. GitHub Actions will take care of the rest
