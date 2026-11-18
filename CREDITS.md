# 署名与修改说明 / Credits and changes

本主题包含一份**社区同人二创立绘**，按 CC BY-NC-SA 4.0 协议使用。CC BY 要求署名，BY-NC 要求不可商用，SA 要求以相同协议再分发。下面写清角色是谁的、谁画的、本主题改了什么。

This repository includes **derivative community fan art**, used under CC BY-NC-SA 4.0. Attribution, non-commercial use and share-alike are required. The chain below names the original character, the artists, and the changes made here.

## 角色与立绘 / Character and illustration

| 环节 | 署名 | 链接 |
| --- | --- | --- |
| 原始角色形象 | 上善无形（上善） | — |
| DeepSeek 女仆形象二次设计（本主题使用的原画） | **ZipZipPipe** | https://www.pixiv.net/artworks/148186519 |
| Q 版设定图参考 | YunYueSama | https://github.com/YunYueSama/codex-deepseek-pet |
| 设定图整理 | xiaoweigen | https://github.com/xiaoweigen/deepseek-dafeiyu-assets |

原画为 Pixiv 作品《AI娘化》第 1 页，作者原话：「作为保存用，方便所有人取用，需要标注作者，不可商用」「其中 deepseek 娘形象基于用户：上善 的鲸鱼娘形象……遵循原作者签署的 CC BY-NC-SA 4.0 协议」。

## 本主题所做的修改 / Changes made in this theme

原图是浅灰白底、四周大片留白的单页插画，本主题对 `assets/fatfish-light.webp` 与 `assets/fatfish-dark.webp` 做了：

1. **去底**：去掉浅灰白背景与发丝间的封闭白洞，保留围裙、白袜、荷叶边等属于人物的白色；边缘去白边。
2. **裁留白**：按 alpha 包围盒裁到人物本身。
3. **分深浅两版调色**：深色版压暗偏冷（融入深海），浅色版提亮偏暖（融入浅滩）。
4. **转 WebP**：压缩后两版合计约 128 KB，保证整个主题包不超过 1 MB。

未对人物造型、服装、配色做任何重绘；只做了去底、裁切、轻微调色与格式转换。

其余文件（`theme.css`、`assets/*.svg`）为本主题原创，同样以 CC BY-NC-SA 4.0 发布。

## 许可 / License

**CC BY-NC-SA 4.0** — Attribution-NonCommercial-ShareAlike 4.0 International。协议全文见 [LICENSE](LICENSE)，官方说明见 https://creativecommons.org/licenses/by-nc-sa/4.0/ 。

This theme is licensed **CC BY-NC-SA 4.0**: you must give appropriate credit, may not use it for commercial purposes, and must distribute your contributions under the same license.

## 再分发须知 / If you redistribute

- 保留本文件与 `theme.css` 顶部的署名注释，不要删掉作者链。
- 不要商用（包括卖主题、放进付费产品、用于商业投放）。
- 改了要说明改了什么，并以 CC BY-NC-SA 4.0 发布。

若你代表 Multica 官方或任何商业主体希望以其他方式使用这份立绘，需要另行取得上游权利人（ZipZipPipe 及原始角色权利人）的许可。
