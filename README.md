# 鹈鹕骑自行车 · 模型测试

用同一条提示词测试不同模型生成 2D SVG 动画的效果。所有模型的思考强度都设为「中」。

## 原始提示词

> 创建一个HTML，内容是SVG绘制一个鹈鹕骑自行车的2D动画,写实风格,尽可能精细,不要读取记忆,从头开始做

## 测试结果

| 模型系列 | 测试版本 | HTML 文件 |
| --- | --- | --- |
| Claude | Fable 5.2 | [pelican_bike.html](claude/fable5.2/pelican_bike.html) |
| Gemini | Argon | [pelican_bicycle.html](gemini/argon/pelican_bicycle.html) |
| Gemini | Hydrogen | [pelican-bicycle.html](gemini/hydrogen/pelican-bicycle.html) |
| Gemini | Neon | [pelican-bicycle.html](gemini/neon/pelican-bicycle.html) |
| GPT | 6.2 Astra | [pelican.html](gpt/6.2Astra/pelican.html) |

Claude Opus 5.5 的目录暂时没有 HTML 文件。

## 查看动画

下载或克隆仓库，用浏览器打开表格中对应的 HTML 文件即可播放动画。
