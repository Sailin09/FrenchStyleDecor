# 床幔七图模板 · Van-019 认可版

版本：2026-09-21。用户认可 Van-019 花纹修正后的整套效果，要求作为后续床幔模板，并将该色调用于店铺产品图。认可的是展示逻辑与视觉方向，不等于纤维、尺寸、性能或织纹真实性已得到认证。

## 快速调用

“按 FrenchStyleDecor 的床幔七图模板处理这个新品，沿用 Van-019 的自然白、暖白墙面、旧木色与柔和花园日光。先核对原图花形、花束比例、间距、挂法与下摆；做七张不同用途的正方形图片，核对后添加 Fren.png 水印，同时保留所有无水印版本。”

阅读顺序：本模板 → [店铺色调](../brand/approved-tone-2026-09-21.md) → [参考七图](../products/van-019-template/README.md) → [后处理](post-processing.md)。这是仓库工作模板，可直接用上述口令调用。

## 输入与事实锁定

- 每款提供完整源图、正侧面、挂法、花纹近景、下摆，优先原始清晰照片。
- 记录已确认颜色、材质、尺寸、片数、顶面、配件、护理；缺失事实留待确认，不从生成图推断。
- 原图决定产品；Van-019 参考只决定光线、环境、画面气氛，不得把 Van-019 花型、金属架或绑带套在不同商品上。
- 先描述花形、叶形、纹样方向、单元大小与间隔。用花束相对整片帘高、绑带宽度的比例核对；有实测数据才使用厘米。
- 本款纠错经验：原图是不规则轮廓花朵与叶枝花束，留有轻透空隙；不能被重绘成均匀小雏菊或密集碎花。该描述仅适用于 Van-019，不能成为所有床幔的花型提示词。

## 七张图：一图回答一个购买问题

|编号|用途 / 购买问题|构图与信息|主要检查|
|---|---|---|---|
|01|主图：放在卧室是什么效果？|平视斜前方，完整顶部至下摆，两面和束起开口可见；商品主导，留少量环境|不能俯视、切掉挂法、过多空地板|
|02|中景：束起后如何垂落？|一个转角、束带、自然褶皱和展开布面；近于01|束带位置合理，花纹不能随褶皱任意缩放|
|03|挂法：怎样连接床架？|上部横杆、真实连接与绑带近景|按实物挂法，不自动改成穿杆、挂钩或增加顶布|
|04|花纹：图案如何分布？|展开布面中近景，能看见一个完整花束及相邻间距|不得生成不同花型；AI图标记为细节示意，实物证据用源照片|
|05|垂放：放下后是什么状态？|完整垂放外形、层叠与自然透视|结构/片数由原图支持，不承诺遮光、防蚊、隐私|
|06|下摆：边缘与落地如何？|仅下部近景，边缘、褶皱和地面关系占主体|不能再次生成全景；不得加宽荷叶边或增加装饰|
|07|另一侧整体：侧面的包围关系如何？|平视侧面斜角，长侧面主导，顶部与底边完整；与01改变观察侧/机位|不得与01重复，不用俯视或严格正面替代|

默认七张独立1:1照片，不拼图，不强制文字或放大圆圈。尺寸、包装、包含清单需事实支持后单独补充。主图和细节图的光线、色温、房间语言一致；结构性差异优先服从原产品。

## 可复用生成提示词

先填写 PRODUCT_LOCK 和 SHOT，不直接使用未填占位符。将原始商品照片作为主要参考、认可场景作为最后一张风格参考，明确每张参考的职责。

```text
Edit the original product references into one square photorealistic product scene.
PRODUCT_LOCK: [actual product color; motif shape, direction, relative scale and spacing; fabric transparency; attachment method; panel/opening/top structure; edge and hem from this SKU's original photos].
Preserve the actual product. Do not borrow pattern or construction from the room reference. Preserve motif size relative to the full hanging panel and the original spacing; do not replace flowers with generic daisies, invent embroidery, or increase pattern density.
ROOM_AND_LIGHT: Romantic French cottage home, warm-white plaster, gently aged natural oak, soft garden daylight, calm neutral shadows, subtly warm environmental reflections. Keep the confirmed product color faithful. For white products use luminous natural white with visible detail, not yellow beige, icy blue, or clipped fluorescent white. Restrained greenery, relaxed bedding, believable lived-in atmosphere; textile is the focal point.
SHOT: [one specific slot's camera, framing and purpose from the seven-shot table].
No top-down overall view, fused furniture, distorted frames, excessive props, giant bouquets, sepia filter, repeated composition or text. Source photographs govern product truth; the final reference governs atmosphere only.
```

## 审核与交付

1. 先做01，对照原图检查花形、相对大小和疏密，再扩展其余槽位。好看不能替代商品一致性。
2. 逐张检查色彩、挂法、顶面、花型、边饰、透明度和床架几何；重点检查03/04/06是否重造织纹。
3. 做七图总览，确认用途不同、01与07机位有区别、06确为近景，没有遗漏或重复。
4. 未通过审核的图标记待重做，不算最终上架成品；生成细节仅为 visualization。
5. 经检查后使用原 Fren.png 全图水印，2000×2000、sRGB、JPG95、4:4:4；检查实际导出和水印存在。
6. 原图、无水印稿、重做/未采用稿都保留；成品与无水印分目录，禁止自动清理或覆盖。
