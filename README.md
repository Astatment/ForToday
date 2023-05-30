# ForToday

统计算法竞赛选手最近 7 天内的解题数量

![image](https://github.com/Zxilly/ForToday/assets/31370133/0a37cf94-f8da-47cc-be3b-664e03ff1164)

## 支持

当前支持以下平台
- [洛谷](https://www.luogu.com.cn/)
- [Codeforces](https://codeforces.com/)
- [NowCoder](https://ac.nowcoder.com/)

> Codeforces 支持获取组织内部 VP 的数据，需要设置 `constants.ts` 中的 `CODEFORCES_GROUP_ID`

## 使用方法

1. 修改 `constants.ts` 中的 `targets`
2. 部署到 `vercel`，同时启动一个 `redis` 实例，并将 `REDIS_URL` 设置为 `redis` 实例的连接地址

## 配置

如果需要配置洛谷的爬取，可以启动后在网页中按 `Ctrl + Q` 后输入自己的洛谷 `Cookie`

## LICENSE

MIT
