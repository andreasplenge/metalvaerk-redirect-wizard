# metalvaerk.dk → metalværk.dk Redirect

This repository hosts a simple redirect from the old domain `metalvaerk.dk` to the new domain `metalværk.dk`.

## How it works

- All requests to `metalvaerk.dk` are redirected to `metalværk.dk`
- URL paths are preserved (e.g., `/about` → `metalværk.dk/about`)
- Uses GitHub Pages for hosting

## Deployment

The site automatically deploys via GitHub Actions when changes are pushed to the `main` branch.

You can also manually trigger a deployment from the Actions tab.

## DNS Configuration

Point your domain registrar's DNS to GitHub Pages:

- A record: `@` → `185.199.108.153`
- A record: `@` → `185.199.109.153`
- A record: `@` → `185.199.110.153`
- A record: `@` → `185.199.111.153`
