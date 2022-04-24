# GameCI

Documentation for open source GameCI projects. You can find the `.md` files inside the [docs](./docs) folder.
The live version is available on [game.ci](https://game.ci). This website is built using 
[Docusaurus 2](https://docusaurus.io/), a modern static website generator.

### Installation

```bash
yarn
```

### Local Development

```bash
yarn start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```bash
yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

Using SSH:

```bash
USE_SSH=true yarn deploy
```

Not using SSH:

```bash
GIT_USER=<Your GitHub username> yarn deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.

## Community

Feel free to join us on
[![Discord](assets/readme/Discord.svg)](https://game.ci/discord)
and engage with the community.

## Support us

GameCI is free for everyone forever.

You can support us at [OpenCollective](https://opencollective.com/game-ci).

## Licence

This repository is [MIT](./LICENSE) licensed.

This includes all contributions from the community.

## Sponsors

[![Vercel](assets/readme/Vercel.svg)](https://vercel.com?utm_source=game-ci)
