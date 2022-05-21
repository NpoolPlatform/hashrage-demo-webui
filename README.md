<a href="https://github.com/NpoolPlatform/procyon-webui/actions/workflows/ci.yml"><img src="https://github.com/NpoolPlatform/procyon-webui/workflows/test/badge.svg" alt="build status"></a>

# procyon webui (procyon-webui)

vue3 framework use quasar ui and pinia manage store

## Jenkins

## Jenkins(额外的变量)

Jenkins UI 涉及的环境变量和可选值

| 环境变量                 | 值 | 说明                                                                          |
|:-------------------------|:---|:------------------------------------------------------------------------------|
| CERTIFICATE_CLASS_ISSUER |    | dev: selfsigned-cluster-issuer, prod: \${dns-verdor}-\${account}-cluster-issuer,例如(alidns-default-cluster-issuer) |

## Install the dependencies
```bash
yarn
```

### Start the app in development mode (hot-code reloading, error reporting, etc.)
```bash
quasar dev
```

### Lint the files
```bash
yarn lint
```

### Build the app for production
```bash
quasar build
```

### compatible babel

> yarn add @babel/preset-env babel-jest @babel/core --dev

### practice of unit test link

+ [Vue Test Utils](https://test-utils.vuejs.org/guide/)
+ [Pinia Test](https://pinia.vuejs.org/cookbook/testing.html)
+ [Pinia Test Example](https://github.com/vuejs/pinia/blob/v2/packages/testing/src/testing.spec.ts)
+ [Quasar Test Example](https://github.com/quasarframework/quasar-testing/blob/dev/packages/unit-jest/src/templates/typescript/test/jest/___tests__/MyButton.spec.ts)

### Customize the configuration
See [Configuring quasar.conf.js](https://quasar.dev/quasar-cli/quasar-conf-js).
