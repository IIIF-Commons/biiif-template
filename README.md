<!-- <a href="https://app.netlify.com/start/deploy?repository=https://github.com/edsilv/biiif-template">
  <img src="https://www.netlify.com/img/deploy/button.svg" alt="Deploy to Netlify" />
</a> -->

# biiif-template

A template for creating IIIF manifests/collections with [biiif](https://github.com/edsilv/biiif/)

## Netlify

[![Deploy with Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/edsilv/biiif-template)

<details>
  <summary>Netlify Instructions</summary>
  <ol>
    <li>Click "Deploy to Netlify"</li>
    <li>Click "Connect to Github"</li>
    <li>Choose a name for your new repository, e.g. "my-cool-iiif"</li>
    <li>Click "Save and Deploy"</li>
    <li>Copy the auto-generated name for your site, e.g. `confident-goldstine-3646b6`</li>
    <li>Underneath your site name, where it says "Deploys from GitHub", click on the Github link to visit your newly generated repository</li>
    <li>Click on `package.json`</li>
    <li>Click on the "Edit this file" pencil in the top right corner</li>
    <li>Where it says `"build": "npx biiif collection -u https://sitename.netlify.app"`, paste your netlify site name to replace `sitename`.</li>
    <li>It should now read something like `"build": "npx biiif collection -u https://confident-goldstine-3646b6.netlify.app"`</li>
    <li>Scroll down and commit your changes</li>
    <li>Wait a few moments for your netlify site to redeploy, then visit `https://confident-goldstine-3646b6.netlify.app/index.json`. This is your published IIIF manifest</li>
  </ol>
</details>

## Vercel (work in progress)

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/git/external?repository-url=https%3A%2F%2Fgithub.com%2Fedsilv%2Fbiiif-template&project-name=my-cool-iiif&repo-name=my-cool-iiif)

<details>
  <summary>Vercel Instructions</summary>
  <ol>
    <li>Click "Deploy"</li>
    <li>coming soon...</li>
  </ol>
</details>
