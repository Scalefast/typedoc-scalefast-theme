## Scalefast Theme for TypeDoc
TypeDoc documentation application theme customized for Scalefast company.

## Install
```
npm i --save-dev typedoc-scalefast-theme
```

## Usage
Add a new option to the typedoc command to specify the package path.
```
npx typedoc --theme ./node_modules/typedoc-scalefast-theme/src
```
Or add the subject in the `typedoc.json` file.
```json
{
  "theme": "./node_modules/typedoc-scalefast-theme/src",
}
```

## Dependencies
* typedoc
* typedoc-plugin-pages
* @types/lunr

## Contributing
We are open to making changes to the theme as long as it fits the company's styles and adjustments that provide flexibility.

If by any chance the default theme created does not work and you want to use something very different, you will have to consider creating another repository and expand the existing one to support several themes.

## License

Copyright (c) 2021 Scalefast.  
Licensed under the GNU General Public License v3.0.
