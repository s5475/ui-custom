# UI Custom

Extended base theme for Hugo **s5475**.

## Install

```sh
git submodule add 'https://github.com/s5475/ui-custom.git' 'themes/ui-custom'
```

## Update

```sh
git submodule update --recursive --remote --merge
```

## Uninstall

```sh
m='ui-custom'; git submodule deinit -f "themes/${m}"; git rm -r --cached "themes/${m}"; rm -rf ".git/modules/themes/${m}"; rm -rf "themes/${m}"
```
