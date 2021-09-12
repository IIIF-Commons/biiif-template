<!-- <a href="https://app.netlify.com/start/deploy?repository=https://github.com/edsilv/biiif-template">
  <img src="https://www.netlify.com/img/deploy/button.svg" alt="Deploy to Netlify" />
</a> -->

# biiif-template

A template for creating IIIF manifests/collections with [biiif](https://github.com/edsilv/biiif/)

## How to deploy

- [Netlify](#Netlify)
- [Vercel](#Vercel)

## Netlify

[![Deploy with Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/edsilv/biiif-template)

  1. Click Deploy to Netlify
  2. Click Connect to Github
  3. Choose a name for your new repository, e.g. "my-cool-iiif"
  4. Click Save and Deploy
  5. Copy the auto-generated name for your site, e.g. `confident-goldstine-3646b6`
  6. Underneath your site name, where it says Deploys from GitHub, click on the Github link to visit your newly generated repository
  7. Click on `package.json`
  8. Click on the Edit this file pencil in the top right corner
  9. Where it says `"build": "npx biiif collection -u https://sitename.platform.app"`, paste your netlify site name to replace `sitename`, and replace `platform` with `netlify`
  10. It should now read something like `"build": "npx biiif collection -u https://confident-goldstine-3646b6.netlify.app"`
  11. Scroll down and commit your changes
  12. Wait a few moments for your netlify site to redeploy, then visit `https://confident-goldstine-3646b6.netlify.app/index.json`. This is your published IIIF manifest

## Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/git/external?repository-url=https%3A%2F%2Fgithub.com%2Fedsilv%2Fbiiif-template)

  1. Click Deploy
  2. Enter a name for your repository, e.g. "my-cool-iiif"
  3. Optionally select Create Private Git Repository
  4. Click Continue
  5. Choose a team, or skip
  8. On the Import Project screen leave it on the default settings and click Continue
  9. Optionally specify a project name
  10. Expand Build and Output Settings In Output directory, enter "collection"
  11. Wait for the deploy to complete
  12. Click Open Dashboard
  13. Copy your project name, e.g. "my-cool-iiif"
  14. Underneath your project name, where it has a Github icon, click on the Github link to visit your newly generated repository
  15. Click on `package.json`
  16. Click on the Edit this file pencil in the top right corner
  17. Where it says `"build": "npx biiif collection -u https://sitename.platform.app"`, paste your vercel project name to replace `sitename`, and replace `platform` with `vercel`.
  18. It should now read something like `"build": "npx biiif collection -u https://my-cool-iiif.vercel.app"`
  19. Scroll down and commit your changes
  20. Wait a few moments for your vercel site to redeploy, then visit `https://my-cool-iiif.vercel.app/index.json`. This is your published IIIF manifest
</details>
