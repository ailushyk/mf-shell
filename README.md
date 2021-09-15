mf-shell

## Setup react app

### install dependencies
```shell
# add workspaces
# -w apps/mf-shell -w packages/mf-ui
ni react react-dom 
```
### install dev dependencies
```shell
# typescript
nid typescript @types/react @types/react-dom

# init tsconfig
npx tsc --init

# webpack
nid webpack webpack-cli webpack-dev-server
nid serve html-webpack-plugin clean-webpack-plugin

# babel
nid @babel/core @babel/preset-env @babel/preset-react @babel/preset-typescript @babel/plugin-transform-runtime @babel/runtime
nid babel-loader

# type checking
nid fork-ts-checker-webpack-plugin @types/fork-ts-checker-webpack-plugin
```
