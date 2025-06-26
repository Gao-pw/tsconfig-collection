### @siroi/tsconfig

这是一套针对不同项目类型的 TypeScript 配置集合。

## 安装

bash

```bash
pnpm add -D @siroi/tsconfig typescript
```

![]()

## 使用方法

### 浏览器端包

对于浏览器端的包，请扩展 `tsconfig.browser-package.json`：

json

```json
{
  "extends": "@siroi/tsconfig/tsconfig.browser-package.json",
  "compilerOptions": {
    "outDir": "./dist",
    "rootDir": "./src"
  }
}
```

![]()

### 浏览器应用

对于浏览器应用，请扩展 `tsconfig.browser-app.json`：

json

```json
{
  "extends": "@siroi/tsconfig/tsconfig.browser-app.json",
  "compilerOptions": {
    "outDir": "./dist",
    "rootDir": "./src"
  }
}
```

![]()

### 服务端包

对于服务端的包，请扩展 `tsconfig.server-package.json`：

json

```json
{
  "extends": "@siroi/tsconfig/tsconfig.server-package.json",
  "compilerOptions": {
    "outDir": "./dist",
    "rootDir": "./src"
  }
}
```

### 服务端应用

对于服务端应用，请扩展 `tsconfig.server-app.json`：

json

```json
{
  "extends": "@siroi/tsconfig/tsconfig.server-app.json",
  "compilerOptions": {
    "outDir": "./dist",
    "rootDir": "./src"
  }
}
```

## 许可证

MIT
