# node-typescript-simple

Install: 
  * npm i -g typescript
  * npm i -g ts-node

Execute: 
 1. npm init
 2. tsc --init
 
 ```json
 tsconfig example:
 {
  "compilerOptions": {
    "target": "es5",                          /* Specify ECMAScript target version: 'ES3' (default), 'ES5', 'ES2015', 'ES2016', 'ES2017','ES2018' or 'ESNEXT'. */
    "module": "commonjs",                     /* Specify module code generation: 'none', 'commonjs', 'amd', 'system', 'umd', 'es2015', or 'ESNext'. */
    "lib": ["es2016", "dom"],                             /* Specify library files to be included in the compilation. */
    "declaration": false,                   /* Generates corresponding '.d.ts' file. */
    "outDir": "./dist",                        /* Redirect output structure to the directory. */
    "strict": true,                           /* Enable all strict type-checking options. */
    "esModuleInterop": true,                   /* Enables emit interoperability between CommonJS and ES Modules via creation of namespace objects for all imports. Implies 'allowSyntheticDefaultImports'. */
  },
  "include": ["src/**/*"]
}
```