# @vill-v/type-as

neta了崩坏3 往世乐土的英杰维尔薇

<!-- automd:badges color="orange" license licenseBranch  bundlephobia packagephobia -->

[![npm version](https://img.shields.io/npm/v/@vill-v/type-as?color=orange)](https://npmjs.com/package/@vill-v/type-as)
[![npm downloads](https://img.shields.io/npm/dm/@vill-v/type-as?color=orange)](https://npm.chart.dev/@vill-v/type-as)
[![bundle size](https://img.shields.io/bundlephobia/minzip/@vill-v/type-as?color=orange)](https://bundlephobia.com/package/@vill-v/type-as)
[![install size](https://badgen.net/packagephobia/install/@vill-v/type-as?color=orange)](https://packagephobia.com/result?p=@vill-v/type-as)
[![license](https://img.shields.io/github/license/vill-v-kit/type-as?color=orange)](https://github.com/vill-v-kit/type-as/blob/true/LICENSE)

<!-- /automd -->

**开发中常用的类型判断**

## 安装
<!-- automd:pm-install -->

```sh
# ✨ Auto-detect
npx nypm install @vill-v/type-as

# npm
npm install @vill-v/type-as

# yarn
yarn add @vill-v/type-as

# pnpm
pnpm install @vill-v/type-as

# bun
bun install @vill-v/type-as

# deno
deno install @vill-v/type-as
```

<!-- /automd -->

## 说明

_只是个人项目，整体较为随便，作为开发途中的经验总结，如有相似的需求，推荐copy或阅读源码，不建议将该包在实际项目中使用_

**如有幸被实际使用在项目内，不胜荣幸**

```ts

const obj = {test: [{test1: 'test2'}]}

getByPath(obj, 'test[0].test1')
// -> test2

const obj1 = {test: [{test1: 'test2'}]}

setByPath(obj1, 'test[0].test1', 'test3')
// obj -> {test: [{test1: 'test3'}]}

const obj2 = {test: [{test1: 'test2'}]}

delByPath(obj2, 'test[0]')

// obj -> {test: []}

const obj3 = {test: [{test1: 'test2'}]}

hasByPath(obj3, 'test[0].test1')
// -> true
```

<!-- automd:contributors author="Colourlessglow" license="MIT" -->

Published under the [MIT](https://github.com/vill-v-kit/type-as/blob/main/LICENSE) license.
Made by [@Colourlessglow](https://github.com/Colourlessglow) and [community](https://github.com/vill-v-kit/type-as/graphs/contributors) 💛
<br><br>
<a href="https://github.com/vill-v-kit/type-as/graphs/contributors">
<img src="https://contrib.rocks/image?repo=vill-v-kit/type-as" />
</a>

<!-- /automd -->

<!-- automd:with-automd -->

---

_🤖 auto updated with [automd](https://automd.unjs.io)_

<!-- /automd -->
