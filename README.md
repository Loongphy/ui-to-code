## Project Overview

This project leverages **Cursor** + **Claude 3.7 Sonnet Thinking** to automate the conversion of UI designs into code. By collecting UI design images from various sources, we use advanced AI technology to transform them into executable frontend code and document the conversion results.

## Project Objectives

- Explore and evaluate Claude 3.7 Sonnet's capabilities in understanding UI designs and generating corresponding code
- Establish a comparative record of different types of UI-to-code conversions

## Conversion Results Log

The following table records the daily UI-to-code conversion results:

| Date | Original UI Design | Generated Code Result | Source |
|------|-------------------|----------------------|--------|
| 2023-03-06 | [Original Design Link] | [Code Implementation Result Link] | [@dingyi](https://x.com/dingyi/status/1897253014806880540) |
| 2023-03-06 | [Original Design Link] | [Code Implementation Result Link] | [@Tanjim38](https://x.com/Tanjim38/status/1897205862974021780) |

## Prompt

```
1:1还原图片中的 UI，写入到 xxx_20250306.html 中。

<前置要求>
- 使用 HTML + TailwindCSS + Alphine.js 实现，所有框架使用 CDN 引入，保证最终产物只有单个 HTML 文件
- 图片可使用 unsplash 填充
- 非文字图形优先使用 CDN 图标替换，如果不合适则使用 SVG 绘制，不可使用特殊字符如 ◆ 代替图形
- 字体通过 google fonts 引入
</前置要求>

<页面要求>
</页面要求>
```
