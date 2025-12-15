# CTP Futureproof site

This repository contains the source for the CTP Futureproof Inc. website hosted on GitHub Pages. It uses [Jekyll](https://jekyllrb.com) with the [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes) remote theme.

## Local setup
1. Install Ruby and Bundler (`gem install bundler`).
2. Install dependencies: `bundle install`
3. Run the site locally: `bundle exec jekyll serve`
4. Open `http://localhost:4000` in your browser.

## Deployment
Changes merged into `main` are published automatically by GitHub Pages. Commit updates to content, configuration, or `assets/css/main.scss` to adjust branding.

GitHub Pages usually republishes within a few minutes, but CDN caching can delay visible updates for 5–10 minutes. If you have the site open already, do a hard refresh (Shift + Reload) to pull the latest assets after a deployment.
