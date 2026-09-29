# 抱枕套七图模板 · FrenchStyleDecor

版本：2026-09-29。适用于 FrenchStyleDecor 店铺的抱枕套 / 靠垫套产品图。模板固定的是展示逻辑、镜头差异和品牌氛围；每款商品的花型、颜色、尺寸、结构和工艺仍以该款原始照片为唯一事实来源。

## 快速调用

“按 FrenchStyleDecor 的抱枕套七图模板处理这个新品。先锁定原图中的底色、织物纹理、花型布局、滚边/包边和实际结构；生成七张用途明确、机位明显不同的正方形产品图。不要把七张做成高相似度变体。先保留无水印版本，审核通过后再按店铺后处理规范添加 Fren.png 水印。”

## 当前参考样板

- [七图总览参考](../products/pillowcase-template/overview.jpg)
- [店铺统一色调](../brand/approved-tone-2026-09-21.md)
- [商品图片通用流程](display-template.md)
- [后处理规范](post-processing.md)

当前参考样板的已确认视觉事实：浅象牙/奶油色织物底，稀疏的灰粉色小玫瑰枝、低饱和橄榄绿/灰绿色叶片和少量浅赭色枝条；正面有细窄的缝制边缘。未提供的背面、拉链、填充物、尺寸、材质成分和护理方式不得从生成图推断。

## 不可改变的产品规则

- 以每款抱枕套的原始照片锁定颜色、底布纹理、花型单元、花朵与叶片的相对大小、间距、方向、四角分布和包边。
- 保持抱枕套原有长宽比例、饱满程度、缝线和边缘轮廓；不得自动变成长方形、加厚滚边、加褶边、流苏、纽扣、蝴蝶结或装饰性拉链。
- 不重新排版、镜像、旋转或密集化花纹；不同角度只改变相机和环境，不改变产品图案。
- 浅色产品保持自然象牙白/奶油白并保留织物细节；不得偏成黄色、灰褐色或过曝纯白。
- 未被原图证实的背面结构、拉链位置、填充物、材质、尺寸、可拆洗性能和功能不进入画面，也不写进文案。
- 生成底图不加文字和水印；水印只在审核后的最终导出步骤添加。无水印原稿和未采用稿都保留。

## 七张图：每张只回答一个购买问题

| 编号 | 用途 / 购买问题 | 机位与构图 | 必须看到 |
|---|---|---|---|
| 01 | 主图：抱枕套正面是什么样？ | 平视正面或轻微 10° 斜角；单个抱枕套完整入镜，置于浅色法式扶手椅或素色软凳；背景克制 | 完整正面花型、四角、缝制边缘、真实饱满度 |
| 02 | 侧面：厚度和立体轮廓如何？ | 45–60° 侧前方；放在窗边长凳或沙发转角；让一条侧边和前片同时可见 | 侧边厚度、转角、包边和自然阴影；不能只重复01 |
| 03 | 平铺：整片图案如何分布？ | 90° 顶视平铺在洗旧木桌/床面；不放大主体，四角尽量完整 | 全部图案比例、花纹间距、面料整体色调 |
| 04 | 细节：花朵和织物纹理如何？ | 近距离 30–45° 微距；只取中央或一组完整花枝，不做全景 | 花瓣、叶片、底布织纹和印花/刺绣边界；不能重画纹样 |
| 05 | 边缘：缝制和包边如何？ | 贴近上角或侧角的局部特写；保留一段直边和一个转角 | 原实物边缘、针脚、包边轮廓；不虚构拉链或背面 |
| 06 | 客厅使用：放在什么家具上？ | 宽幅生活方式图；抱枕套作为焦点放在素色法式沙发/阅读椅，配少量书或茶几物件 | 产品仍占画面主要视觉面积，花型清晰，环境不遮挡 |
| 07 | 卧室使用：床上效果如何？ | 与06明显不同的高位斜角或床尾视角；放在白色/燕麦色床品上，可有一只素色搭配枕 | 与06不同空间和机位；产品完整、比例可信，不能生成第二款花型 |

七张必须是独立的 1:1 图片，不拼图、不做七个几乎相同的正面变体。若只生成三张，优先使用 01、03、06；若需要补图，按 02、04、05、07 的信息差补齐。

## 强制差异规则

每个槽位至少改变两项：相机角度、拍摄距离、家具/空间、摆放方式、信息重点。生成前先写清楚该张要回答的问题；生成后做七图总览，确认没有两张只是轻微裁切或换了道具。角度可以是正面、侧前方、顶视、微距、高位斜角，但产品花型布局必须保持一致。

## 可复用提示词骨架

```text
Create one square photorealistic Etsy product image for a French cottage home-textile shop.
PRODUCT_LOCK: Use the original pillow-cover references as the only authority for the product. Preserve the exact confirmed base color, woven/slub texture, floral motif shapes, motif scale, spacing, direction, edge finish, seams and cushion proportions. Do not redesign or densify the print. Do not invent a zipper, reverse side, filling, fabric composition, size or care claim.
ROOM_AND_LIGHT: Romantic French cottage interior, warm natural daylight, warm-white plaster, aged natural oak, restrained neutral styling, soft realistic shadows. Keep pale ivory/cream products luminous with visible textile detail; do not turn them yellow, beige-brown or blue-white.
SHOT: [insert exactly one slot from the seven-shot table]. Make this camera angle, distance and use case visibly different from the other slots.
Keep the product as the visual focus. No text, watermark, collage, extra motifs, fused furniture, distorted geometry, giant bouquet or repeated composition.
```

## 审核与交付

1. 先用原始产品照片核对 01 的底色、花型布局、比例和边缘，再生成其余槽位。
2. 逐张检查：产品是否完整、图案是否保持、边缘是否真实、角度是否符合该槽位、环境是否遮挡产品。
3. 做七图总览，确认每张用途不同；特别检查 01/02、06/07 不得高相似，04/05 必须是真正细节图。
4. 生成稿只作为视觉展示，不替代尺寸、材质、结构和性能证据。缺失事实留待用户确认。
5. 审核通过后按 [后处理规范](post-processing.md) 导出 2000×2000、sRGB、JPG95、4:4:4；再添加原始 `Fren.png` 水印。
6. 保留原始参考、无水印生成稿、重做稿和最终水印稿；不同版本分目录，不自动删除或覆盖。
