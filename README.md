# vuejs-atom-snippets

Inspired by Sarah Drasner's Vue snippets for VS Code. This is not aiming to be a port of that package. It contains snippets for the things I most commonly use. You can find a detailed breakdown of the snippets below.

## Single File Components

| Command | Output |
| ------- | ------ |
| `vscaffold` | Scaffolds out a full Vue SFC with the options I am most likely to use. Options are ordered according to the Vue styleguide to prevent lint errors. |
| `vbase` | Scaffolds out a Vue SFC with just a name. |
| `vimport` | Imports a local Vue component. `import MyComponent from '@/components/MyComponent'` |
| `vcomponents` | Sets up the `components` option |
| `vfilters` | Sets up the `filters` option |
| `vprops` | Sets up the `props` option |
| `vdata` | Sets up the `data` option |
| `vcomputed` | Sets up the `computed` option |
| `vwatchers` | Sets up the `watch` option |
| `vcreated` | Sets up the `created` hook |
| `vmounted` | Sets up the `mounted` hook |
| `vdestroyed` | Sets up the `destroyed` hook |
| `vmethods` | Sets up the `methods` option |

## Vuex

| Command | Output |
| ------- | ------ |
| `vstore` | A blank slate Vuex store setup. |
| `vmodule` | A full Vuex module, with state, getters, actions, and mutations. |

## License

MIT