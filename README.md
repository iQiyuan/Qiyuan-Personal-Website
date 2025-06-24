# Deprecated Version React Resume with Vercel
The main reason for ultimately deciding to deprecate this version is that the webpage is flashy but impractical. The source code is overly bloated and entirely forked from React Resume, making it difficult for me to maintain and offering limited scalability. 

## Still Accessible Here : [deprecated version](https://qiyuan-personal-website.vercel.app/)
Previously, it was deployed to Vercel, but Vercel was linked to this repo and kept trying to build my main branch. The build kept failing, which resulted in a prominent red X that I didn’t like. So I simply disconnected it from Vercel. I won’t be updating this deprecated version anyway. The current visible version is from March 2025.

## Just in case it might be needed in the future
Install [Node](https://nodejs.org/en/download/package-manager) and [Yarn](https://yarnpkg.com/getting-started/install). Reconfigure the **fnm** env as follows:
```bash
fnm env --use-on-cd | Out-String | Invoke-Expression
```
Once the repository is ready, start the local host by:
```bash
yarn install
yarn dev
```

## Deploy the Website with [Vercel](https://vercel.com/)
Navigate to Vercel and create a new project, and follow the steps to link it to the repository.
