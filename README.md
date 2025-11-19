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
  <svg width="320" height="180" viewBox="0 0 320 180" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="一只骑自行车的鹈鹕">
    <defs>
      <linearGradient id="sunset" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#ffd76b" />
        <stop offset="100%" stop-color="#ff9c5a" />
      </linearGradient>
    </defs>
    <rect width="320" height="180" fill="url(#sunset)" rx="12" />
    <circle cx="60" cy="50" r="24" fill="#fff2b3" opacity="0.8" />
    <g transform="translate(70 100)">
      <circle cx="0" cy="0" r="28" fill="none" stroke="#222" stroke-width="6" />
      <circle cx="110" cy="0" r="28" fill="none" stroke="#222" stroke-width="6" />
      <line x1="0" y1="0" x2="110" y2="0" stroke="#222" stroke-width="6" stroke-linecap="round" />
      <line x1="55" y1="-10" x2="0" y2="0" stroke="#222" stroke-width="5" stroke-linecap="round" />
      <line x1="55" y1="-10" x2="110" y2="0" stroke="#222" stroke-width="5" stroke-linecap="round" />
      <circle cx="55" cy="-10" r="9" fill="#444" />
      <g>
        <line x1="55" y1="-10" x2="15" y2="-40" stroke="#444" stroke-width="5" stroke-linecap="round">
          <animateTransform attributeName="transform" type="rotate" from="0 55 -10" to="360 55 -10" dur="4s" repeatCount="indefinite" />
        </line>
        <line x1="55" y1="-10" x2="95" y2="-40" stroke="#444" stroke-width="5" stroke-linecap="round">
          <animateTransform attributeName="transform" type="rotate" from="360 55 -10" to="0 55 -10" dur="4s" repeatCount="indefinite" />
        </line>
      </g>
    </g>
    <g transform="translate(135 60)">
      <ellipse cx="0" cy="0" rx="36" ry="26" fill="#f0f4ff" stroke="#374151" stroke-width="4" />
      <ellipse cx="-28" cy="-18" rx="18" ry="14" fill="#f0f4ff" stroke="#374151" stroke-width="4" />
      <path d="M -40 -18 Q -60 -10 -34 -2" fill="#fbbb4c" stroke="#c97b1c" stroke-width="3" stroke-linejoin="round" />
      <circle cx="-30" cy="-22" r="4" fill="#111" />
      <path d="M -5 15 Q 5 28 15 12" fill="none" stroke="#374151" stroke-width="5" stroke-linecap="round" />
      <path d="M -5 15 Q -20 35 -10 45" fill="none" stroke="#374151" stroke-width="5" stroke-linecap="round">
        <animate attributeName="d" dur="2s" repeatCount="indefinite" values="M -5 15 Q -20 35 -10 45; M -5 15 Q -25 28 -15 40; M -5 15 Q -20 35 -10 45" />
      </path>
    </g>
  </svg>
</p>

[^1]: 人生海海，代码亦是旅途。
