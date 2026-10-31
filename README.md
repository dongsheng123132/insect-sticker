# insect-sticker · 全球昆虫贴纸库

昆虫贴纸库：每种一张白边贴纸，附多语言虫名与结构化数据。学 [花叔 huashu-bird-sticker](https://github.com/alchaincyf/huashu-bird-sticker) 的「鸣迹」模式。

> 🚧 **占坑阶段**：数据 schema、许可、样例数据已就位；贴纸尚未生成（筹备中）。昆虫已描述约 100 万种，不能一步全做——**先从全球蝴蝶全物种（约 1.8–2 万种）开始**，再扩甲虫等目。

**English:** Stickers for the world's insect species. Insects (~1M described) can't be done all at once, so we start with the complete butterflies (~18–20k species), then expand. **Early stage: schema, license and samples are live.**

---

## 这是什么

这是「**看昆虫 · 虫迹（Insect Tracks）**」iOS App 的贴纸库：每认出/收藏一种昆虫，就把它的贴纸贴进本子，盖日期地点邮戳。

## 灵感与方法

照抄花叔四步流水线（见他的[长文](https://x.com/AlchainHust/status/2116088319511605472)）：找参考图 → 照着画 → 独立打分审校 → 画不好就重画。参考图不打包，将逐种在 `data/species.json` 溯源。

## 数据 schema

见 [`data/sample.json`](data/sample.json) 与 [`data/README.md`](data/README.md)。

## 目录结构

```
stickers/<Order>/<Family>/<Genus_species>.webp
data/species.json（尚未生成）
data/species.schema.json
data/README.md
LICENSE.md
NOTICE.md
```

## 许可

- 贴纸：**PolyForm Shield 1.0.0** —— 源码/资源公开、可复制分发，但**不是 OSI 开源许可**，有**竞争限制**：禁止做与看昆虫·虫迹竞争的观察/识虫/昆虫图鉴产品。
- 数据（编纂部分）：**MIT**；第三方条款见 [NOTICE.md](NOTICE.md)。

详见 [LICENSE.md](LICENSE.md)。

## Roadmap

- [x] 数据 schema 与许可
- [ ] 首批蝴蝶贴纸小样（100–300 种）跑通流水线
- [ ] 全球蝴蝶全物种（约 1.8–2 万种）
- [ ] 扩展甲虫等目
- [ ] 看昆虫·虫迹 iOS App 上架

## 数据源

- Catalogue of Life（分类）
- GBIF / iNaturalist（跨库 ID、俗名、分布）
- IUCN Red List（保护等级）

## 贡献

发现贴纸错误、分类/虫名有误、或有更好的开放参考图，欢迎提 issue / PR。
