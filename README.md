# Bitcoin Bottom Index Dashboard

**Live site:** https://brls123.github.io/BBI-Page/

This repository hosts the published static site for the Bitcoin Bottom Index dashboard.

## What it is

Bitcoin Bottom Index (BBI) is a dashboard for tracking Bitcoin market conditions through a bottom-focused composite framework. It combines valuation, sentiment, macro, cycle, onchain, and market-context signals into a readable static site.

## What this repo contains

This is the deployment repository for GitHub Pages. It stores the generated static output only, including:

- prebuilt HTML pages
- static assets
- exported Next.js output
- API/static data files required by the dashboard

## Source repository

The source code, data refresh pipeline, and deployment workflow live here:

- https://github.com/brls123/BBI-Bitcoin-Index

## Update flow

The site is updated automatically from the source repository when the deploy workflow runs.

Typical triggers include:

- pushes to the main branch
- scheduled daily builds
- manual workflow runs

## Notes

If you are looking for the application source code, scripts, or workflow configuration, go to the source repository above. This repo is mainly for the published Pages output.
