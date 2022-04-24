# typescript-template

This repository contains some boilerplate code to get started with any typescript project.

This is a pretty simple template, using the following packages:

- `prettier`: Code formatting
- `typescript (tsc)`: Transpiling typescript to javascript
- `ts-node`: Running typescript code without having to transpile it

## Using the template

1. Clone the repository
   ```shell
   $ git clone git@github.com:cbyrneee/typescript-template.git
   ```
2. Change the package name, author, and license in `package.json`
   ```json
   {
     "name": "my-package",
     "author": "Your Name",
     "license": "Your License Identifier"
   }
   ```
3. Run your code in `index.ts`!
   ```shell
   $ yarn dev
   ```

## Scripts

- `build`: Transpile typescript to javascript and output it in `./build`
- `start`: Run `./build/index.js`
- `dev`: Run `./src/index.ts` with `ts-node`
- `format`: Formats files that are not in `.gitignore` with `prettier`

## License

[MIT](https://choosealicense.com/licenses/mit/)
