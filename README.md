# eslint-config-bundle

Eslint configuration bundle

## How to use

```bash
  npm i -D eslint-config-bundle
```

create an `.eslintrc.yaml`

```yaml
---
env:
  node: true
  es6: true

extends:
  - bundle/env/core.yaml
```

if you want to include `nodejs` rule set

add `node.yaml` to `extends` block

```yaml
  - bundle/env/node.yaml
```

if you have tests with `mocha` and `chai`

add below `mocha.yaml` & `chai.yaml` to `extends` block

```yaml
  - bundle/env/mocha.yaml
  - bundle/env/chai.yaml
```

## Bundled configurations

- [eslint-config-airbnb-base](https://www.npmjs.com/package/eslint-config-airbnb-base)
- [eslint-plugin-dependencies](https://www.npmjs.com/package/eslint-plugin-dependencies)
- [eslint-plugin-import](https://www.npmjs.com/package/eslint-plugin-import)
- [eslint-plugin-node](https://www.npmjs.com/package/eslint-plugin-node)
- [eslint-plugin-promise](https://www.npmjs.com/package/eslint-plugin-promise)
- [eslint-plugin-security](https://www.npmjs.com/package/eslint-plugin-security)
