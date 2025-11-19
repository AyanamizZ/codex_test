# 项目简介

> "代码是一场静默的诗篇，在黑色终端中迸发光芒。"

这里保存着一些零碎的实验文件，也许会随着时光慢慢扩展。若你愿意，可以随意翻阅这些片段，在字符间寻觅灵感。

## 文艺段落

- **层叠的字符**：仿佛在夜空缓缓盛开的烟花，散落又重聚，描绘出思绪的轨迹。
- **空白的留白**：有时比文字更能诉说一段沉默，把故事交给想象补全。
- **脚注的低语**[^1]：像在纸页边缘悄悄写下的心事，等待知音发现。

```python
# 一个或许无用的小例子
def hello():
    print("Hello, world!")
```

> 当思绪随指尖滑落，代码亦成诗行。

<p align="center">
  <!-- GitHub 会移除 SVG 中的 SMIL 动画，所以这里保留一个静态插图版本 -->
  <svg width="240" height="180" viewBox="0 0 240 180" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="一只骑自行车的鹈鹕">
    <defs>
      <linearGradient id="sky" x1="0%" y1="0%" x2="0%" y2="100%">
        <stop offset="0%" stop-color="#e0f7ff" />
        <stop offset="100%" stop-color="#ffffff" />
      </linearGradient>
      <linearGradient id="beak" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#f9c74f" />
        <stop offset="100%" stop-color="#f9844a" />
      </linearGradient>
    </defs>

    <rect width="240" height="180" fill="url(#sky)" rx="12" />

    <g id="pelican" transform="translate(60 55)">
      <ellipse cx="70" cy="45" rx="45" ry="30" fill="#f2f2f2" stroke="#bdbdbd" stroke-width="2" />
      <circle cx="108" cy="32" r="20" fill="#f5f5f5" stroke="#bdbdbd" stroke-width="2" />
      <circle cx="116" cy="30" r="4" fill="#333" />
      <path d="M124 32 L150 38 L124 44" fill="url(#beak)" stroke="#f9844a" stroke-width="2" />
      <path d="M40 25 Q10 0 15 35" fill="none" stroke="#cddc39" stroke-width="6" stroke-linecap="round" />
      <g id="wing" transform="translate(40 30)">
        <path d="M0 20 Q40 0 70 25 Q40 45 0 20" fill="#dce3ef" stroke="#bdbdbd" stroke-width="2" />
      </g>
      <g id="legs">
        <path d="M45 60 L35 95" stroke="#f9844a" stroke-width="6" stroke-linecap="round" />
        <path d="M80 60 L95 95" stroke="#f9844a" stroke-width="6" stroke-linecap="round" />
      </g>
    </g>

    <g id="bicycle" transform="translate(40 95)">
      <circle cx="30" cy="50" r="30" stroke="#4e342e" stroke-width="5" fill="none" />
      <circle cx="140" cy="50" r="30" stroke="#4e342e" stroke-width="5" fill="none" />
      <path d="M30 50 L90 10 L140 50 L105 50" fill="none" stroke="#6d4c41" stroke-width="5" stroke-linecap="round" />
      <path d="M90 10 L90 -20" stroke="#6d4c41" stroke-width="5" stroke-linecap="round" />
      <path d="M75 -20 L105 -20" stroke="#6d4c41" stroke-width="5" stroke-linecap="round" />
    </g>

    <g id="clouds" fill="#ffffff" opacity="0.8">
      <ellipse cx="30" cy="35" rx="18" ry="10" />
      <ellipse cx="55" cy="35" rx="14" ry="9" />
      <ellipse cx="190" cy="20" rx="22" ry="12" />
      <ellipse cx="212" cy="20" rx="16" ry="10" />
    </g>
  </svg>
</p>

[^1]: 人生海海，代码亦是旅途。
