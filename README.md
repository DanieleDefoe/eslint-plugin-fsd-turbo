# eslint-plugin-abuzar-plugin

eslint plugin for FSD architecture

## Installation

You'll first need to install [ESLint](https://eslint.org/):

```sh
npm i eslint --save-dev
```

Next, install `eslint-plugin-abuzar-plugin`:

```sh
npm install eslint-plugin-abuzar-plugin --save-dev
```

## Usage

In your [configuration file](https://eslint.org/docs/latest/use/configure/configuration-files#configuration-file), import the plugin `eslint-plugin-abuzar-plugin` and add `abuzar-plugin` to the `plugins` key:

```js
import abuzar-plugin from "eslint-plugin-abuzar-plugin";

export default [
    {
        plugins: {
            abuzar-plugin
        }
    }
];
```


Then configure the rules you want to use under the `rules` key.

```js
import abuzar-plugin from "eslint-plugin-abuzar-plugin";

export default [
    {
        plugins: {
            abuzar-plugin
        },
        rules: {
            "abuzar-plugin/rule-name": "warn"
        }
    }
];
```



## Configurations

<!-- begin auto-generated configs list -->
TODO: Run eslint-doc-generator to generate the configs list (or delete this section if no configs are offered).
<!-- end auto-generated configs list -->



## Rules

<!-- begin auto-generated rules list -->
TODO: Run eslint-doc-generator to generate the rules list.
<!-- end auto-generated rules list -->


