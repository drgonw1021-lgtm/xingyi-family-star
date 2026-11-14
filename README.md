# 星裔 · Xingyi — Family Star Map

一个家族是一片宇宙。每个人是一颗星，一次婚姻把两片星云接起来。

「星裔」是一个**单文件、离线运行**的家族星图工具：双击 HTML 就能用，不需要服务器、不需要账号。它把族谱画成一片会在缓慢自转的星空，你点任意一颗星，就能看到 TA 和你是什么关系。

> One family is a universe. Every person is a star; a marriage joins two nebulae.
> Xingyi is a single-file, offline family star map — open the HTML and it runs. No server, no account.

---

## 功能 / Features

| 中文 | English |
| --- | --- |
| Canvas 绘制的伪 3D 星图，整片星云缓慢自转 | A pseudo-3D star map drawn on Canvas, slowly rotating |
| 两种布局：**辐射**（按亲疏一圈一圈）与**族谱**（按辈分分层） | Two layouts: **radial** (rings by closeness) and **tree** (layered by generation) |
| 以「观看人」为中心——换一个人看，整张网按他的眼睛重排，称谓也跟着变 | Centered on a viewer — switch the viewer and the whole web, terms included, is recalculated |
| 全连接：能连的都连上，点一条线就能读到两人之间的称谓 | Fully connected: tap a line to read the relation between two people |
| 谱系算法算称谓：爷奶/姥姥姥爷、伯叔姑舅姨、堂表、侄甥、姻亲，按最近共同祖先与代数推导 | Kinship terms derived from the nearest common ancestor and generational distance |
| 十色调色板，混色血缘：两家结合后的子孙继承混色 | Ten-colour palette with blended bloodlines for the children of two families |
| 添人时先查重：同一位置同名的人只确认一次，不会重复长星 | Duplicate check while adding: same name in the same spot is confirmed once |
| 疑似同一人可一键合并：信息更全的一方当主，关系自动改指 | One-tap merge for suspected duplicates, keeping the fuller record |
| 分享码：一串文本装下整张星图，离线也能交给家人 | Share code: the whole map in one string, works offline |
| 邀请卡：导出 PNG，卡上留着一颗具体的「暗星」当理由 | Invite card exported as PNG, with one concrete unlit star as the reason |
| 个人资料可见性：家族可见 / 仅血缘 / 仅本人 | Profile visibility: family / bloodline / only me |
| 中英双语，右上角一键切换 | Chinese and English, one-tap switch |

## 运行 / Run

```text
直接用浏览器打开 Xingyi-Family-Star.html
```

- 纯前端，无构建步骤，无外部依赖。
- 数据存在浏览器 `localStorage`（键 `xingyi.v3`）。
- 「更多 → 导出全量数据」可导出 JSON；换设备时用「导入数据」恢复。

## 数据与隐私 / Data & privacy

- 所有数据只存在你自己的浏览器里。
- 没有任何网络请求，不上传、不统计、不埋点。
- 唯一的对外动作是你主动点「保存这张卡」导出一张 PNG。

## 已知限制 / Known limits

- 没有后端：多人共同补星需要另配服务（本仓库只含单机版）。
- 生年缺失时长幼无法判定，称谓降级为「兄弟／姐妹」。
- 面向桌面浏览器；移动端只做了基础适配。

## 许可 / License

MIT，见 [LICENSE](LICENSE)。

## 名字 / Name

「星裔」= 星辰的后裔。家族的每一代，都是上一片星云里落下来的一颗。
