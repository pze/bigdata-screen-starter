# bigdata-starter

## dev 本地开发环境搭建

```
npm install
make
```

然后访问终端上提示的地址，比如 http://localhost:1234

## build 构建生产环境文件

```
make build
```

## QA

2. 如何添加页面?

参考 `package.json` 里面的 `targets`。

1. 构建报错

```
rm -rf dist
```

再试试。
