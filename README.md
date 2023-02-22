# [Blogkit Notion Starter](https://github.com/2nthony/blogkit-notion-starter)

Starter template for [blogkit](https://github.com/2nthony/blogkit).

## Getting started

### Get notion template

Duplicate the [database](https://2nthony.notion.site/b48993719cb846d09bd22b8fe211728a?v=e47faf3edb0a49378e650b5e95dac6d8) to your notion.

### Connect notion database

Follow the [Create an integration](https://developers.notion.com/docs/create-a-notion-integration) to:

1. Get `NOTION_TOKEN` (secrets from internal integration **token**)
2. Add connection to the database
3. Get `NOTION_DATABASE_ID`

Save `NOTION_TOKEN` and `NOTION_DATABASE_ID`.

## Configuration

1. Update the site title in `blogkit.config.ts`.

## Deploy your own

Deploy the blogkit notion starter using Vercel:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2F2nthony%2Fblogkit-notion-starter&env=NOTION_TOKEN,NOTION_DATABASE_ID)

## FAQ

### Can not find database ID xxxxxxxxxx

<details><summary>You might forgot to: <a href="https://developers.notion.com/docs/create-a-notion-integration#step-2-share-a-database-with-your-integration">Share a database with your integration</a>.</summary>

![](https://user-images.githubusercontent.com/19513289/216370424-f119d24f-6609-4b1d-a4c1-935a0bde6d5e.png)

</details>
