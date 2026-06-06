# React Charts Docs

- Next.js
- MDX
- Tailwind
- Algolia
- Notion

## Running locally

```sh
yarn install
```

With tokens and page index in hand, rename `.sample.env` and `.sample.env.build` to just `.env` and `.env.build`. In each one, add respective parameters:

```diff
-NOTION_TOKEN=XXXX
+NOTION_TOKEN=<YOUR_TOKEN>
-BLOG_INDEX_ID=XXXXX
+BLOG_INDEX_ID=<YOUR_BLOG_INDEX_ID>
```

Now it will work. Run `yarn dev` to get going.

