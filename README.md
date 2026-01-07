# Thoughtworks Styled Theme


## How to dev

```sh
pnpm install
```

### Build

```sh
rm *.vsix
# Update version in package.json
npx vsce package
```

### Debug in local

* Press 'F5' into debug mod
* CMD+shift+ p: select `Extensions: Disable All Installed Extensions`
* Select your color theme
* Reload VSCode


## Publish

Create a [PAT](https://code.visualstudio.com/api/working-with-extensions/publishing-extension#get-a-personal-access-token)

```sh
./scripts/release
```

See the verification status [here](https://marketplace.visualstudio.com/manage/publishers)
**Enjoy!**


## Ref

- https://github.com/microsoft/vscode/blob/main/src/vs/platform/theme/common/colors/editorColors.ts
