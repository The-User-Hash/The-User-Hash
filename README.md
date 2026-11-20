# 技术提案 PPT

> 本提案针对大模型推理场景下的显存成本问题，
> 提出 KV Cache 分层管理方案。
> 已同步提交给深度求索（DeepSeek）与米哈游评估。

---

## 提案内容

- **问题背景**：长上下文推理中 KV Cache 显存占用过高
- **核心方案**：按访问频率分层，热数据留显存、冷数据下沉
- **预期收益**：显存占用下降，单卡可承载并发数提升
- **落地路径**：分三阶段推进，可先在推理服务侧灰度验证

完整 PPT 见本仓库 `提案PPT/` 目录。

---

## 技术方向

- **大模型应用**：推理成本优化、KV Cache 分层策略、上下文管理
- **自动化开发**：Python 脚本、数据处理流水线、文件批量处理
- **移动端**：APP 开发、端侧模型部署

---

## 联系我

### 📬 联系与协作

如果您对本提案感兴趣，或希望深入探讨技术细节，欢迎通过以下方式联系：

| 渠道 | 账号 / ID | 链接 / 备注 |
| :--- | :--- | :--- |
| **📧 邮箱** | `zengjia168_2026@qq.com`/2929828762@qq.com | **首选** (国内响应最快) |
| **📧 备用邮箱** | `zengjia168_2026@outlook.com` | 国际通用 |
| **💬 微信** | `xiangrikuizengjia` | 扫码或搜索添加 |
| **🐧 QQ** | `2929828762` | [点击跳转添加](https://qm.qq.com/q/KeKaFEOfqE) |
| **🚀 飞书** | `user_r9RoV9tcVB` | [点击添加联系人](https://www-user.feishu.cn/invitation/page/add_contact/?token=d55ia924-0e39-4f0d-afe1-a88cf702b7e1&unique_id=0cbaAiJaYWkGziEKAnzYMA==) |
| **🔨 钉钉** | `iu9_40gasz7ly` | 扫码或搜索添加 |

> **注**：微信、QQ、钉钉的二维码图片已附在仓库目录，欢迎扫码交流。

有技术问题或合作意向，欢迎提 Issue 和直接联系。

---

## 📥 文件下载说明

> **⚠️ 网页版无法预览 PPT 和 PDF 内容，请全部下载之后查看。**
>
> GitHub 网页端只能在线显示代码、Markdown 和图片，PPT（.pptx）和 PDF 文件在页面上会提示
> "Sorry about that, but we can't show files that are this big right now" 或
> "Unable to render code block"——**这不是文件损坏，而是网页无法渲染，文件本身完整无损。**
>
> **下载方法：**
> 1. 点击左侧文件列表中的目标文件
> 2. 点击右上角的 **下载图标 ↓**（在 Raw 按钮右侧）
> 3. 下载完成后用本地 Office / PDF 阅读器打开
>
> **建议优先下载 PDF 版本**（2.8 MB，手机可直接打开），PPT 原版为 22.9 MB，需下载后用 PowerPoint 或 WPS 打开。