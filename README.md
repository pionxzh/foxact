<img src="https://pic.skk.moe/gh/foxact.gif" alt="foxact logo" width="128" height="128" align="right" />

# foxact

React Hooks/Utils done right. For Browser, SSR, and React Server Components.

## Documentation

Under construction.

## Features

#### React 18 Safe

All hooks and utils are React 18+ Concurrent Rendering resilient.

**foxact** strictly follows React best practices, e.g. never read and write ref during the render phase, unlike many other open-sourced React Hooks libraries.

You can use **foxact** with `<Suspense />`, `startTransition`, `<OffScreen />` without worrying about app falling apart.

#### SSR Friendly

Works perfectly with server-side rendering, incremental static generation, and static site generation.

Supports [Next.js](https://nextjs.org) (both Pages Directory and App Router), [Waku](https://github.com/dai-shi/waku), [Gatsby](https://www.gatsbyjs.com/), [Remix](https://remix.run/), and [Shopify Hydrogen](https://hydrogen.shopify.dev/).

#### Type Safe and Sound

Written in TypeScript with TSDocs, supports TypeScript 4.8+.

#### Super Lightweight

The entire **foxact** library has zero dependencies and is **less than 5 KiB gzipped in sum**. And what's more...

#### Fully Tree Shakable

Feel free to take what you want from **foxact** without worrying about client bundle size.

## License

[MIT](./LICENSE)

----

**foxact** © [Sukka](https://github.com/SukkaW), Released under the [MIT](./LICENSE) License.
Authored and maintained by Sukka with help from contributors ([list](https://github.com/SukkaW/foxact/graphs/contributors)).

> [Personal Website](https://skk.moe) · [Blog](https://blog.skk.moe) · GitHub [@SukkaW](https://github.com/SukkaW) · Telegram Channel [@SukkaChannel](https://t.me/SukkaChannel) · Mastodon [@sukka@acg.mn](https://acg.mn/@sukka) · Twitter [@isukkaw](https://twitter.com/isukkaw) · Keybase [@sukka](https://keybase.io/sukka)
