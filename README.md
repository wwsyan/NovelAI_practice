# NovelAI_practice
NovelAI的学习之路

## ToDoList
- [x] 三段式写作：[链接](https://www.bilibili.com/read/cv19143955)
- [ ] 使用局部重绘，生成指定角色的表情包：[链接](https://www.bilibili.com/read/cv19064710?spm_id_from=333.999.0.0)
- [x] 学会使用LORA：[秋叶的使用教程](https://www.bilibili.com/video/BV1Py4y1d7eJ/?spm_id_from=333.337.search-card.all.click&vd_source=6ac7c4e9791ca84c0eeb7af7f2237d31)
- [x] 测试至少20种不同类型的LORA：[结果](https://github.com/wwsyan/NovelAI_practice/blob/main/LORA%E7%9A%84%E6%B5%8B%E8%AF%95.md)
- [ ] 炼制海拉的LORA模型，有MMD建模：[链接](https://www.aplaybox.com/details/model/3pds00hYubGD)
- [ ] 炼制帕加茜的LORA模型（无MMD建模，素材少）
- [ ] ControlNet Seq 场景生成/人物背景合成：[链接](https://www.bilibili.com/video/BV1zN411F716/?spm_id_from=333.999.0.0&vd_source=6ac7c4e9791ca84c0eeb7af7f2237d31)
- [ ] ControlNet 修手：[链接](https://www.bilibili.com/video/BV1Ej411g7R4/?spm_id_from=333.999.0.0&vd_source=6ac7c4e9791ca84c0eeb7af7f2237d31)

## Tricks
<ul>
<li>SD1.5（c站上大多数模型的基底）的默认尺寸是512×512，最大采样尺寸是768×768，超过该分辨率人体极易崩坏。</li>
</ul>

## 痛点
| 说明 | 解决方法 |
| :---: | :---: |
| 画高分辨率图片时，如1600×900，极易出现多人多腿 | 正负面tag拉满，如单人：正面(1girl, solo1.4)，负面(multiple girls:1.4)|
| 局部重绘时，如何引导输出理想的内容，比如：教室，黑板，女孩——重绘黑板的内容 | 无 | 暂无 |
| 如何画多件衣服，如大衣+毛衣+衬衫 | 无 |

## 常用网站
| 说明 | 链接 |
| :---: | :---: |
| 模型分享与下载 | https://civitai.com/ |
| 图片分享（含模型和tag信息）| https://pixai.art/ |
| tag快速检索 | https://www.prompttool.com/NovelAI |
| 参考图检索 | https://www.pinterest.com/ |
| b站大佬：大江户战士 | [合集-AI绘画相关](https://space.bilibili.com/55123/channel/collectiondetail?sid=1162295) |
