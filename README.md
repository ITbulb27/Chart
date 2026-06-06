


# ⚠️ No Longer Maintained ⚠️
This project is no longer actively maintained. No further updates, bug fixes, or support will be provided.

----

Simple, immersive and interactive charts for React




## Quick Features

- Line Charts
- Bar Charts
- Column Charts
- Bubble Charts
- Area Charts
- Axis Stacking
- Inverted Axes
- Hyper Responsive
- Invisibly Powered by D3
- Declarative
- Mutliple Axes



# Contributors ✨


<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->


<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->


<!-- Force 2 -->

## Running the examples (Windows)

If you're on Windows, the dev tooling and scripts may need small tweaks. The steps below worked in this workspace and are the quickest way to run the `examples/simple` app:

1. Build the local package (from the repo root):

   - `npm install --legacy-peer-deps`
   - `npm install yarn --save-dev --legacy-peer-deps`
   - `npx yarn build`

2. Start the simple example:

   - `cd examples/simple`
   - `npm install --legacy-peer-deps`
   - `npm start`

Tips & troubleshooting

- If npm fails with peer dependency errors, re-run `npm install` with `--legacy-peer-deps`.
- If you hit OpenSSL errors like `ERR_OSSL_EVP_UNSUPPORTED` on recent Node versions, start the dev server with the legacy provider:

  PowerShell:

  - `$env:NODE_OPTIONS='--openssl-legacy-provider'; npm start`

  CMD:

  - `set NODE_OPTIONS=--openssl-legacy-provider&& npm start`

- The example's static HTML and global CSS are located at:

  - `examples/simple/public/index.html`
  - `examples/simple/src/styles.css`

- If the dev server reports a port is already in use it will prompt to use another port — answer `Y` to continue.

