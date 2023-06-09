# Tauri + Vue 3 + TypeScript

This template should help get you started developing with Vue 3 and TypeScript in Vite. The template uses Vue 3 `<script setup>` SFCs, check out the [script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup) to learn more.

## Recommended IDE Setup

- [VS Code](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) + [Tauri](https://marketplace.visualstudio.com/items?itemName=tauri-apps.tauri-vscode) + [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer)

## Type Support For `.vue` Imports in TS

Since TypeScript cannot handle type information for `.vue` imports, they are shimmed to be a generic Vue component type by default. In most cases this is fine if you don't really care about component prop types outside of templates. However, if you wish to get actual prop types in `.vue` imports (for example to get props validation when using manual `h(...)` calls), you can enable Volar's Take Over mode by following these steps:

1. Run `Extensions: Show Built-in Extensions` from VS Code's command palette, look for `TypeScript and JavaScript Language Features`, then right click and select `Disable (Workspace)`. By default, Take Over mode will enable itself if the default TypeScript extension is disabled.
2. Reload the VS Code window by running `Developer: Reload Window` from the command palette.

You can learn more about Take Over mode [here](https://github.com/johnsoncodehk/volar/discussions/471).


# Usage
- change all `tauri-starter` to your project name
- chang `HomyeeKing` to your name


# Credits
- [Tarui](https://github.com/tauri-apps/tauri) to build Desktop Applications
- [Vite](https://github.com/vitejs/vite) for instant DX and large ecosystem
- [Vue](https://github.com/vuejs/core) for frontend UI
- [unocss](https://github.com/unocss/unocss) for atomic CSS use and better implement style
- [unplugin-vue-components](https://github.com/antfu/unplugin-vue-components) for auto import Vue Componets in `src/components` folder
- [vueuse](https://github.com/vueuse/vueuse) for quick logic implement
- [unplugin-icons](https://github.com/antfu/unplugin-icons) for access icons as component