# Blogkit Notion Starter

Starter template for [blogkit](https://github.com/2nthony/blogkit).

## Blogging

First, duplicate the [template](https://2nthony.notion.site/cd8c60e825274c278e671af80f09f385?v=c8368886a493480b848ab10bb16b9a2b) to your notion.

## Build the blog

Before building the blog, you need to follow the [Getting Started](https://developers.notion.com/docs/getting-started#getting-started) to get 2 required **environment variables** below:

- `NOTION_TOKEN`
- `NOTION_DATABASE_ID`

```console
npm i

npm run export
```

The static site will be output to `out/`.
