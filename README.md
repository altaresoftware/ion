It's a fork of Bun for Altare's software.

```bash
ion run index.tsx             # TS and JSX supported out-of-the-box
```

The `ion` command-line tool also implements a test runner, script runner, and Node.js-compatible package manager. Instead of 1,000 node_modules for development, you only need `ion`. Bun's built-in tools are significantly faster than existing options and usable in existing Node.js projects with little to no changes.

```bash
ion test                      # run tests
ion run start                 # run the `start` script in `package.json`
ion install <pkg>             # install a package
ionx cowsay 'Hello, world!'   # execute a package
```
