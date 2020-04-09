# ng-packagr-pnpm

Sample repo showcasing that ng-packagr does not work with pnpm.

Output should be created in `src/app/hello/dist`

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
