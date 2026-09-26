# 营销物料与客户触达 Codex Skill

这个 Skill 根据文案、产品照片和参数表制作海报、电子样册或 PPT；在用户明确要求时，通过可用的电脑控制工具发送邮件，或维护 Edge 网页版客户管理表。

## 安装

在 Codex 对话中输入：

> 使用 $skill-installer，从 GitHub 仓库 koanydi/codex-marketing-collateral-and-crm 安装 marketing-collateral-and-crm 目录。

也可以手动把仓库中的 `marketing-collateral-and-crm` 文件夹复制到 `$CODEX_HOME/skills/`；未设置 `CODEX_HOME` 时，默认位置是 `~/.codex/skills/`。在下一轮对话中调用 `$marketing-collateral-and-crm`。

## 使用示例

- `$marketing-collateral-and-crm 把这段产品文案和照片做成适合微信分享的海报。`
- `$marketing-collateral-and-crm 根据这份长文案和参数表制作 PDF 电子样册和可编辑 PPT。`
- `$marketing-collateral-and-crm 用我已登录的邮箱把最终样册发给指定客户。`
- `$marketing-collateral-and-crm 在我打开的 Edge 客户管理表中更新客户编号 123 的指定字段。`

## 运行条件

- 本仓库提供工作指令，不包含图像生成、PPT/PDF 制作、电脑控制工具或账号凭据。使用相应功能前，需要在自己的 Codex 环境中配置可用工具。
- 邮件和客户表操作需要用户提供具体对象、内容和授权；实际操作遵守所用电脑控制工具的确认规则。
- 用户提供的产品事实和参数是内容依据。生成的概念图应与真实产品照片区分。

## 文件

- `marketing-collateral-and-crm/SKILL.md`：任务路由与共通规则
- `marketing-collateral-and-crm/references/creative.md`：海报、样册和 PPT 制作
- `marketing-collateral-and-crm/references/operations.md`：邮件与 Edge 客户表操作

## 许可

MIT，见 `LICENSE`。
