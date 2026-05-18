# 拼豆-总部 · 技术支持网站（GitHub Pages）

静态页面，风格参考 [NeverSayNo 技术支持](https://aikutaigao123.github.io/neversayno-support/support.html)。

## 部署到 GitHub Pages

### 方式 A：独立仓库（推荐）

1. 在 GitHub 新建仓库，例如 `pingdou-hq-support`
2. 将本目录下所有文件推送到仓库 **根目录**（含 `support.html`、`styles.css`）
3. 打开仓库 **Settings → Pages**
4. **Source** 选 `Deploy from a branch`，Branch 选 `main`，文件夹选 `/ (root)`
5. 保存后访问：
   - `https://aikutaigao123.github.io/pingdou-hq-support/support.html`
   - 或 `https://aikutaigao123.github.io/pingdou-hq-support/`（自动跳转）

### 方式 B：用户/组织站点子路径

若已有 `aikutaigao123.github.io` 仓库，可把本目录内容放到子文件夹 `pingdou-hq-support/` 下。

## App Store Connect 填写

- **技术支持网址**：`https://aikutaigao123.github.io/pingdou-hq-support/support.html`  
  （部署后请换成你的实际 URL）

## 自定义

| 文件 | 说明 |
|------|------|
| `support.html` | FAQ、邮箱、服务时间 |
| `privacy.html` | 隐私摘要（完整版仍在 App 内） |
| `styles.css` | 样式 |

当前邮箱：

- 技术支持：`928322941@qq.com`（与 NeverSayNo 项目一致，可按需修改）
- 版权/社区：`1486125245@qq.com`（与 App 内 `LegalPolicyContent` 一致）

## 本地预览

```bash
cd support-site
python3 -m http.server 8080
# 浏览器打开 http://localhost:8080/support.html
```
