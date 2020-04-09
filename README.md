# ng-packagr-pnpm

Sample repo showcasing that ng-packagr@9.1.0 does not work with pnpm.

Output should be created in `src/app/hello/dist`

Make sure to `rm -r node_modules` if you switch between npm and pnpm!

```
ng-packagr:            9.1.0
@angular/compiler:     9.1.1
rollup:                2.2.0
tsickle:               0.38.0
typescript:            3.8.3
```

# NPM works

- `git clone https://github.com/knafteN/ng-packagr-pnpm.git`
- `cd ng-packagr-pnpm`
- `npm i`
- `npm run pkg`

# PNPM does _not_ work

- `npm i -g pnpm`
- `git clone https://github.com/knafteN/ng-packagr-pnpm.git`
- `cd ng-packagr-pnpm`
- `pnpm i`
- `pnpm run pkg`

```
Compiling TypeScript sources through ngc
ERROR: Cannot read property 'type' of null
 ERROR  Command failed with exit code 111.
```
