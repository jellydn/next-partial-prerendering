<h1 align="center">Welcome to next-partial-prerendering 👋</h1>

This is a demo of [Next.js](https://nextjs.org) using [Partial Prerendering](https://nextjs.org/docs/app/api-reference/next-config-js/partial-prerendering).

This template uses the new Next.js [App Router](https://nextjs.org/docs/app). This includes support for enhanced layouts, colocation of components, tests, and styles, component-level data fetching, and more.

It also uses the experimental Partial Prerendering feature available in Next.js 14. Partial Prerendering combines ultra-quick static edge delivery with fully dynamic capabilities and we believe it has the potential to [become the default rendering model for web applications](https://vercel.com/blog/partial-prerendering-with-next-js-creating-a-new-default-rendering-model), bringing together the best of static site generation and dynamic delivery.

> ⚠️ Please note that PPR is an experimental technology that is not recommended for production. You may run into some DX issues, especially on larger code bases, and known issues around performance of client-side navigations have not yet been addressed.

### ✨ [Demo](https://partial-perrendering.productsway.com/)

## Install

```sh
pnpm install
```

## Usage

```sh
pnpm dev
```

## How it works

The index route `/` uses Partial Prerendering through:

1. Enabling the experimental flag in `next.config.js`.

```js
experimental: {
    ppr: true,
},
```

2. Using `<Suspense />` to wrap Dynamic content.

## References

- [Learn Next.js: Partial Prerendering](https://nextjs.org/learn/dashboard-app/partial-prerendering)
- [Building towards a new default rendering model for web applications](https://vercel.com/blog/partial-prerendering-with-next-js-creating-a-new-default-rendering-model)
- [Difference between partial rendering(PPR) and the current streaming suspense?](https://github.com/vercel/next.js/discussions/58322)
- [Learn NextJs 14 App](https://github.com/jellydn/learn-nextjs14-dashboard)
- [Learn Next.js: Streaming](https://nextjs.org/learn/dashboard-app/streaming)

## Show your support

Give a ⭐️ if this project helped you!
