# Stackbit Tutorial [Gatsby + Contentful]

![Tutorial Screenshot](https://assets.stackbit.com/docs/tutorial-shared-thumb-v2.png)

ℹ️ This project is used as a starting point for [a getting started tutorial](https://docs.stackbit.com/getting-started/gatsby-contentful) using Gatsby as the framework and Contentful as the content source. If you would like to create a new project with Contentful as the content source, check out [the Gatsby + Contentful example project](https://github.com/stackbit-themes/stackbit-examples/tree/main/gatsby-contentful).

## Prerequisites

Before you begin, please make sure you have the following:

- Contentful account
- Node v18 or later

### Setup

Copy `.env.example` to `.env` and fill in the appropriate values.

```bash
CONTENTFUL_SPACE_ID="..."
CONTENTFUL_PREVIEW_TOKEN="..."
CONTENTFUL_DELIVERY_TOKEN="..."
CONTENTFUL_MANAGEMENT_TOKEN="..."
```

### Run the Project

Now you should be able to run the Gatsby development server and see your content.

    npm run develop

Visit `localhost:8000` and you should see the example content you imported into your new Contentful space.

And then for starting the Stackbit server:

     stackbit dev --port 8000

## Support

If you get stuck along the way, [drop into our Discord server](https://discord.gg/HUNhjVkznH) and send a message in the `#documentation` or `#help` channels.
