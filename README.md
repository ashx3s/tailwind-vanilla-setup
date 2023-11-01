# tailwind-vanilla-setup

## Install Instructions and debugging tips
**setup npm in your project before adding dependencies. use `npm init -y` to do this**

1. Follow the instructions at [tailwind docs](https://tailwindcss.com/docs/installation) using the "CLI" instructions
2. If you're getting the warning that no classes are being read in source files, [this doc](https://tailwindcss.com/docs/content-configuration) might be useful
3. Check that you've relabeled the "src" and "dist" folders from the example
4. When initializing tailwind with `npx tailwindcss init`, add the `--full` flag to get a more featured config: `npx tailwindcss init --full`
5. Add a `.gitignore` file with `node_modules/` in it **before** you commit
6. Add the `npx tailwindcss -i path -o path --watch` command to your scripts
