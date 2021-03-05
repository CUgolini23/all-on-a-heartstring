# LoveKnots On HeartStrings
![npm](https://img.shields.io/badge/npm-3.10.10-blue.svg)
![build](https://img.shields.io/badge/build-in%20development-yellow.svg)
[![compiler](https://img.shields.io/badge/compiler-roots-blue.svg)](http://roots.cx/)
[![Netlify Status](https://api.netlify.com/api/v1/badges/8025919e-5213-41df-9e96-259aa7771b8d/deploy-status)](https://app.netlify.com/sites/all-on-a-heartstring/deploys)

### Setup

- make sure [node.js](http://nodejs.org) and [roots](http://roots.cx) are installed
- clone this repo down and `cd` into the folder
- run `npm install`
- run `roots watch`
- localhost:1111

### Deploying

- If you just want to compile the production build, run `roots compile -e production` and it will build to public.
- To deploy your site with a single command, run `roots deploy -to XXX` with `XXX` being whichever [ship](https://github.com/carrot/ship#usage) deployer you want to use.
