
## [2022-06-26] v0.6.0


## [2022-06-25] v0.5.1

- ccf6b29 [feat: make prefix-only core module as external module](https://github.com/electron-vite/vite-plugin-electron/pull/22)

## [2022-06-24] v0.5.0

- 0c5155c chore: TODO
- 892940e fix app,getName() return error name

## [2022-06-14] v0.4.9

- abf460f chore: variable rename
- ceb559f chore: `build.cssCodeSplit=false`

## [2022-06-08] v0.4.8

- ab40088 fix(🐞): set `emptyOutDir=false` for prevent accidental deletion of files
- 7baafa0 break: set `electron` `build.outDir` value is `dist/electron` by default
- c13eb49 fix(🐞): assign default value `dist/electron/[process]` of `build.outDir`
  https://github.com/electron-vite/vite-plugin-electron/issues/10

## [2022-06-06] v0.4.7

- 1346707 refactor: better assign default `build.outDir`
- f489da1 chore: commnets
- 6db3bf3 fix: check `output` is Array

## [2022-06-04] v0.4.6

- 394cf6f feat: `config.build.emptyOutDir = false` by default
- 4a67688 feat(🐞): enabled `polyfill-exports` by default