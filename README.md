# 量子沙盒 · Quantum Sandbox

一维薛定谔方程的实时数值模拟，浏览器直接运行。

## 功能
- 四种预设：自由波包、无限深势阱、谐振子、势垒隧穿
- 参数实时调节：势垒高度、波包动量
- 波函数时间演化可视化

## 数值方法
分步傅里叶法（split-step Fourier）：Trotter 分解将传播子拆为动能与势能两部分，分别在动量空间与位置空间对角化处理，每步两次 FFT。网格 512 点，时间步 0.002（无量纲单位）。

## 在线体验
https://uchiha-madala.github.io/quantum-sandbox/
