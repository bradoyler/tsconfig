# tsconfig

> Shared [TypeScript config](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html) for my Typescript projects


## Install

```
$ npm install --save-dev @bradoyler/tsconfig
```


## Usage

`tsconfig.json`

```json
{
	"extends": "@bradoyler/tsconfig",
	"compilerOptions": {
		"outDir": "dist",
		"target": "es2018",
		"lib": [
			"es2018"
		]
	}
}
```


## License

MIT © [Brad Oyler](https://bradoyler.com)
