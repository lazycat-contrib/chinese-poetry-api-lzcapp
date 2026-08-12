# 诗泉 LazyCat 应用

将 [palemoky/chinese-poetry-api](https://github.com/palemoky/chinese-poetry-api) 打包为 LazyCat LPK v2 应用。

- 包名：`community.lazycat.app.chinese-poetry-api`
- 上游版本：`0.6.1`
- 镜像模式：Docker Hub 镜像加速与摘要校验
- 发布目标：喵喵商店
- 数据目录：`/lzcapp/var/data` → `/app/data`
- 服务端口：`1279`

常用接口：

- `/api/v1/health`
- `/api/v1/stats`
- `/api/v1/poems/random`
- `/graphql`
