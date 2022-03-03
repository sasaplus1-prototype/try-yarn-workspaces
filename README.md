# try-yarn-workspaces

try [yarn workspaces](https://classic.yarnpkg.com/lang/en/docs/workspaces/)

## add module

add `packages/a` to `packages/core`:

```console
$ yarn workspace core add a@1.0.0 # semver required
```

see: https://github.com/yarnpkg/yarn/issues/4878#issuecomment-386607832

## remove module

remove `packages/a` from `packages/core`:

```console
$ yarn workspace core remove a
```

## Ref

- https://classic.yarnpkg.com/en/docs/workspaces
- https://classic.yarnpkg.com/lang/en/docs/cli/workspace/
- https://classic.yarnpkg.com/blog/2017/08/02/introducing-workspaces/

## License

The MIT license.
