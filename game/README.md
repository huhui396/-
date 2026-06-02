# 《判官归来》第二关 Demo

改编自小说《九年战神归来,前妻哭着求复婚》第二章「寿宴上的不速之客」。
都市复仇 RPG 的**垂直切片**:验证「威慑系统 + 打脸演出」核心玩法。

## 怎么玩

### 方式一:本地直接玩(零配置)
下载 `index.html`,双击用任意浏览器打开即可(手机、电脑都行)。单文件、无外部依赖、无需联网。

### 方式二:在线访问(GitHub Pages)
仓库已配置自动部署工作流 `.github/workflows/deploy-pages.yml`,但 **Pages 需要先手动开启一次**:

1. 打开仓库 **Settings → Pages**
2. **Build and deployment → Source** 选择 **GitHub Actions**
3. 保存后,在 **Actions** 页面重跑 “Deploy Demo to GitHub Pages” 工作流(或往 `game/` 再推一次提交)
4. 部署成功后,访问地址为:`https://huhui396.github.io/-/`

> ⚠️ 注意:本仓库为 **私有(private)**。GitHub Pages 托管私有仓库站点需要 **GitHub Pro / Team / Enterprise** 套餐。
> 若使用免费账号,有两个选择:
> - 将仓库改为 **public**(Settings → General → 最下方 Change visibility),即可免费使用 Pages;
> - 或保持私有,直接用「方式一」本地游玩。

## 玩法说明

- 你扮演归来的林昭,目标是攻破岳父沈国栋的**心理防线**(不靠动手,靠亮底牌)。
- **核心机制:反差值。** 越是隐忍受气,翻盘打脸时奖励越高。
- 试试**全程隐忍 + 二次施压**冲击 **S 评级**;**过早亮身份牌**会被「剧透」,只能拿 C。

## 技术

纯前端单文件(HTML/CSS/JS),无构建步骤。对应剧本见 `../游戏策划/剧本_第二关_寿宴打脸.md`。
