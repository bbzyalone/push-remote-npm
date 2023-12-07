# 这是一个发布测试包

## node运行ts 的库

```
npx ts-node src/index
```
## 使用 tsup 构建工具

```
npm install tsup -D
```

## 安装测试工具
```
npm install -D jest ts-jest @types/jest
```

## 本地测试
创建另一个测试测试项目 并执行 `npm link vue-ts-json-view`# vue-ts-json-view

## 推送至远程
npm run bulid 
npm publish

## 检查远程依赖版本
```
npm outdated
```
