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

<svg width="320" height="180" viewBox="0 0 320 180" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="骑着自行车的鹈鹕">
  <style>
    .wheel { stroke: #222; stroke-width: 4; fill: none; }
    .pedal { stroke: #f8a100; stroke-width: 4; }
    .leg { stroke: #f1c27d; stroke-width: 5; stroke-linecap: round; }
    .wing { fill: #f2f2f2; stroke: #c4c4c4; stroke-width: 2; }
    .body { fill: #ffffff; stroke: #c4c4c4; stroke-width: 2; }
    .beak { fill: #f8a100; stroke: #c97200; stroke-width: 2; }
    .eye { fill: #111; }
    .pedal-group { transform-origin: 170px 105px; animation: pedal 2s linear infinite; }
    .wheel-spin { transform-origin: center; animation: wheel 2s linear infinite; }
    @keyframes pedal { from { transform: rotate(0deg); } to { transform: rotate(360deg); } }
    @keyframes wheel { from { transform: rotate(0deg); } to { transform: rotate(-360deg); } }
  </style>
  <rect width="320" height="180" fill="#f9fbff"/>
  <circle class="wheel wheel-spin" cx="110" cy="130" r="35"/>
  <circle class="wheel wheel-spin" cx="210" cy="130" r="35"/>
  <line x1="110" y1="130" x2="170" y2="105" stroke="#333" stroke-width="4"/>
  <line x1="170" y1="105" x2="210" y2="130" stroke="#333" stroke-width="4"/>
  <line x1="170" y1="105" x2="200" y2="75" stroke="#333" stroke-width="4"/>
  <g class="pedal-group">
    <line class="pedal" x1="170" y1="105" x2="190" y2="105"/>
    <circle fill="#f8a100" cx="170" cy="105" r="6"/>
  </g>
  <path class="body" d="M180 65 Q210 60 215 80 Q220 110 180 115 Q140 110 145 80 Q150 60 180 65 Z"/>
  <path class="wing" d="M165 75 Q130 85 125 110 Q150 105 170 95"/>
  <ellipse class="body" cx="210" cy="90" rx="28" ry="18"/>
  <path class="beak" d="M238 85 Q270 80 270 90 Q270 100 238 95 Z"/>
  <circle class="eye" cx="225" cy="82" r="3"/>
  <line class="leg" x1="175" y1="110" x2="150" y2="140"/>
  <line class="leg" x1="185" y1="112" x2="205" y2="140"/>
  <text x="20" y="30" font-size="16" fill="#7a869a">鹈鹕骑着清晨的风</text>
</svg>

[^1]: 人生海海，代码亦是旅途。
