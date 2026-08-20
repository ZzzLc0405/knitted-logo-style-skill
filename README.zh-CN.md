<div align="center">

# 🧶 毛线针织 Logo Studio
### 一个将 Logo 转译为软质 3D 针织徽章视觉的风格化 Skill

<p>
  <img alt="status" src="https://img.shields.io/badge/status-ready-success">
  <img alt="type" src="https://img.shields.io/badge/type-skill-blue">
  <img alt="style" src="https://img.shields.io/badge/focus-knitted%20logo%20design-8a2be2">
  <img alt="lang" src="https://img.shields.io/badge/language-English%20%7C%20中文-orange">
</p>

**毛线针织 Logo Studio** 是一套用于把上传 Logo 转化为 **毛线 / 羊毛 / 软质 3D 针织徽章视觉** 的 prompt / skill 包。

它重点强调：**Logo 识别度、材质可信度、风格选择能力，以及最终展示质感。**

[English README](./README.md)

</div>

---

## ✨ 这个 Skill 能做什么

- 保留原始 Logo 的核心轮廓与识别性
- 将 Logo 转译为 **柔软、立体、带针脚纹理的毛线徽章**
- 当用户未指定风格时，自动推荐 **2–3 个合适方向**
- 支持 **中国特色增强** 以及其他不同视觉人格
- 让结果更适合用于 **社媒展示、概念样张、设计展示图**

---

## 🧠 核心流程

### 1. 分析 Logo
Skill 会先判断上传 Logo 的：
- 结构类型
- 复杂度
- 配色逻辑
- 品牌气质
- 是字标、图标还是组合标

### 2. 风格推荐
如果用户**没有指定风格**，Skill 不会立刻出图，而是先推荐 **2–3 个最适合的风格方向**，并附上简短说明。

用户随后可以：
- 回复 **1 / 2 / 3** 进行选择
- 直接说自己想要的新风格
- 或者让系统自动选一个最合适的方向

### 3. 最终生成
在确定方向后，生成一张完成度高的 **毛线针织 Logo 概念图**。

---

## 🎨 内置主风格

- **Chinese Contemporary** —— 现代中国风 / 国潮文创方向
- **Minimal Nordic** —— 北欧极简、低饱和、自然纤维感
- **Vintage Collegiate** —— 复古学院 / 校徽 / 毛衣章感觉
- **Soft Cute** —— 更蓬松圆润、更可爱、更适合社媒传播
- **Street Patch** —— 街头布章 / 刺绣贴布 / 潮流感更强
- **Outdoor Craft** —— 户外编织 / 绳结 / 工艺补丁感
- **Luxury Knit** —— 精品针织 / 精致纱线 / 轻奢展示感
- **Future Knit** —— 柔软科技感 / 未来针织 / 结构更利落

---

## 🇨🇳 中国特色增强

这个 Skill 可以在 **不破坏 Logo 主体识别度** 的前提下，增加更克制、更高级的中国特色。

可用方向包括：
- 祥云纹
- 如意纹
- 微妙结饰
- 印章感点缀
- 金线细节
- 朱砂红、宫墙红、玉石绿、竹青、靛蓝、米白、鎏金等辅助色

目标是让画面更像一枚 **现代国潮文创针织徽章**，而不是一张堆满符号的节庆海报。

---

## 📁 仓库结构

```text
knitted-logo-style-skill/
├─ skill.md
├─ README.md
├─ README.zh-CN.md
├─ LICENSE.md
├─ COMMERCIAL-LICENSE.md
└─ assets/
   └─ examples/
      ├─ case-1.png
      ├─ case-2.png
      ├─ case-3.png
      ├─ case-4.png
      ├─ case-5.png
      └─ case-6.png
```

---

## 🖼 示例图占位

> 你可以把自己的成品图直接替换到 `assets/examples/` 目录中，并保留相同文件名，这样 README 中的展示位会自动生效。

<p align="center">
  <img src="./assets/examples/case-1.png" width="32%" alt="示例图 1">
  <img src="./assets/examples/case-9.png" width="32%" alt="示例图 2">
  <img src="./assets/examples/case-3.png" width="32%" alt="示例图 3">
  <br>
  <img src="./assets/examples/case-4.png" width="32%" alt="示例图 4">
  <img src="./assets/examples/case-8.png" width="32%" alt="示例图 5">
  <img src="./assets/examples/case-6.png" width="32%" alt="示例图 6">
</p>

---

## 🚀 建议使用方式

1. 上传 Logo 参考图
2. 如果你已经知道想要什么风格，直接说出来
3. 如果你不确定，就让 Skill 推荐 2–3 个方向
4. 选择一个，或者让系统自动选择
5. 输出最终毛线针织 Logo 视觉图

---

## 📝 说明

- `skill.md`：主规则与生成逻辑
- `LICENSE.md`：默认个人 / 非商业使用协议
- `COMMERCIAL-LICENSE.md`：商业授权说明预留
- `assets/examples/`：6 张示例图展示位

---

## 📜 许可协议

本仓库默认遵循 **[LICENSE.md](./LICENSE.md)** 中的条款。  
若需商业使用，请查看 **[COMMERCIAL-LICENSE.md](./COMMERCIAL-LICENSE.md)**。
