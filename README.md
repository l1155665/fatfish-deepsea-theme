# 大肥鱼 · 深海（fatfish-deepsea）

A deep-sea theme for [Multica](https://multica.ai). Light mode is a sunlit shallow — pale water, foam white, sea-glass teal. Dark mode is the deep sea — indigo night, glowing bubbles, a whale's back in the outline. The whole interface sits behind a layer of frosted water glass, and a chubby blue-haired whale girl in a maid outfit keeps the bottom-right corner of the canvas, always underneath the text.

深海主题：浅色是阳光透进的浅滩，深色是发光气泡的深海，界面像隔着一层磨砂水玻璃。右下角底层驻着穿女仆装的鲸鱼娘，留白处露脸、有字处只有字。

主题作者：**音不绝**

## 安装 / Install

- **商店 / From the store**：Multica → Settings → Appearance → Manage → 安装《大肥鱼 · 深海》（上架后可见）。
- **手动 / Manually**：从 [latest release](https://github.com/l1155665/fatfish-deepsea-theme/releases/latest) 下载 `theme.zip`，在 Settings → Appearance → Import theme 导入。

## 选项 / Options

| 选项 | 默认 | 说明 |
| --- | --- | --- |
| 水景背景 `backdrop` | 开 | 关掉后界面回到不透明实色 |
| 水下生物 `sea-life` | 小鲸鱼巡游 | 小鲸鱼巡游 / 只有气泡 |
| 角色立绘 `figure` | 开 | 右下角底层的女仆装鲸鱼娘与大肥鱼徽章 |
| 立绘存在感 `figure-presence` | 清晰陪伴 | 柔和水印 / 清晰陪伴 / 鲜明主角，各档均保持零遮挡 |
| 水玻璃浓度 `glass-opacity` | 72% | 越低越能看见背后的水与鲸鱼 |
| 磨砂模糊 `glass-blur` | 12px | 0–30px |
| 圆润程度 `corner` | 0.75rem | 鲸鱼要圆一点 |
| 阅读栏宽 `content-max-width` | 68rem | 48–84rem |
| 标题斜体 `h1-italic` | 关 | 正文用衬线体，斜体像手写航海日志 |

## 兼容 / Compatibility

- `apiVersion: 1`，Multica 主题 API（beta）：变量、`data-mc` 锚点与清单字段都可能变。
- 浅色与深色两套配色，全部通过 WCAG AA 对比度。
- 不加载任何网络资源：所有 `url()` 都是本仓库 `assets/` 下的相对路径文件，整个包不超过 1 MB。

## 校验 / Check

```sh
# 在 multica-ai/multica 的检出目录里
pnpm theme:check path/to/fatfish-deepsea-theme
pnpm theme:preview path/to/fatfish-deepsea-theme --out preview
```

## 署名与许可 / Credits & license

「大肥鱼／鲸鱼娘」立绘是社区同人二创，按 **CC BY-NC-SA 4.0（署名 · 非商业 · 相同方式共享）** 使用与再分发。完整的署名链、每个人做了什么、本主题改了什么，见 [CREDITS.md](CREDITS.md)。

整个主题包（CSS、SVG 与立绘）以同一协议发布：**CC BY-NC-SA 4.0**，不可商用。协议全文见 [LICENSE](LICENSE)。

The character illustration is derivative community fan art, used under **CC BY-NC-SA 4.0**. The theme as a whole — CSS, SVGs and the illustration — is distributed under the same license and may not be used commercially. See [CREDITS.md](CREDITS.md) for the full attribution chain and [LICENSE](LICENSE) for the legal code.
