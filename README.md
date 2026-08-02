<div align="center">

<img src="https://trae-api-cn.mchost.guru/api/ide/v1/text_to_image?prompt=Minecraft%20Slimefun%20mod%20banner%2C%20green%20glowing%20slime%20blocks%20and%20slime%20balls%20floating%2C%20cute%20pixel%20art%20green%20slime%20creature%20with%20big%20eyes%2C%20laboratory%20with%20glowing%20green%20potions%20and%20machines%2C%20dark%20forest%20background%2C%20neon%20green%20and%20lime%20color%20scheme%2C%20magical%20science%20atmosphere%2C%20cinematic%20wide%20game%20banner&image_size=landscape_16_9" width="100%"/>

<br/>

<pre>
  ██████╗ ██╗     ██╗███╗   ███╗███████╗    ██╗  ██╗███████╗██╗     ██████╗ ███████╗██████╗
  ██╔════╝ ██║     ██║████╗ ████║██╔════╝    ██║  ██║██╔════╝██║     ██╔══██╗██╔════╝██╔══██╗
  ███████╗ ██║     ██║██╔████╔██║█████╗      ███████║█████╗  ██║     ██████╔╝█████╗  ██████╔╝
  ╚════██║ ██║     ██║██║╚██╔╝██║██╔══╝      ██╔══██║██╔══╝  ██║     ██╔═══╝ ██╔══╝  ██╔══██╗
  ███████║ ███████╗██║██║ ╚═╝ ██║███████╗    ██║  ██║███████╗███████╗██║     ███████╗██║  ██║
  ╚══════╝ ╚══════╝╚═╝╚═╝     ╚═╝╚══════╝    ╚═╝  ╚═╝╚══════╝╚══════╝╚═╝     ╚══════╝╚═╝  ╚═╝
</pre>

<br/>

