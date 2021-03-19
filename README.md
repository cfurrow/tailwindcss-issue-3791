# Sample NextJS project + TailwindCSS JIT
In response to issue noted here: https://github.com/tailwindlabs/tailwindcss/issues/3791

```
error - ./src/styles/tailwind.css ((webpack)/css-loader/cjs.js??ref--5-oneOf-6-1!(webpack)/postcss-loader/cjs.js??ref--5-oneOf-6-2!./src/styles/tailwind.css)
Error: ENOENT: no such file or directory, stat '/media/acatzk/Hard%20Drive/backup/React-Projects/joshuagalit.com/src/styles/tailwind.css'
```

The question was why NextJS, TailwindCSS + TailwindCSS JIT throws an error for a dev, and if it was related to jsconfig.json in some way. 

This sample project does not throw the same error that the other dev had, so I don't think that's the case.

```
yarn install
yarn dev
```
