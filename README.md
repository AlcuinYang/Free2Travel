# Free2Travel

产品工作名：LetsGoTravel。通过对话、旅行复盘和可解释推荐，逐步形成可执行、可修改的旅行计划。

## 当前状态

当前仓库包含产品规划与设计资料，尚无可运行网站。首个重点验证目的地为伦敦，出发地、身份、人数和天数为可变输入。

## 开发阅读顺序

1. [整体 PRD](docs/PRD.md)：产品范围、需求优先级、业务规则及验收。
2. [MVP 实施文件](docs/MVP-implementation-v1.md)：页面、输入输出、数据边界和工程阶段。
3. [多模型开发流程](docs/DEVELOPMENT-WORKFLOW.md)：Opus 骨架、DeepSeek 模块实现与独立 review 的分工及交接。

## 最新设计决策

- 液态玻璃极简科技风，少量手绘点缀；正文优先保证阅读。
- 主内容居中，底部对话舱；桌面支持移动停靠，取消右侧常驻聊天。
- 偏好、经历及旅行草稿默认保存在设备；云端模型处理需单独说明。
- 导出 PDF 旅行手册、PNG 分享卡和 JSON 可恢复备份。
- 现有概念图仍为旧巴黎场景与右侧聊天布局，仅作为配色和材质参考。

## 设计资料

- [旧版概念渲染](docs/design/travel-workspace-liquid-glass-v1.png)
- [生成提示词](docs/design/ui-render-prompt-v1.md)

## 在另一台服务器继续

```sh
git clone https://github.com/AlcuinYang/Free2Travel.git
cd Free2Travel
```

先阅读以上三份文档，再建立隔离分支开展开发。当前尚未确定依赖安装与运行命令，不应假定已有应用入口。

模型凭据与服务地址由每台机器自行配置，不提交 API 密钥、私人旅行资料或本机认证文件。文档中的本机配置观察仅为当时的接入记录，不能当作服务器的有效配置。
