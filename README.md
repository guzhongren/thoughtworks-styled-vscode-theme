# Thoughtworks Styled Theme


## How to dev

```sh
pnpm install
```

### Build

```sh
rm *.vsix
npx vsce package
```

### Debug in local

* CMD+shift+ p: select `Extensions: Disable All Installed Extensions`
* Select your color theme
* Reload VSCode


## Publish

```sh
# build .vsix before publishing
npx vsce publish
```
**Enjoy!**


## Ref

- https://github.com/microsoft/vscode/blob/main/src/vs/platform/theme/common/colors/editorColors.ts
