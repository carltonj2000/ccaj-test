# Scripts Yarn Workspace

Scripts Yarn Workspace

## Global Install

- `npm [un]link` setup a command to run locally without requiring the path

## Yarn Workspace

- packages contains directories with your packages
- package.json contains { "private": true, "workspaces": ["packages/*"] }
- in the root directory run yarn
- now all `packages/*` directories are runnable yarn `<pkg-name>`
- updated code in `packages/*` is automatically run via yarn `<pkg-name>`

# NPM publishing

```bash
npm login
npm version [patch|minor|major]
npm publish --access public
npm i -g @carltonj2000/ccaj
npm uninstall -g @carltonj2000/ccaj
```

# OCLIF

npx oclif multi mynewcli

# DEB

In order for `npx oclif-dev pack:deb` to work need to
comment out the `chmod` and `chown` in the
`vi node_modules/@oclif/dev-cli/lib/commands/pack/deb.js`
file.
