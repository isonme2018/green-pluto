# Stackbit Fjord Theme

This site was generated by [www.stackbit.com](https://www.stackbit.com), v0.3.18.

Stackbit Fjord Theme original README is located [here](./README.theme.md).

# Running Your Site Locally

1. Install [Node.js and npm](https://nodejs.org/en/)

1. Install npm dependencies:

        npm install

1. Get "stackbit-api-key" from project menu in [Stackbit dashboard](https://app.stackbit.com/dashboard)

1. Run the following command to assign this key to `STACKBIT_API_KEY` environment variable:

        export STACKBIT_API_KEY={stackbit_netlify_api_key}

1. Run the following command to fetch additional site contents from Stackbit if needed:

        npx @stackbit/stackbit-pull --stackbit-pull-api-url=https://api.stackbit.com/pull/5f32e1664f6e7e001efb7502

1. Start a local development server:

        npm run develop

1. Browse to [http://localhost:8000/](http://localhost:8000/)
