# 非官方 Niva(next) 类型定义
![npm version](https://img.shields.io/npm/v/%40latedream%2Fniva-types?style=flat-square&labelColor=%23233) ![Niva version](https://img.shields.io/badge/Niva(next)-%3D0.9.x-green?style=flat-square)

因为 [Niva](https://github.com/bramblex/niva) 和 [Niva-next](https://github.com/iYeXin/niva-next) 都还没有官方的类型定义, ~~但是我又急着用~~所以我自己写了一个

## 食用方法
### 安装
用你喜欢的包管理器安装 `@latedream/niva-types`
```sh
pnpm add -D @latedream/niva-types # 比如 pnpm
```

### 引入
引入类型定义有两种方式, 任选其一即可
1. 修改 `tsconfig.json`
```jsonc
{
  "compilerOptions": {
	...,
    "types": [
      "@latedream/niva-types"
	  // "@latedream/niva-types/next" // Niva-next
    ],
	...
  }
}
```
2. 在任意`d.ts`文件中添加以下代码
```ts
// Niva 原版
/// <reference types="@latedream/niva-types" />

// Niva-next
/// <reference types="@latedream/niva-types/next" />
```