[![Version](https://img.shields.io/badge/Version-V5.0.0-39ff14?style=for-the-badge&logo=leaflet&logoColor=white)](https://github.com/fxjcangku/slimefun-helper/releases)
[![Minecraft](https://img.shields.io/badge/Minecraft-JsMacros-4caf50?style=for-the-badge&logo=minecraft&logoColor=white)](https://modrinth.com/mod/jsmacros)
[![Language](https://img.shields.io/badge/JavaScript-ES2021-8bc34a?style=for-the-badge&logo=javascript&logoColor=white)](.)
[![License](https://img.shields.io/badge/License-MIT-66bb6a?style=for-the-badge)](LICENSE)
[![Maintained](https://img.shields.io/badge/Maintained-Jerinin-2e7d32?style=for-the-badge&logo=github&logoColor=white)](.)

<br/>

> ### 🟢 基于 JsMacros 的粘液科技全自动化解决方案
> *配方读取 · 材料计算 · 仓储补货 · 自动合成 · 实时 HUD*

<br/>

<!-- 史莱姆装饰 -->
<pre>
  ╭──────────╮     ✦ · ˚ *  · ★  · ˚ ✦     ╭──────────╮     ˚ · ✦ · *  ˚ ·     ╭──────────╮
  │ ●      ● │                              │ ●      ● │                          │  ● .. ●  │
  │  ╰────╯  │  ≺≺  S L I M E F U N  ≻≻    │  ╰────╯  │   ≺≺  H E L P E R ≻≻   │  ╰─╮╭─╯  │
  │  ╭────╮  │                              │  ╭─────╮ │                          │   (  ᗒᗕ) │
  ╰──╯    ╰──╯     · ˚  ★  · ✦  ˚  · *     ╰──╯     ╰─╯     ˚  ✦ · ★  · ˚  *   ╰──────────╯
   [ Slime! ]                               [ Big Slime ]                          [ Baby Slime ]
</pre>

<br/>

</div>

---

<div align="center">

### `🧪 配方读取` &nbsp;·&nbsp; `⚗️ 材料计算` &nbsp;·&nbsp; `📦 仓储补货` &nbsp;·&nbsp; `🤖 自动合成` &nbsp;·&nbsp; `📊 实时HUD`

</div>

---

## 🟢 项目概览

<table>
<tr>
<td width="55%">

**Slimefun Helper** 是 **Jerinin** 维护的 JsMacros 粘液科技全自动化脚本。

从指南批量读取配方、智能分析依赖链、实时扫描仓储、一键自动合成——无需手动逐步操作，让粘液科技的繁琐材料链变得全自动。

</td>
<td width="45%">

```
运行环境   Minecraft + JsMacros
脚本语言   JavaScript
当前版本   V5.0.0
维护者     Jerinin
许可证     MIT
```

</td>
</tr>
</table>

---

## ✨ 功能模块

<table>
<thead>
<tr>
<th width="140">功能</th>
<th>说明</th>
<th width="90">状态</th>
</tr>
</thead>
<tbody>
<tr><td>🟢 <b>配方读取</b></td><td>从粘液科技指南批量读取分类配方，或单独读取当前配方页</td><td align="center"><code>稳定</code></td></tr>
<tr><td>🧮 <b>材料计算</b></td><td>自动分析配方依赖树、对比现有库存、精确列出缺失材料</td><td align="center"><code>稳定</code></td></tr>
<tr><td>🔄 <b>合成队列</b></td><td>根据依赖关系生成最优合成顺序，避免前置材料缺失</td><td align="center"><code>稳定</code></td></tr>
<tr><td>📦 <b>仓储补货</b></td><td>扫描附近所有容器，校验实时槽位后自动取出所需材料</td><td align="center"><code>稳定</code></td></tr>
<tr><td>⚙️ <b>工作站执行</b></td><td>支持配置化的单方块及多方块工作站全自动合成</td><td align="center"><code>稳定</code></td></tr>
<tr><td>🚫 <b>黑名单</b></td><td>排除不希望自动拆分或处理的配方，实时切换无需重启</td><td align="center"><code>稳定</code></td></tr>
<tr><td>📊 <b>HUD 显示</b></td><td>紧凑三栏实时显示制作需求、缺失材料和合成队列</td><td align="center"><code>稳定</code></td></tr>
<tr><td>📖 <b>指南兼容</b></td><td>通过独立配置识别跨版本服务器的指南和菜单物品</td><td align="center"><code>稳定</code></td></tr>
<tr><td>🤚 <b>自动副手</b></td><td>启动时自动寻找背包内指南并安全交换到副手</td><td align="center"><code>稳定</code></td></tr>
<tr><td>🔢 <b>数量快捷操作</b></td><td>配方详情页按 ±1、±32、±64 快速调整制作数量</td><td align="center"><code>稳定</code></td></tr>
<tr><td>🖥️ <b>配置管理器</b></td><td>本地网页可视化编辑并导出工作站配置</td><td align="center"><code>稳定</code></td></tr>
</tbody>
</table>

---

## 🌿 V5.0.0 更新亮点

<details open>
<summary><b>🟢 指南兼容与副手管理</b></summary>
<br/>

- 新增独立 `config/指南识别.json`，可配置指南原版 ID、名称及 NBT 关键词
- 兼容代理或跨版本服务器剥离 Slimefun PDC 后的自定义指南
- 仅在启动时自动将指南交换到副手，运行后可自由换下
- 副手原物品交换回指南原槽位，校验失败时自动还原

</details>

<details>
<summary><b>🧪 配方页面兼容</b></summary>
<br/>

- 菜单导航物品支持按名称关键词识别，降低代理服菜单 ID 丢失影响
- 放宽分类列表和配方详情的固定 Slimefun ID 限制
- 保留页面结构、容器类型和槽位布局校验

</details>

<details>
<summary><b>🔢 数量快捷操作</b></summary>
<br/>

```
数量+1    数量-1
数量+32   数量-32
数量+64   数量-64
      数量归零
```

- 数量变化自动重新计算制作列表、材料计算和 HUD
- HUD 按物品实际堆叠上限显示组数，自动区分 64/16/不可堆叠

</details>

<details>
<summary><b>🐛 问题修复</b></summary>
<br/>

- 修复数量快捷按钮在跨版本物品 ID 环境下无响应
- 修复黑名单操作后按钮状态不能实时切换
- 修复脚本运行期间持续抢占副手问题
- 修复 HUD 横向铺满屏幕及按钮重复叠加
- 修复重新启动脚本时旧 Draw2D 合成 HUD 残留

</details>

---

## 🟢 安装说明

### 前置：JsMacros

> **本项目不是独立 Mod，必须先安装 JsMacros 才能运行。**

| 资源 | 链接 |
|------|------|
| GitHub Releases | [JsMacros/JsMacros](https://github.com/JsMacros/JsMacros/releases) |
| Modrinth | [modrinth.com/mod/jsmacros](https://modrinth.com/mod/jsmacros/versions) |
| 官方文档 | [jsmacros.wagyourtail.xyz](https://jsmacros.wagyourtail.xyz/) |

### 安装步骤

```
1. 确认 JsMacros 已正常安装并可打开宏界面
2. 前往 Release 页面下载 V5.0.0.zip
3. 解压，保留完整目录（不要只复制 .js 文件）
4. 将"粘液助手"文件夹复制到 JsMacros 脚本目录
5. 新建宏 → 类型选 JavaScript → 选择粘液助手 V5.0.0.js
6. 绑定按键 → 进入粘液科技服务器 → 按键运行
7. HUD 显示"制作需求 / 缺失材料 / 合成队列"即启动成功
```

---

## 🤖 使用流程

```
打开指南  →  进入分类页  →  点击「读取配方」
    ↓
查看 HUD 确认材料清单和合成队列
    ↓
点击工作站物品关闭指南
    ↓
脚本自动：扫描仓储 → 补充材料 → 依次合成
```

> 首次使用请用普通材料进行小批量测试。

---

## 📁 项目结构

```
粘液助手/
├─ 粘液助手 V5.0.0.js          主脚本
├─ 使用说明.md
├─ config/
│  ├─ 指南识别.json             指南兼容配置
│  ├─ 配方.json                 读取后保存的配方
│  ├─ 工作站.json               工作站结构配置
│  └─ 黑名单.json               排除配方
├─ logs/                        运行日志（自动生成）
└─ html/
   └─ 工作站配置管理器.html      可视化配置编辑器
```

---

## ⚠️ 使用须知

```
· 不同服务器的 Slimefun 附属、菜单槽位可能不同，请先小批量测试
· 合成前请预留足够背包空间，确认仓储和工作站在交互范围内
· 使用前请确认服务器规则允许客户端脚本
· 遇到问题请提供 logs/slimefun-helper.log 和游戏截图
```

---

## 📄 许可证

本项目使用 [MIT License](LICENSE)，历史贡献归属与许可证信息按仓库 LICENSE 保留。

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a4a1a,50:0d2b0d,100:0a1a0a&height=130&section=footer" width="100%"/>

**Made with 🟢 by Jerinin**

*「粘液科技，交给脚本。」*

</div>
