<!-- <a href="https://app.netlify.com/start/deploy?repository=https://github.com/edsilv/biiif-template">
  <img src="https://www.netlify.com/img/deploy/button.svg" alt="Deploy to Netlify" />
</a> -->

# biiif-template

A template for creating IIIF manifests/collections with [biiif](https://github.com/edsilv/biiif/)

## Netlify

[![Deploy with Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/edsilv/biiif-template)

<details>
  <summary>Netlify Instructions</summary>
  1. Click "Deploy to Netlify"
  2. Click "Connect to Github"
  3. Choose a name for your new repository, e.g. "my-cool-iiif"
  4. Click "Save and Deploy"
  5. Copy the auto-generated name for your site, e.g. `confident-goldstine-3646b6`
  6. Underneath your site name, where it says "Deploys from GitHub", click on the Github link to visit your newly generated repository
  7. Click on `package.json`
  8. Click on the "Edit this file" pencil in the top right corner
  9. Where it says `"build": "npx biiif collection -u https://sitename.netlify.app"`, paste your netlify site name to replace `sitename`.
  10. It should now read something like `"build": "npx biiif collection -u https://confident-goldstine-3646b6.netlify.app"`
  11. Scroll down and commit your changes
  12. Wait a few moments for your netlify site to redeploy, then visit `https://confident-goldstine-3646b6.netlify.app/index.json`. This is your published IIIF manifest
</details>

## Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/git/external?repository-url=https%3A%2F%2Fgithub.com%2Fedsilv%2Fbiiif-template&project-name=my-cool-iiif&repo-name=my-cool-iiif)

<details>
  <summary>Vercel Instructions</summary>
  1. Click "Deploy"
  2. coming soon...
</details>
