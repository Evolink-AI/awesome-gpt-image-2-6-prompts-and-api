# GPT Image 2.6 — 最新提示词案例

[← 全部 265 条提示词](../../README_zh-CN.md)

十五条完整公开提示词，包括两个官方编辑示例和十三条创作者提示词，涵盖动画、编辑、海报、人像和旅行摄影。原有 250 个 GPT Image 2.5 案例保留原编号。

## 目录

  - [案例 251: 白宫环绕动画](#gpt-image-2-6-case-251)
  - [案例 252: 保留场景的花朵移除](#gpt-image-2-6-case-252)
  - [案例 253: 雪夜广告牌编辑](#gpt-image-2-6-case-253)
  - [案例 254: 持茶人像版本对比](#gpt-image-2-6-case-254)
  - [案例 255: 巴洛克冬日画框海报](#gpt-image-2-6-case-255)
  - [案例 256: 清爽角色拉伸动画](#gpt-image-2-6-case-256)
  - [案例 257: 角色吃饭表情动图](#gpt-image-2-6-case-257)
  - [案例 258: 圈选角色圣诞编辑](#gpt-image-2-6-case-258)
  - [案例 259: 角色眨眼轻晃动画](#gpt-image-2-6-case-259)
  - [案例 260: 循环动漫万花筒动画](#gpt-image-2-6-case-260)
  - [案例 261: 户外运动杂志封面](#gpt-image-2-6-case-261)
  - [案例 262: 怀旧地标街景摄影](#gpt-image-2-6-case-262)
  - [案例 263: 电影感街头时装肖像](#gpt-image-2-6-case-263)
  - [案例 264: 环形灯参考时装肖像](#gpt-image-2-6-case-264)
  - [案例 265: 立冬宋式艺术封面](#gpt-image-2-6-case-265)

<a id="gpt-image-2-6-case-251"></a>
### 案例 251: [白宫环绕动画](https://x.com/nima2qisi2/status/2118295936606798006) (作者 [@nima2qisi2](https://x.com/nima2qisi2))

**输入:** 公开提示词未要求提供参考图。

创作者要求生成 GIF。X 以 MP4 提供这段动画，点击预览图可播放原始动画。只有白宫片段与公开提示词相符；同一帖子中的自由女神像及故宫片段未收录。这段合成环绕动画不是实拍纪录，也不代表建筑几何已获验证。

| 输出 |
| --- |
| 原始来源媒体；参考图与生成结果的角色见各项标注。 |

[![白宫合成环绕动画](https://pub-62cf7640cd0f4066b60933bd2e9b85ef.r2.dev/github-repo-media/awesome-gpt-image-2-5-prompts/assets/gpt-image-2-6/2118295303778615296.jpg)](https://pub-62cf7640cd0f4066b60933bd2e9b85ef.r2.dev/github-repo-media/awesome-gpt-image-2-5-prompts/assets/gpt-image-2-6/2118295303778615296.mp4)

[播放创作者的环绕动画](https://pub-62cf7640cd0f4066b60933bd2e9b85ef.r2.dev/github-repo-media/awesome-gpt-image-2-5-prompts/assets/gpt-image-2-6/2118295303778615296.mp4)

**提示词:**

```
帮我做一个真实白宫外观的360°环绕模仿无人机拍摄，要真实还原建筑环境的实际外观情况，做成gif
```

---

<a id="gpt-image-2-6-case-252"></a>
### 案例 252: [保留场景的花朵移除](https://developers.openai.com/api/docs/guides/image-prompting#remove-an-object) (作者 [@OpenAI](https://developers.openai.com))

**输入:** 使用下方展示的参考图。

官方编辑示例。请使用所附参考照片。两个公开结果放在一起展示；这是作例，并非重复测量的基准测试。

| 输出 |
| --- |
| 原始来源媒体；参考图与生成结果的角色见各项标注。 |

<table>
<tr><td colspan="2"><strong>参考图</strong><br><img src="https://pub-62cf7640cd0f4066b60933bd2e9b85ef.r2.dev/github-repo-media/awesome-gpt-image-2-5-prompts/assets/gpt-image-2-6/man-with-blue-hat.webp" width="360" alt="参考照片：手持花朵的男子"></td></tr>
<tr><td width="50%" valign="top"><strong>GPT Image 2.6 Flare</strong><br><img src="https://pub-62cf7640cd0f4066b60933bd2e9b85ef.r2.dev/github-repo-media/awesome-gpt-image-2-5-prompts/assets/gpt-image-2-6/man-with-no-flower-gpt-image-2-6-flare.webp" width="360" alt="保留场景的花朵移除 — GPT Image 2.6 Flare"></td><td width="50%" valign="top"><strong>GPT Image 2.6 Sunburst</strong><br><img src="https://pub-62cf7640cd0f4066b60933bd2e9b85ef.r2.dev/github-repo-media/awesome-gpt-image-2-5-prompts/assets/gpt-image-2-6/man-with-no-flower-gpt-image-2-6-sunburst.webp" width="360" alt="保留场景的花朵移除 — GPT Image 2.6 Sunburst"></td></tr>
</table>

**提示词:**

```
Remove the flower from man's hand. Do not change anything else.
```

---

<a id="gpt-image-2-6-case-253"></a>
### 案例 253: [雪夜广告牌编辑](https://developers.openai.com/api/docs/guides/image-prompting#change-one-condition) (作者 [@OpenAI](https://developers.openai.com))

**输入:** 使用下方展示的参考图。

这是后续编辑步骤的完整提示词，并非最初生成广告牌的提示词。每个模型分别使用对应的日落广告牌图作为输入。各模型的输入与输出并排展示。

| 输出 |
| --- |
| 原始来源媒体；参考图与生成结果的角色见各项标注。 |

<table>
<tr><td width="50%" valign="top"><strong>Flare 输入</strong><br><img src="https://pub-62cf7640cd0f4066b60933bd2e9b85ef.r2.dev/github-repo-media/awesome-gpt-image-2-5-prompts/assets/gpt-image-2-6/billboard-gpt-image-2-6-flare.webp" width="360" alt="雪夜广告牌编辑 — Flare 输入"></td><td width="50%" valign="top"><strong>Flare 冬季输出</strong><br><img src="https://pub-62cf7640cd0f4066b60933bd2e9b85ef.r2.dev/github-repo-media/awesome-gpt-image-2-5-prompts/assets/gpt-image-2-6/billboard-winter-gpt-image-2-6-flare.webp" width="360" alt="雪夜广告牌编辑 — Flare 冬季输出"></td></tr>
<tr><td width="50%" valign="top"><strong>Sunburst 输入</strong><br><img src="https://pub-62cf7640cd0f4066b60933bd2e9b85ef.r2.dev/github-repo-media/awesome-gpt-image-2-5-prompts/assets/gpt-image-2-6/billboard-gpt-image-2-6-sunburst.webp" width="360" alt="雪夜广告牌编辑 — Sunburst 输入"></td><td width="50%" valign="top"><strong>Sunburst 冬季输出</strong><br><img src="https://pub-62cf7640cd0f4066b60933bd2e9b85ef.r2.dev/github-repo-media/awesome-gpt-image-2-5-prompts/assets/gpt-image-2-6/billboard-winter-gpt-image-2-6-sunburst.webp" width="360" alt="雪夜广告牌编辑 — Sunburst 冬季输出"></td></tr>
</table>

**提示词:**

```
Make it look like a winter evening with snowfall.
```

---

<a id="gpt-image-2-6-case-254"></a>
### 案例 254: [持茶人像版本对比](https://x.com/v3rt0x_/status/2118147596891901957) (作者 [@v3rt0x_](https://x.com/v3rt0x_))

**输入:** 公开提示词未要求提供参考图。

创作者将第一张图标为 GPT Image 2.6，第二张图标为 GPT Image 2.5。未披露具体变体、设置或重试次数。这是创作者对比，并非受控基准测试。

| 输出 |
| --- |
| 原始来源媒体；参考图与生成结果的角色见各项标注。 |

<table>
<tr><td width="50%" valign="top"><strong>GPT Image 2.6 — 创作者标注</strong><br><img src="https://pub-62cf7640cd0f4066b60933bd2e9b85ef.r2.dev/github-repo-media/awesome-gpt-image-2-5-prompts/assets/gpt-image-2-6/2118147098709274624.jpg" width="360" alt="持茶人像版本对比 — GPT Image 2.6 — 创作者标注"></td><td width="50%" valign="top"><strong>GPT Image 2.5 — 创作者标注</strong><br><img src="https://pub-62cf7640cd0f4066b60933bd2e9b85ef.r2.dev/github-repo-media/awesome-gpt-image-2-5-prompts/assets/gpt-image-2-6/2118147411746955264.jpg" width="360" alt="持茶人像版本对比 — GPT Image 2.5 — 创作者标注"></td></tr>
</table>

**提示词:**

```
a realistic photo of a woman holding a cup of tea inside her home
```

---

<a id="gpt-image-2-6-case-255"></a>
### 案例 255: [巴洛克冬日画框海报](https://x.com/Goodmanprotocol/status/2118193088128745875) (作者 [@Goodmanprotocol](https://x.com/Goodmanprotocol))

**输入:** 上传一张你有权使用的场景图。来源未单独提供原始输入图。

创作者将这些作品标注为 GPT Image 2.6 输出。两张海报都是生成结果，各自带有小幅参考图缩略图，但未单独提供原始输入图。请上传你有权使用的场景图。具体模型版本、设置和重试次数未公开。

| 输出 | 输出 2 |
| --- | --- |
| <strong>雪人画框海报</strong><br><img src="https://pub-62cf7640cd0f4066b60933bd2e9b85ef.r2.dev/github-repo-media/awesome-gpt-image-2-5-prompts/assets/gpt-image-2-6/2118193058370158592.jpg" width="320" alt="雪人画框海报"> | <strong>冬日村庄画框海报</strong><br><img src="https://pub-62cf7640cd0f4066b60933bd2e9b85ef.r2.dev/github-repo-media/awesome-gpt-image-2-5-prompts/assets/gpt-image-2-6/2118193073935245312.jpg" width="320" alt="冬日村庄画框海报"> |

**提示词:**

```
PREMIUM BAROQUE FRAMED ARTWORK - PHOTOREALISTIC GALLERY POSTER

Use the uploaded image as the sole visual reference. Create a seamless 3:4 vertical fine-art poster.

TOP SECTION (75%): Display the original scene as a beautiful painting inside an ornate antique gold Baroque frame, mounted on a subtly textured plaster wall. Preserve the original scene and its defining details. Select 1–3 prominent elements already present in the image and extend them beyond the frame in realistic 3D, with natural depth, perspective and cast shadows. Do not introduce any new objects, flowers, plants or decorative elements that are not present in the source image. Choose a muted wall color derived from the original image's palette. Match the lighting, atmosphere and time of day of the original scene. Photorealistic rendering with a sophisticated fine-art gallery aesthetic.

BOTTOM SECTION (25%): Continue the same plaster wall and lighting seamlessly. Place a small, clean thumbnail of the original unedited image slightly left of center, without a white border and with a subtle natural shadow. Beside it, add a refined 2–3-word ALL-CAPS serif title and a single-line italic subtitle inspired by the original scene. Keep the typography minimal, elegant and clearly contrasted against the wall.

COMPOSITION & QUALITY: The entire poster must appear as one continuous image. No divider lines, white bands, gaps, separate panels or outer borders. Ensure seamless transitions, balanced spacing, realistic materials, sophisticated typography and premium editorial art direction. Preserve the original subject's identity and visual character without altering the source scene.
```

---

<a id="gpt-image-2-6-case-256"></a>
### 案例 256: [清爽角色拉伸动画](https://x.com/MiraMusic_AI/status/2118168013618987298) (作者 [@MiraMusic_AI](https://x.com/MiraMusic_AI))

**输入:** 准备一张你有权使用的角色参考图。

创作者同时公开了这段完整日文动画提示词、角色设定图和生成动画。请使用你有权使用的角色参考图。具体模型版本、设置和重试次数未公开。X 以 MP4 提供所请求的 GIF，点击动画链接查看动态效果。

| 输入 | 输出 |
| --- | --- |
| <strong>创作者角色设定图</strong><br><img src="https://pub-62cf7640cd0f4066b60933bd2e9b85ef.r2.dev/github-repo-media/awesome-gpt-image-2-5-prompts/assets/gpt-image-2-6/2118167991833759744.jpg" width="320" alt="创作者角色设定图"> | <a href="https://pub-62cf7640cd0f4066b60933bd2e9b85ef.r2.dev/github-repo-media/awesome-gpt-image-2-5-prompts/assets/gpt-image-2-6/2118167499812536321.mp4"><strong>角色拉伸动画预览</strong><br><img src="https://pub-62cf7640cd0f4066b60933bd2e9b85ef.r2.dev/github-repo-media/awesome-gpt-image-2-5-prompts/assets/gpt-image-2-6/2118167499812536321.jpg" width="320" alt="角色拉伸动画预览"></a> |

[播放创作者的角色拉伸动画](https://pub-62cf7640cd0f4066b60933bd2e9b85ef.r2.dev/github-repo-media/awesome-gpt-image-2-5-prompts/assets/gpt-image-2-6/2118167499812536321.mp4)

**提示词:**

```
ストレッチをしているGIFを製作してください。
仕上げはフラットでクリーンに。
複雑な微細テクスチャ、過剰な細密描写、粒状ノイズ、ザラつき、斜めグリッド状の模様なし
```

---

<a id="gpt-image-2-6-case-257"></a>
### 案例 257: [角色吃饭表情动图](https://x.com/Gorden_Sun/status/2118166046175908016) (作者 [@Gorden_Sun](https://x.com/Gorden_Sun))

**输入:** 准备一张你有权使用的角色参考图。

创作者明确说明第一个附件为生成的 GIF，第二个为角色参考图。中文提示词要求在画面上写出“真香！”。请使用你有权使用的角色参考图。具体模型版本、设置和重试次数未公开；X 以 MP4 提供动画。

| 输入 | 输出 |
| --- | --- |
| <strong>创作者角色参考图</strong><br><img src="https://pub-62cf7640cd0f4066b60933bd2e9b85ef.r2.dev/github-repo-media/awesome-gpt-image-2-5-prompts/assets/gpt-image-2-6/2118166009131757568.jpg" width="320" alt="创作者角色参考图"> | <a href="https://pub-62cf7640cd0f4066b60933bd2e9b85ef.r2.dev/github-repo-media/awesome-gpt-image-2-5-prompts/assets/gpt-image-2-6/2118165970133168129.mp4"><strong>吃饭动画预览</strong><br><img src="https://pub-62cf7640cd0f4066b60933bd2e9b85ef.r2.dev/github-repo-media/awesome-gpt-image-2-5-prompts/assets/gpt-image-2-6/2118165970133168129.jpg" width="320" alt="吃饭动画预览"></a> |

[播放创作者的吃饭动画](https://pub-62cf7640cd0f4066b60933bd2e9b85ef.r2.dev/github-repo-media/awesome-gpt-image-2-5-prompts/assets/gpt-image-2-6/2118165970133168129.mp4)

**提示词:**

```
使用这个角色，生成一张GIF图，内容是她吃大白米饭，图片里有文字：真香！
```

---

<a id="gpt-image-2-6-case-258"></a>
### 案例 258: [圈选角色圣诞编辑](https://x.com/IHayato/status/2118151619212890291) (作者 [@IHayato](https://x.com/IHayato))

**输入:** 准备一张用红圈和蓝圈标出待编辑位置的角色图。

这是创作者引用的完整日文后续编辑提示词：在红圈内添加圣诞帽，将蓝圈内的书替换为礼物。来源合成图同时展示带标注输入和编辑结果，未单独提供无标注输入图。请使用你自己标注的角色图。创作者称该编辑由 GPT Image 2.6 完成，未说明具体模型版本。

| 输出 |
| --- |
| <strong>创作者合成图：带标注输入与圣诞编辑</strong><br><img src="https://pub-62cf7640cd0f4066b60933bd2e9b85ef.r2.dev/github-repo-media/awesome-gpt-image-2-5-prompts/assets/gpt-image-2-6/2118151559322419200.jpg" width="640" alt="创作者合成图：带标注输入与圣诞编辑"> |

**提示词:**

```
赤丸にサンタ帽、青丸の本はプレゼントに
```

---

<a id="gpt-image-2-6-case-259"></a>
### 案例 259: [角色眨眼轻晃动画](https://x.com/IHayato/status/2118151619212890291) (作者 [@IHayato](https://x.com/IHayato))

**输入:** 准备一张你有权使用的角色参考图。

这是创作者引用的完整日文后续动画提示词。请准备你有权使用的角色参考图；来源未单独提供这段动画的输入图。同帖还含另一项圣诞编辑及价格图，此处均不作为动画输入。创作者称该结果由 GPT Image 2.6 生成，未说明具体模型版本。X 以 MP4 提供动画。

| 输出 |
| --- |
| <a href="https://pub-62cf7640cd0f4066b60933bd2e9b85ef.r2.dev/github-repo-media/awesome-gpt-image-2-5-prompts/assets/gpt-image-2-6/2118151194552180736.mp4"><strong>角色眨眼动画预览</strong><br><img src="https://pub-62cf7640cd0f4066b60933bd2e9b85ef.r2.dev/github-repo-media/awesome-gpt-image-2-5-prompts/assets/gpt-image-2-6/2118151194552180736.jpg" width="320" alt="角色眨眼动画预览"></a> |

[播放创作者的角色眨眼动画](https://pub-62cf7640cd0f4066b60933bd2e9b85ef.r2.dev/github-repo-media/awesome-gpt-image-2-5-prompts/assets/gpt-image-2-6/2118151194552180736.mp4)

**提示词:**

```
まばたきして、ふわっと揺れて
```

---

<a id="gpt-image-2-6-case-260"></a>
### 案例 260: [循环动漫万花筒动画](https://x.com/aimikoda/status/2118665755994546650) (作者 [@aimikoda](https://x.com/aimikoda))

**输入:** 准备一张你有权使用的角色参考图。

创作者称这段动画由 GPT Image 2.6 生成。原帖展示了动画，未附原始角色参考图。X 以 MP4 格式提供这段 GIF。

| 输出 |
| --- |
| <a href="https://pub-62cf7640cd0f4066b60933bd2e9b85ef.r2.dev/github-repo-media/awesome-gpt-image-2-5-prompts/assets/gpt-image-2-6/2118665679846993920.mp4"><strong>动漫万花筒动画预览</strong><br><img src="https://pub-62cf7640cd0f4066b60933bd2e9b85ef.r2.dev/github-repo-media/awesome-gpt-image-2-5-prompts/assets/gpt-image-2-6/2118665679846993920.jpg" width="320" alt="动漫万花筒动画预览"></a> |

[播放创作者的万花筒动画](https://pub-62cf7640cd0f4066b60933bd2e9b85ef.r2.dev/github-repo-media/awesome-gpt-image-2-5-prompts/assets/gpt-image-2-6/2118665679846993920.mp4)

**提示词:**

```
Create a seamless looping 1:1 2D anime kaleidoscope animation using the supplied character as the exact identity reference. Preserve the face, hairstyle, anatomy, outfit and visual style.

COMPOSITION: A vibrant, symmetrical kaleidoscope featuring one large central character and four surrounding copies arranged diagonally at different radial angles. Layer overlapping character portraits, decorative Japanese fans, floral motifs and colorful geometric patterns. Fill the entire frame with dense, intricate details extending beyond the edges. No circular frames.

ANIMATION: Keep the overall composition stationary while all five character instances perform independent, expressive anime movements: head tilts, blinking, playful expressions, flowing hair and rhythmic gestures. Use smooth hand-drawn animation with crisp linework, cel shading and lively secondary motion.

LOOP: All movements return naturally to their initial poses for a perfectly seamless infinite loop.

No text, logos, subtitles or additional characters.
```

---

<a id="gpt-image-2-6-case-261"></a>
### 案例 261: [户外运动杂志封面](https://x.com/Goodmanprotocol/status/2119083132691615772) (作者 [@Goodmanprotocol](https://x.com/Goodmanprotocol))

**输入:** 指定一项运动、一个主体或一个创意。公开提示词接受文字描述。

创作者展示了单板滑雪和帆船两张杂志封面，均使用大字号排版。

| 输出 | 输出 2 |
| --- | --- |
| <a href="https://pub-62cf7640cd0f4066b60933bd2e9b85ef.r2.dev/github-repo-media/awesome-gpt-image-2-5-prompts/assets/gpt-image-2-6/2119083106296877056.jpg"><img src="https://pub-62cf7640cd0f4066b60933bd2e9b85ef.r2.dev/github-repo-media/awesome-gpt-image-2-5-prompts/assets/gpt-image-2-6/2119083106296877056.jpg" width="120" alt="单板滑雪封面"></a> | <a href="https://pub-62cf7640cd0f4066b60933bd2e9b85ef.r2.dev/github-repo-media/awesome-gpt-image-2-5-prompts/assets/gpt-image-2-6/2119083118611304448.jpg"><img src="https://pub-62cf7640cd0f4066b60933bd2e9b85ef.r2.dev/github-repo-media/awesome-gpt-image-2-5-prompts/assets/gpt-image-2-6/2119083118611304448.jpg" width="120" alt="帆船封面"></a> |

**提示词:**

```
Create a premium, photorealistic editorial magazine poster inspired by high-end outdoor adventure photography, contemporary sports campaigns, and minimalist Swiss graphic design.

CORE CONCEPT: Automatically identify the main subject, activity, environment, and visual characteristics from the provided subject or concept. Transform it into a striking editorial cover that combines dramatic full-frame photography with oversized, bold typography.

PHOTOGRAPHY & COMPOSITION: Capture the subject in an extraordinary, visually dynamic moment. Use professional sports and lifestyle photography, realistic anatomy, precise details, natural textures, dramatic environmental elements, and authentic movement.

The main photograph should occupy the upper and middle sections of the poster. Use an immersive composition with the subject prominently positioned and the environment providing visual depth.

TYPOGRAPHIC DESIGN:

- Add an enormous, bold, uppercase headline featuring the main subject or activity.
- Use condensed extra-bold sans-serif typography.
- Position the headline across the lower-middle portion of the poster.
- Allow the subject to overlap and partially obscure the typography, creating an integrated photographic-editorial effect.
- Choose typography colors that contrast beautifully with the photograph.
- Include subtle microtypography, thin horizontal divider lines, and editorial labels.

EDITORIAL DETAILS: Include sophisticated magazine-style elements:

- Small uppercase category label at the top.
- Edition number: EDITION 01.
- Small subtitle describing the activity or environment.
- Minimalist footer branding: VISUAL STUDIES.
- Short editorial tagline: THE ART OF [MAIN SUBJECT].
- Subtle technical coordinates or location details where appropriate.

VISUAL STYLE: Luxury outdoor adventure magazine, contemporary editorial art direction, premium sports photography, cinematic natural lighting, rich realistic colors, crisp details, sophisticated typography, professional graphic design, and carefully balanced negative space.

LAYOUT: Vertical 4:5 poster composition. Clean rectangular layout with subtle rounded corners, carefully aligned typography, strong visual hierarchy, and professional magazine-cover aesthetics.

IMPORTANT: The design must feel like a professionally art-directed magazine cover, not a generic AI-generated image. Ensure all typography is correctly spelled, legible, properly integrated, and visually balanced. Avoid unnecessary text, logos, watermarks, and decorative clutter.
```

---

<a id="gpt-image-2-6-case-262"></a>
### 案例 262: [怀旧地标街景摄影](https://x.com/Naiknelofar788/status/2118968665769197976) (作者 [@Naiknelofar788](https://x.com/Naiknelofar788))

**输入:** 将 [LANDMARK / CITY / COUNTRY] 替换为目的地。

创作者用同一个提示词模板展示了三个不同地标附近的街景。

| 输出 | 输出 2 |
| --- | --- |
| <a href="https://pub-62cf7640cd0f4066b60933bd2e9b85ef.r2.dev/github-repo-media/awesome-gpt-image-2-5-prompts/assets/gpt-image-2-6/2118968646475419648.jpg"><img src="https://pub-62cf7640cd0f4066b60933bd2e9b85ef.r2.dev/github-repo-media/awesome-gpt-image-2-5-prompts/assets/gpt-image-2-6/2118968646475419648.jpg" width="120" alt="圆顶地标附近的街景"></a> | <a href="https://pub-62cf7640cd0f4066b60933bd2e9b85ef.r2.dev/github-repo-media/awesome-gpt-image-2-5-prompts/assets/gpt-image-2-6/2118968646450257920.jpg"><img src="https://pub-62cf7640cd0f4066b60933bd2e9b85ef.r2.dev/github-repo-media/awesome-gpt-image-2-5-prompts/assets/gpt-image-2-6/2118968646450257920.jpg" width="120" alt="埃菲尔铁塔附近的街景"></a> |
| <a href="https://pub-62cf7640cd0f4066b60933bd2e9b85ef.r2.dev/github-repo-media/awesome-gpt-image-2-5-prompts/assets/gpt-image-2-6/2118968646479581184.jpg"><img src="https://pub-62cf7640cd0f4066b60933bd2e9b85ef.r2.dev/github-repo-media/awesome-gpt-image-2-5-prompts/assets/gpt-image-2-6/2118968646479581184.jpg" width="120" alt="塔楼附近的街景"></a> |  |

**提示词:**

```
Create an ultra-realistic cinematic street photography image of [LANDMARK / CITY / COUNTRY], inspired by the nostalgic atmosphere of old Japanese neighbourhoods.

Instead of presenting the landmark as a typical tourist postcard, capture an authentic everyday street corner near the iconic location. Include traditional wooden architecture, weathered shopfronts, hanging fabric signs, glowing red lanterns, vintage bicycles parked along the pavement, handwritten menus, narrow stone walkways, overhead utility pipes and subtle cultural details unique to the destination.

The iconic landmark should be naturally visible in the background or subtly integrated into the street composition, recognizable but not dominating the frame.

Photography style: Premium editorial travel photography, eye-level perspective, candid documentary composition, rich architectural textures, natural imperfections, cinematic shadows, muted earthy tones, warm amber highlights, deep charcoal shadows and subtle film grain.

Mood: Quiet nostalgia, authentic local life, timeless urban beauty, intimate travel journal aesthetic.

Camera: Full-frame DSLR, 35mm lens, natural available light, realistic depth, exceptional detail, photorealistic textures.

Vertical 4:5 composition. No artificial HDR, no exaggerated colours, no cartoon effects, no generic tourist-poster styling.
```

---

<a id="gpt-image-2-6-case-263"></a>
### 案例 263: [电影感街头时装肖像](https://x.com/Goodmanprotocol/status/2118925189329420653) (作者 [@Goodmanprotocol](https://x.com/Goodmanprotocol))

**输入:** 公开提示词未要求提供参考图。

创作者展示了一张戴兜帽的人像特写，背景是虚化的街头人群。

| 输出 |
| --- |
| <a href="https://pub-62cf7640cd0f4066b60933bd2e9b85ef.r2.dev/github-repo-media/awesome-gpt-image-2-5-prompts/assets/gpt-image-2-6/2118925178583572480.jpg"><img src="https://pub-62cf7640cd0f4066b60933bd2e9b85ef.r2.dev/github-repo-media/awesome-gpt-image-2-5-prompts/assets/gpt-image-2-6/2118925178583572480.jpg" width="240" alt="戴兜帽的街头时装人像"></a> |

**提示词:**

```
Cinematic Streetwear Editorial Portrait

Create an ultra-realistic, high-end fashion editorial photograph of a beautiful young European woman in her early 20s, captured in a candid close-up street-style portrait. She has naturally fair skin, delicate facial features, expressive light hazel-green eyes, softly defined lips, and long, voluminous dark brunette hair falling naturally around her face, with a few loose strands crossing her forehead.

Outfit & Styling:
She wears an oversized, washed-black heavyweight hoodie with the hood pulled over her head. The hoodie features a subtle, minimalist embroidered logo on the chest, with a relaxed silhouette and premium cotton texture. Her styling is effortlessly understated, contemporary, and editorial.

Pose & Expression:
Standing still in a crowded urban environment, she looks directly into the camera with a calm, slightly mysterious, emotionally neutral expression. Her head is subtly turned, shoulders relaxed, and hair moves naturally across her face. Capture an authentic, spontaneous street-photography moment.

Environment & Composition:
A softly blurred crowd of people surrounds her, creating layered foreground and background depth. Include out-of-focus figures wearing dark clothing, with warm skin tones and indistinct urban surroundings. Keep the woman perfectly sharp and visually separated from the environment through shallow depth of field.

Lighting & Color Grading:
Natural warm-brunette daylight falling softly across her face, subtle highlights on her skin, gentle shadows beneath the hood, and a cinematic balance of cool charcoal blues and warm earthy skin tones. Muted, desaturated color palette with deep blacks, subtle film grain, and rich tonal contrast.

Camera & Technical Details:
Shot on an 85mm portrait lens at f/1.2, extreme shallow depth of field, precise eye focus, creamy optical bokeh, cinematic subject isolation, natural skin texture, realistic individual hair strands, authentic fabric details, professional full-frame photography, premium fashion campaign aesthetic.

Overall Aesthetic: Luxury streetwear editorial, candid European street photography, understated cinematic mood, photorealistic, sophisticated, atmospheric, and effortlessly fashionable.

Aspect Ratio: 4:5 | Style: Photorealistic Editorial Photography
```

---

<a id="gpt-image-2-6-case-264"></a>
### 案例 264: [环形灯参考时装肖像](https://x.com/Naiknelofar788/status/2118922441032700283) (作者 [@Naiknelofar788](https://x.com/Naiknelofar788))

**输入:** 上传一张你有权使用的面部参考图。交付资料未单独提供原始参考图。

女性人像符合提示词描述的姿势和造型。原帖另有一张男性人像，本案例展示的是女性人像。

| 输出 |
| --- |
| <a href="https://pub-62cf7640cd0f4066b60933bd2e9b85ef.r2.dev/github-repo-media/awesome-gpt-image-2-5-prompts/assets/gpt-image-2-6/2118922432224563201.jpg"><img src="https://pub-62cf7640cd0f4066b60933bd2e9b85ef.r2.dev/github-repo-media/awesome-gpt-image-2-5-prompts/assets/gpt-image-2-6/2118922432224563201.jpg" width="240" alt="环形轮廓光时装人像"></a> |

**提示词:**

```
Create an ultra-photorealistic, premium DSLR-style fashion portrait in 8K Ultra HD, vertical 4:6 aspect ratio, suitable for a FayMas profile. Closely match the reference image’s pose, outfit, accessories, lighting, and background.

FACE IDENTITY:
Use my uploaded original photo as the ONLY facial reference. Preserve my exact recognizable face, natural skin tone, face shape, eyes, nose, lips, jawline, and facial proportions. No face swapping, reshaping, whitening, plastic skin, or excessive beauty filters. Maintain realistic skin texture.

HAIR & ACCESSORIES:
Long, straight black hair in a high ponytail with a few loose strands. Round black-lens sunglasses with thin metallic frames, small stud earrings, black smartwatch, and silver bangle.

OUTFIT:
Oversized navy-blue sweatshirt with black raglan sleeves and a vintage “BROOKLYN — NEW YORK — EST. 1998” eagle graphic. Black distressed cargo jeans with realistic ripped details.

POSE & EXPRESSION:
Three-quarter portrait from head to upper thighs. One arm crossing the waist, the other hand holding the opposite sleeve. Relaxed shoulders, confident posture, head slightly turned sideways, closed lips, and a calm, stylish expression. Anatomically correct hands and fingers.

BACKGROUND & LIGHTING:
Dark charcoal-black studio background with subtle cinematic smoke. A bright white circular ring light behind the head creates a halo effect and soft rim lighting on the hair and shoulders. Professional studio lighting, realistic shadows, sharp focus, balanced contrast, and detailed fabric texture.

QUALITY:
Ultra-photorealistic 8K UHD, professional DSLR photography, crisp details, realistic colors, cinematic contrast, premium fashion aesthetic, vertical composition.

NEGATIVE PROMPT:
Different face, altered identity, distorted facial features, artificial whitening, plastic skin, overexposure, excessive smoothing, cartoon, painting, blur, extra fingers, deformed hands, extra arms, incorrect anatomy, distorted sunglasses, garbled text, low resolution, watermark, unwanted logos.
```

---

<a id="gpt-image-2-6-case-265"></a>
### 案例 265: [立冬宋式艺术封面](https://x.com/DeepBlueX0/status/2118893793797914959) (作者 [@DeepBlueX0](https://x.com/DeepBlueX0))

**输入:** 公开提示词未要求提供参考图。

创作者将第一张标为聊天模式，第二张标为工作模式。这里沿用创作者的模式标签。

| 输出 | 输出 2 |
| --- | --- |
| <a href="https://pub-62cf7640cd0f4066b60933bd2e9b85ef.r2.dev/github-repo-media/awesome-gpt-image-2-5-prompts/assets/gpt-image-2-6/2118893783198924800.jpg"><img src="https://pub-62cf7640cd0f4066b60933bd2e9b85ef.r2.dev/github-repo-media/awesome-gpt-image-2-5-prompts/assets/gpt-image-2-6/2118893783198924800.jpg" width="120" alt="聊天模式"></a> | <a href="https://pub-62cf7640cd0f4066b60933bd2e9b85ef.r2.dev/github-repo-media/awesome-gpt-image-2-5-prompts/assets/gpt-image-2-6/2118893783211548672.jpg"><img src="https://pub-62cf7640cd0f4066b60933bd2e9b85ef.r2.dev/github-repo-media/awesome-gpt-image-2-5-prompts/assets/gpt-image-2-6/2118893783211548672.jpg" width="120" alt="工作模式"></a> |

**提示词:**

```
極簡東方 × 宋式美學 × 時令詩意 × 獨立藝術封面 × 東方自然意境
中國農歷節氣：立冬
視覺主體：根據節氣特徵，選擇3種最具節氣代表性與視覺美感的瓜果蔬菜、動物或自然現象。
```

---
