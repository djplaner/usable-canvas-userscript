# Getting Started

For the example, assume your app name is `usable-canvas-course-check` (git and file system) and `UsableCanvasCourseCheck` (Svelte component name)

## 1. Clone the repo

:construction:

## 2. Modify the config

1. Change the name of App.ts in `src` to your app name
2. Modify `package.json` 
   1. description

## 3. Update rollup config

rollup.build.config.js and rollup.config.js

1. change `usable-canvas-userscript.js` to your app name


rollup.config.js

- If using the shoelace style component library, uncomment that section
- install showlace  `npm install @shoelace-style/shoelace`

## 4. Update userscript details (meta.js)

1. Change `usable-canvas-userscript` to your app name

## 5. Update the local userscript (dist/usable-canvas-userscript.dev.user.js)

1. Change `usable-canvas-userscript` to your app name
2. Change the folder for the `@resource` and `@require` to your folder structure


## 6. Remove the files in `dist` folder but not `dev.user.js`