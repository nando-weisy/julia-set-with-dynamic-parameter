# 🌀 动态参数下的 Julia 集（Julia Set）

## 什么是 Julia 集？
- 由初值**z_0**和迭代公式  
  **z₍ₙ₊₁₎ = zₙ² + c**  
  生成，其中 z 从每个像素对应的复数开始迭代。  
- 迭代结果不发散的点构成 Julia 集。  
- **只要改变复数参数 c**，就能得到完全不同的图案。
- 参见博文https://paulbourke.net/fractals/juliaset/以了解更多。

## 本项目做了什么？
把 **c 变成“动态参数”**：让它沿着一条路径慢慢变化 →  
逐帧渲染 → 合成 **流畅的 Julia 集变形 GIF**！

## gif动态展示
![z^4 的 Julia 集动态演示](julia_set(z.^3).gif)
