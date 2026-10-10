# 播放器使用说明

> [!WARNING]
> **免责声明**  
> 本工具**不包含任何游戏资源文件**！为了尊重版权并规避法律风险（DMCA），你必须自行提取游戏资源。  
> 📖 **解包参考教程**：[Live2DHub 解包指南](https://live2dhub.com/t/topic/3519)

---

## 📁 资源目录结构

请将提取出的资源文件按照 Unity3D 的 `container` 结构放入 `assets` 文件夹中。**请务必确保路径与下方列表完全一致**：

### 1. 音频文件
* **BGM/SE/VOICE**
  ```text
  assets/advscene/resources/advscene/sound/**.m4a
  ```

### 2. 贴图与 Spine 动画
* **通用场景**
  ```text
  assets/advscene/resources/advscene/texture/**.png
  assets/advscene/resources/advscene/texture/**.atlas
  assets/advscene/resources/advscene/texture/**.prefab
  ```
* **魔物娘TD**
  ```text
  assets/resources/character/**.png
  assets/resources/character/**.atlas
  assets/resources/character/**.prefab
  ```
* **拉莱耶少女队**
  ```text
  assets/assetbundleresources/character/**.png
  assets/assetbundleresources/character/**.atlas
  assets/assetbundleresources/character/**.prefab
  ```

### 3. 数据与脚本
* **游戏索引**：
  ```text
  assets/advscene/scenariochapter/config.chapter.json
  ```
* **剧情脚本**：
  ```text
  assets/advscene/scenarioexcel/**.book.json
  ```

---

## 🌐 本地化说明
如果你想要翻译游戏内容，直接修改 `剧情脚本` 目录下对应的 `**.book.json` 文件。

---

## ⌨️ 快捷键与操作

| 动作 | 快捷键 / 鼠标操作 |
| :--- | :--- |
| **切换快进** | `Ctrl` |
| **切换自动播放** | `Tab` |
| **切换全屏 / 窗口化** | `Alt` + `Enter` |
| **隐藏 / 显示 UI** | `鼠标右键` |
| **画面缩放微调** | `鼠标滚轮` |
| **画面平移微调** | `按住鼠标中键` 拖动 |

---

## 💬 讨论与反馈
* **Telegram 交流群**：[点击加入群组](https://t.me/+wM8U-dHm7ctlMjhl)

---

## 📝 更新日志

- **260813**：小屏幕适配
- **260614**：支持拉莱耶少女队的变异立绘
- **260522**：加入 UI 和静态图的 Tween 动画
- **260401**：加入角色立绘移动、缩放、旋转、改色等常见 Tween 动画
- **260327**：支持拉莱耶少女队的环境音效果
- **260318**：新增支持拉莱耶少女队
- **260224**：加入自动播放功能
- **251211**：允许全屏与窗口化切换，修复小屏幕 UI 偏移问题
- **251026**：魔物娘TD 播放器公开发布
