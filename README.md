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
    <li>Click Deploy to Netlify</li>
    <li>Click Connect to Github</li>
    <li>Choose a name for your new repository, e.g. "my-cool-iiif"</li>
    <li>Click Save and Deploy</li>
    <li>Copy the auto-generated name for your site, e.g. `confident-goldstine-3646b6`</li>
    <li>Underneath your site name, where it says Deploys from GitHub, click on the Github link to visit your newly generated repository</li>
    <li>Click on `package.json`</li>
    <li>Click on the "Edit this file" pencil in the top right corner</li>
    <li>Where it says `"build": "npx biiif collection -u https://sitename.platform.app"`, paste your netlify site name to replace `sitename`, and replace `platform` with `netlify`</li>
    <li>It should now read something like `"build": "npx biiif collection -u https://confident-goldstine-3646b6.netlify.app"`</li>
    <li>Scroll down and commit your changes</li>
    <li>Wait a few moments for your netlify site to redeploy, then visit `https://confident-goldstine-3646b6.netlify.app/index.json`. This is your published IIIF manifest</li>
  </ol>
</details>

## Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/git/external?repository-url=https%3A%2F%2Fgithub.com%2Fedsilv%2Fbiiif-template&project-name=my-cool-iiif&repo-name=my-cool-iiif)

<details>
  <summary>Vercel Instructions</summary>
  <ol>
    <li>Click Deploy</li>
    <li>Enter a name for your project, e.g. "my-cool-iiif"</li>
    <li>Click Continue</li>
    <li>Choose Github</li>
    <li>Enter a name for your repository, e.g. "my-cool-iiif"</li>
    <li>Optionally select Create Private Git Repository</li>
    <li>Click Continue</li>
    <li>On the Import Project screen leave it on the default settings click Continue</li>
    <li>Optionally specify a project name</li>
    <li>Expand Build and Output Settings In Output directory, enter "collection"</li>
    <li>Wait for the deploy to complete</li>
    <li>Click Open Dashboard</li>
    <li>Copy your project name, e.g. "my-cool-iiif"</li>
    <li>Underneath your project name, where it has a Github icon, click on the Github link to visit your newly generated repository</li>
    <li>Click on `package.json`</li>
    <li>Click on the "Edit this file" pencil in the top right corner</li>
    <li>Where it says `"build": "npx biiif collection -u https://sitename.platform.app"`, paste your vercel project name to replace `sitename`, and replace `platform` with `vercel`.</li>
    <li>It should now read something like `"build": "npx biiif collection -u https://my-cool-iiif.vercel.app"`</li>
    <li>Scroll down and commit your changes</li>
    <li>Wait a few moments for your vercel site to redeploy, then visit `https://my-cool-iiif.vercel.app/index.json`. This is your published IIIF manifest</li>
  </ol>
</details>
