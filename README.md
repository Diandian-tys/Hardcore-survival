# 硬核生存 (Hardcore Survival) — Minecraft Bedrock Addon

[![Minecraft Bedrock](https://img.shields.io/badge/Minecraft%20Bedrock-1.21%2B-brightgreen.svg)](https://www.minecraft.net/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

专为追求极限生存挑战的玩家打造的 **Minecraft 基岩版 (Bedrock Edition)** 硬核模组。加载模组的那一刻起，生存法则将被彻底改写！

---

## ✨ 核心特性 (Features)

### 1. 🌐 局内双语切换 (In-Game Bilingual Support)
- 首次进入世界自动弹出语言选择菜单，支持 **简体中文 (Chinese)** 与 **English (英文)**。
- 游戏中随时在聊天栏发送 `!lang` 或 `!语言` 即可重新打开语言切换面板。

### 2. ❤️ 极限残血压制 (2-Heart Health Cap)
- 玩家原本的 10 颗心（20 点生命值）在安装模组后会被**强制锁定为 2 颗心（4 点生命值）**。
- 任何生命提升或伤害吸收效果均会被自动清除，容错率极低，每一次受击都可能致命。

### 3. 🌙 黑夜梦魇级怪物强化 (Nighttime Mob Escalation)
- 每当夜幕降临（游戏时间 `13000` ~ `23000`）：
  - **常规难度下（和平 / 简单 / 普通）**：所有丧尸（Zombie）与骷髅小白（Skeleton）将被强制拉升至**困难模式强度**（力量 II、速度 I、抗性提升 I，并自动配备铁质装备）。
  - **困难难度下（Hard）**：怪物将突破原版上限，进入**【超困难·炼狱状态】**（力量 IV、速度 II、抗性提升 II、防火，并配备钻石/铁质护甲与钻石剑）！

### 4. 🌊 水中「抽筋」致命机制 (Water Cramp Mechanic)
- 当玩家潜入水下或处于溺水耗氧状态时，有极高概率触发**【抽筋 (Cramp)】**状态！
- **抽筋效果**：
  - 叠加极强缓慢（无法游动）、挖掘疲劳、虚弱与反胃药水效果。
  - 玩家无法向上游出水面，只能在水底无力扑腾并持续下沉，极易直接溺亡！

---

## 📦 安装方法 (Installation)

1. 下载本仓库发布包中的 `HardcoreSurvival.mcaddon`（或直接上传整个解压目录至 GitHub 仓库）。
2. 双击 `HardcoreSurvival.mcaddon` 自动导入至 Minecraft 基岩版。
3. 创建或编辑世界：
   - 在 **行为包 (Behavior Packs)** 中激活 **硬核生存 (Hardcore Survival)**。
   - 在 **资源包 (Resource Packs)** 中确认已同步激活。
   - 开启世界设置中的 **「测试版 API (Beta APIs)」** 实验性玩法（用于运行 Script API 逻辑）。

---

## 📄 开源协议 (License)

本项目基于 [MIT License](LICENSE) 开源，欢迎自由修改、分发与二次创作。
