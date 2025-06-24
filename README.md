# Deprecated Version React Resume with Vercel
The main reason for ultimately deciding to deprecate this version is that the webpage is flashy but impractical. The source code is overly bloated and entirely forked from React Resume, making it difficult for me to maintain and offering limited scalability.

## Still Accessible Here : [deprecated version](https://qiyuan-personal-website.vercel.app/)
Previously, it was deployed to Vercel, but Vercel was linked to this repo and kept trying to build my main branch. The build kept failing, which resulted in a prominent red X that I didn’t like. So I simply disconnected it from Vercel. I won’t be updating this deprecated version anyway. The current visible version is from March 2025.

## Just in case it might be needed in the future
Install [Node](https://nodejs.org/en/download/package-manager) and [Yarn](https://yarnpkg.com/getting-started/install). Reconfigure fnm environment as follows:
```bash
fnm env --use-on-cd | Out-String | Invoke-Expression
```

Open your terminal and install all dependencies. After all dependencies installed, you can start to run your website on localhost.
```bash
yarn install
yarn dev
```

## Deploy the Website
It is recommended to first create a GitHub repository, then push the built web project to GitHub. After that, log in to [Vercel](https://vercel.com/) and follow their steps to complete the deployment. Once deployed, a Vercel URL will be generated, which can be used to access the corresponding website. If you want to use a custom domain, purchase the domain first, and then point its DNS to Vercel.


Read more: https://nextjs.org/docs/messages/export-image-api
```
The error message indicates that you are trying to export a Next.js project as a static site (using output: 'export'), but the default image optimization feature is incompatible with static exports. To resolve this issue, you can disable Next.js's image optimization feature. If you prefer not to disable image optimization, the best option is to use a hosting platform that can run a Next.js server (such as Vercel, Heroku, etc.) or configure an external image optimization service. However, if you still wish to use GitHub Pages, the only option is to disable the image optimization feature, as GitHub Pages does not support dynamic functionality.
