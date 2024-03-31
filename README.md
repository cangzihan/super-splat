# SuperSplat紫寒魔改版

Official tools: https://playcanvas.com/super-splat

## New feature

- The customization feature allows users to select a region within the scene and delete Gaussian points based on specified criteria.
- Upon selection, the system identifies Gaussian points within the chosen region and removes them according to the defined conditions.

## Local Development

The steps required to clone the repo and run a local development server are as follows:
```
git clone https://github.com/playcanvas/super-splat.git
cd super-splat
npm i
npm run develop
```

The last command `npm run develop` will build and run a local version of the editor on port 3000. Changes to the source are detected and the editor is automatically rebuilt.

To access the local editor instance, open a browser tab and navigate to `http://localhost:3000`.
