# @keystonejs/demo-project-meetup

## 5.0.1

### Patch Changes

- [`8226eb47`](https://github.com/keystonejs/keystone/commit/8226eb4709ea8ad5773c900eaaa96068d3cb6bad) [#1819](https://github.com/keystonejs/keystone/pull/1819) Thanks [@w01fgang](https://github.com/w01fgang)! - Upgraded `@emotion/core` and `@emotion/styled`.

* [`5595e4c4`](https://github.com/keystonejs/keystone/commit/5595e4c45c618fa7e13a3d91e3ea3892b4f10475) [#1808](https://github.com/keystonejs/keystone/pull/1808) Thanks [@gautamsi](https://github.com/gautamsi)! - Upgraded `react-apollo` and replaced use of `react-apollo-hooks` with `react-apollo`. `react-apollo` has a similar hooks API to `react-apollo-hooks`.
* Updated dependencies [[`45fd7ab8`](https://github.com/keystonejs/keystone/commit/45fd7ab899655364d0071c0d276d188378944ff5), [`8735393e`](https://github.com/keystonejs/keystone/commit/8735393ec7b01dd0491700244e915b4b47c1cc53), [`8226eb47`](https://github.com/keystonejs/keystone/commit/8226eb4709ea8ad5773c900eaaa96068d3cb6bad), [`8226eb47`](https://github.com/keystonejs/keystone/commit/8226eb4709ea8ad5773c900eaaa96068d3cb6bad), [`b0756c65`](https://github.com/keystonejs/keystone/commit/b0756c65525625919c72364d8cefc32d864c7c0e), [`20632bca`](https://github.com/keystonejs/keystone/commit/20632bca495058f2845d36fe95650eede0a9ebdc), [`3138013c`](https://github.com/keystonejs/keystone/commit/3138013c49205bd7f9b05833ae6158ebeb281dc0), [`d132a3c6`](https://github.com/keystonejs/keystone/commit/d132a3c64aec707b98ed9a9ceffee44a98749b0a), [`ba8aef71`](https://github.com/keystonejs/keystone/commit/ba8aef71d1a04f643fb7f7590d7d6d136b1d4eba), [`5595e4c4`](https://github.com/keystonejs/keystone/commit/5595e4c45c618fa7e13a3d91e3ea3892b4f10475), [`b17b50c0`](https://github.com/keystonejs/keystone/commit/b17b50c0783dd246786aad1de41136967ad73b5c), [`479597e0`](https://github.com/keystonejs/keystone/commit/479597e0920cbedf28f76c14a95b564282f2c1d9)]:
  - @keystonejs/keystone@5.1.1
  - @keystonejs/email@5.0.1
  - @keystonejs/app-admin-ui@5.0.2
  - @keystonejs/fields@5.1.0
  - @keystonejs/fields-wysiwyg-tinymce@5.0.1
  - @keystonejs/adapter-mongoose@5.1.1

## 5.0.0

### Major Changes

- [`7b4ed362`](https://github.com/keystonejs/keystone-5/commit/7b4ed3623f5774d7783c39962bfa1ce97938e310) [#1821](https://github.com/keystonejs/keystone-5/pull/1821) Thanks [@jesstelford](https://github.com/jesstelford)! - Release @keystonejs/\* packages (つ＾ ◡ ＾)つ

  - This is the first release of `@keystonejs/*` packages (previously `@keystone-alpha/*`).
  - All packages in the `@keystone-alpha` namespace are now available in the `@keystonejs` namespace, starting at version `5.0.0`.
  - To upgrade your project you must update any `@keystone-alpha/*` dependencies in `package.json` to point to `"@keystonejs/*": "^5.0.0"` and update any `require`/`import` statements in your code.

### Patch Changes

- Updated dependencies [[`7b4ed362`](https://github.com/keystonejs/keystone-5/commit/7b4ed3623f5774d7783c39962bfa1ce97938e310)]:
  - @keystonejs/adapter-mongoose@5.0.0
  - @keystonejs/app-admin-ui@5.0.0
  - @keystonejs/app-graphql@5.0.0
  - @keystonejs/app-next@5.0.0
  - @keystonejs/auth-password@5.0.0
  - @keystonejs/email@5.0.0
  - @keystonejs/fields-wysiwyg-tinymce@5.0.0
  - @keystonejs/fields@5.0.0
  - @keystonejs/file-adapters@5.0.0
  - @keystonejs/keystone@5.0.0
  - @keystonejs/session@5.0.0

# @keystone-alpha/demo-project-meetup

## 0.3.7

### Patch Changes

- Updated dependencies [[`0a36b0f4`](https://github.com/keystonejs/keystone-5/commit/0a36b0f403da73a76106b5e14940a789466b4f94), [`7129c887`](https://github.com/keystonejs/keystone-5/commit/7129c8878a825d961f2772be497dcd5bd6b2b697), [`3bc02545`](https://github.com/keystonejs/keystone-5/commit/3bc025452fb8e6e69790bdbee032ddfdeeb7dabb), [`768420f5`](https://github.com/keystonejs/keystone-5/commit/768420f567c244d57a4e2a3aaafe628ea9813d9d), [`a48281ba`](https://github.com/keystonejs/keystone-5/commit/a48281ba605bf5bebc89fcbb36d3e69c17182eec), [`a8ee0179`](https://github.com/keystonejs/keystone-5/commit/a8ee0179842f790dd3b5d4aae3524793e752ee26), [`effc1f63`](https://github.com/keystonejs/keystone-5/commit/effc1f639d5824720b7a9d82c2ee881d77acb901)]:
  - @keystone-alpha/keystone@16.1.0
  - @keystone-alpha/app-graphql@8.2.1
  - @keystone-alpha/adapter-mongoose@6.0.1
  - @keystone-alpha/app-admin-ui@5.10.3
  - @keystone-alpha/fields@15.0.0
  - @keystone-alpha/auth-password@1.0.6
  - @keystone-alpha/fields-wysiwyg-tinymce@3.0.10

## 0.3.6

### Patch Changes

- Updated dependencies [[`6d7d0df0`](https://github.com/keystonejs/keystone-5/commit/6d7d0df0515c3aa21c7d24db17919ddbb5701ce9)]:
  - @keystone-alpha/adapter-mongoose@6.0.0
  - @keystone-alpha/fields@14.0.0
  - @keystone-alpha/keystone@16.0.0
  - @keystone-alpha/app-admin-ui@5.10.2
  - @keystone-alpha/auth-password@1.0.5
  - @keystone-alpha/fields-wysiwyg-tinymce@3.0.9

## 0.3.5

- Updated dependencies [4e6a574d](https://github.com/keystonejs/keystone-5/commit/4e6a574d):
- Updated dependencies [b96a3a58](https://github.com/keystonejs/keystone-5/commit/b96a3a58):
  - @keystone-alpha/app-admin-ui@5.10.0
  - @keystone-alpha/auth-password@1.0.4
  - @keystone-alpha/fields-wysiwyg-tinymce@3.0.8
  - @keystone-alpha/keystone@15.3.1
  - @keystone-alpha/fields@13.0.0
  - @keystone-alpha/adapter-mongoose@5.0.0

## 0.3.4

- Updated dependencies [d316166e](https://github.com/keystonejs/keystone-5/commit/d316166e):
  - @keystone-alpha/file-adapters@2.0.0

## 0.3.3

- Updated dependencies [42a45bbd](https://github.com/keystonejs/keystone-5/commit/42a45bbd):
  - @keystone-alpha/adapter-mongoose@4.0.7
  - @keystone-alpha/keystone@15.1.0

## 0.3.2

- Updated dependencies [b61289b4](https://github.com/keystonejs/keystone-5/commit/b61289b4):
- Updated dependencies [0bba9f07](https://github.com/keystonejs/keystone-5/commit/0bba9f07):
- Updated dependencies [9ade2b2d](https://github.com/keystonejs/keystone-5/commit/9ade2b2d):
  - @keystone-alpha/adapter-mongoose@4.0.6
  - @keystone-alpha/keystone@15.0.0
  - @keystone-alpha/app-admin-ui@5.8.1
  - @keystone-alpha/auth-password@1.0.2
  - @keystone-alpha/fields-wysiwyg-tinymce@3.0.7
  - @keystone-alpha/fields@12.0.0

## 0.3.1

- Updated dependencies [decf7319](https://github.com/keystonejs/keystone-5/commit/decf7319):
- Updated dependencies [89c0d7e9](https://github.com/keystonejs/keystone-5/commit/89c0d7e9):
- Updated dependencies [89c0d7e9](https://github.com/keystonejs/keystone-5/commit/89c0d7e9):
- Updated dependencies [f8ad0975](https://github.com/keystonejs/keystone-5/commit/f8ad0975):
- Updated dependencies [a8e9378d](https://github.com/keystonejs/keystone-5/commit/a8e9378d):
  - @keystone-alpha/adapter-mongoose@4.0.5
  - @keystone-alpha/keystone@14.0.0
  - @keystone-alpha/app-admin-ui@5.8.0
  - @keystone-alpha/auth-password@1.0.1
  - @keystone-alpha/fields-wysiwyg-tinymce@3.0.6
  - @keystone-alpha/fields@11.0.0
  - @keystone-alpha/app-graphql@8.0.0

## 0.3.0

### Minor Changes

- [79e362c0](https://github.com/keystonejs/keystone-5/commit/79e362c0): update demos to use apollo hooks instead of Query and Mutations.

## 0.2.3

- Updated dependencies [8d0d98c7](https://github.com/keystonejs/keystone-5/commit/8d0d98c7):
  - @keystone-alpha/adapter-mongoose@4.0.4
  - @keystone-alpha/app-graphql@7.0.0
  - @keystone-alpha/keystone@13.0.0

## 0.2.2

### Patch Changes

- [30f6b7eb](https://github.com/keystonejs/keystone-5/commit/30f6b7eb): upgraded `react-toast-notifications` to `2.2.4`. use `useToasts` hook when possible.

## 0.2.1

- Updated dependencies [33001656](https://github.com/keystonejs/keystone-5/commit/33001656):
  - @keystone-alpha/adapter-mongoose@4.0.3
  - @keystone-alpha/keystone@12.0.0

## 0.2.0

### Minor Changes

- [e42fdb4a](https://github.com/keystonejs/keystone-5/commit/e42fdb4a): Makes the password auth strategy its own package.
  Previously: `const { Keystone, PasswordAuthStrategy } = require('@keystone-alpha/keystone');`
  After change: `const { PasswordAuthStrategy } = require('@keystone-alpha/auth-password');`

## 0.1.9

- Updated dependencies [b86f0e26](https://github.com/keystonejs/keystone-5/commit/b86f0e26):
  - @keystone-alpha/adapter-mongoose@4.0.1
  - @keystone-alpha/keystone@10.5.0

## 0.1.8

- Updated dependencies [144e6e86](https://github.com/keystonejs/keystone-5/commit/144e6e86):
  - @keystone-alpha/fields@10.2.0
  - @keystone-alpha/adapter-mongoose@4.0.0
  - @keystone-alpha/keystone@10.0.0

## 0.1.7

### Patch Changes

- [42c3fbc9](https://github.com/keystonejs/keystone-5/commit/42c3fbc9): Upgrade emotion to 10.0.14
- [42c3fbc9](https://github.com/keystonejs/keystone-5/commit/42c3fbc9): Upgrade eslint to 6.0.1
- [42c3fbc9](https://github.com/keystonejs/keystone-5/commit/42c3fbc9): Upgrade express to 4.17.1

- Updated dependencies [42c3fbc9](https://github.com/keystonejs/keystone-5/commit/42c3fbc9):
- Updated dependencies [42c3fbc9](https://github.com/keystonejs/keystone-5/commit/42c3fbc9):
  - @keystone-alpha/adapter-mongoose@3.0.0
  - @keystone-alpha/keystone@9.0.0
  - @keystone-alpha/fields@10.0.0
  - @keystone-alpha/fields-wysiwyg-tinymce@3.0.5
  - @keystone-alpha/app-admin-ui@5.1.0

## 0.1.6

- Updated dependencies [4007f5dd](https://github.com/keystonejs/keystone-5/commit/4007f5dd):
  - @keystone-alpha/adapter-mongoose@2.2.1
  - @keystone-alpha/keystone@8.0.0
  - @keystone-alpha/fields@9.1.0

## 0.1.5

### Patch Changes

- [db212300](https://github.com/keystonejs/keystone-5/commit/db212300):

  Upgrade next to v9 and remove support for next-routes. You should switch to the native support for dynamic routes in next@9

* Updated dependencies [2b094b7f](https://github.com/keystonejs/keystone-5/commit/2b094b7f):
  - @keystone-alpha/app-admin-ui@5.0.4
  - @keystone-alpha/fields-wysiwyg-tinymce@3.0.4
  - @keystone-alpha/fields@9.0.0
  - @keystone-alpha/keystone@7.0.3

## 0.1.4

### Patch Changes

- [aa9d8920](https://github.com/keystonejs/keystone-5/commit/aa9d8920):

  Remove commercial font Nueu Haas Unica from Open Source library

## 0.1.3

- Updated dependencies [b6a9f6b9](https://github.com/keystonejs/keystone-5/commit/b6a9f6b9):
  - @keystone-alpha/app-admin-ui@5.0.3
  - @keystone-alpha/fields-wysiwyg-tinymce@3.0.3
  - @keystone-alpha/keystone@7.0.2
  - @keystone-alpha/fields@8.0.0

## 0.1.2

- Updated dependencies [91fffa1e](https://github.com/keystonejs/keystone-5/commit/91fffa1e):
  - @keystone-alpha/adapter-mongoose@2.2.0
  - @keystone-alpha/keystone@7.0.0

## 0.1.1

### Patch Changes

- [7086b423](https://github.com/keystonejs/keystone-5/commit/7086b423):

  Use latest (un)authenticate mutations

* Updated dependencies [30c1b1e1](https://github.com/keystonejs/keystone-5/commit/30c1b1e1):
* Updated dependencies [1b4cf4e0](https://github.com/keystonejs/keystone-5/commit/1b4cf4e0):
* Updated dependencies [1b4cf4e0](https://github.com/keystonejs/keystone-5/commit/1b4cf4e0):
* Updated dependencies [1b4cf4e0](https://github.com/keystonejs/keystone-5/commit/1b4cf4e0):
  - @keystone-alpha/app-admin-ui@5.0.0
  - @keystone-alpha/fields-wysiwyg-tinymce@3.0.1
  - @keystone-alpha/keystone@6.0.0
  - @keystone-alpha/fields@7.0.0
  - @keystone-alpha/adapter-mongoose@2.1.0
  - @keystone-alpha/app-graphql@6.1.0
  - @keystone-alpha/session@2.0.0

## 0.1.0

### Minor Changes

- [dfcabe6a](https://github.com/keystonejs/keystone-5/commit/dfcabe6a):

  Specify custom servers from within the index.js file

  - Major Changes:
    - The `index.js` export for `admin` must now be exported in the `servers`
      array:
      ```diff
       module.exports = {
         keystone,
      -  admin,
      +  apps: [admin],
       }
      ```
    - The `keystone.prepare()` method (often used within a _Custom Server_
      `server.js`) no longer returns a `server`, it now returns a `middlewares`
      array:
      ```diff
      +const express = require('express');
       const port = 3000;
       keystone.prepare({ port })
      -  .then(async ({ server, keystone: keystoneApp }) => {
      +  .then(async ({ middlewares, keystone: keystoneApp }) => {
           await keystoneApp.connect();
      -    await server.start();
      +    const app = express();
      +    app.use(middlewares);
      +    app.listen(port)
         });
      ```

### Patch Changes

- [92f69b5c](https://github.com/keystonejs/keystone-5/commit/92f69b5c):

  Use KS5 built-in login routes

- [a98bce08](https://github.com/keystonejs/keystone-5/commit/a98bce08):

  Add support for an `onConnect` function to be passed to the Keystone constructor, which is called when all adapters have connected.

- [8494e4cc](https://github.com/keystonejs/keystone-5/commit/8494e4cc):

  `@keystone-alpha/app-admin-ui` no longer accepts a `keystone` paramater in its constructor. It is now automatically passed during the `keystone.prepare()` call.

* Updated dependencies [666e15f5](https://github.com/keystonejs/keystone-5/commit/666e15f5):
* Updated dependencies [b2651279](https://github.com/keystonejs/keystone-5/commit/b2651279):
  - @keystone-alpha/keystone@5.0.0
  - @keystone-alpha/app-admin-ui@4.0.0
  - @keystone-alpha/app-graphql@6.0.0

## 0.0.2

### Patch Changes

- [9b6fec3e](https://github.com/keystonejs/keystone-5/commit/9b6fec3e):

  Remove unnecessary dependency from packages

* Updated dependencies [9a0456ff](https://github.com/keystonejs/keystone-5/commit/9a0456ff):
  - @keystone-alpha/fields@6.1.1
  - @keystone-alpha/adapter-mongoose@2.0.0

## 0.0.1

### Patch Changes

- [0ea974f9](https://github.com/keystonejs/keystone-5/commit/0ea974f9):

  Add to changeset set, so we don't end up in an error state

- [b22d6c16](https://github.com/keystonejs/keystone-5/commit/b22d6c16):

  Remove custom server execution from the CLI.

  The Keystone CLI does not execute custom servers anymore, instead of running `keystone` to start a Keystone instance that has a custom server, run the server file directly with `node`.

  ```diff
  - "start": "keystone",
  + "start": "node server.js"
  ```

- [6f598e83](https://github.com/keystonejs/keystone-5/commit/6f598e83):

  - Add Admin UI static building

* Updated dependencies [9dbed649](https://github.com/keystonejs/keystone-5/commit/9dbed649):
  - @keystone-alpha/admin-ui@3.2.0
  - @keystone-alpha/fields-wysiwyg-tinymce@2.0.0
  - @keystone-alpha/keystone@4.0.0
  - @keystone-alpha/fields@6.0.0