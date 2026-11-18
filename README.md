# Caveman CN

**少说废话，技术信息一字不少。**

## 功能与流程

结论优先、去掉寒暄与复述、代码和错误原样保留、否定词与步骤顺序完整，以及普通／极简／文言三种回答方式。原来的核心规则保留，仅调整技能名称和本地模式引用。

## 只增加这些

- 中文启停与状态口令，状态查询不会误开启压缩。
- 现代汉语默认保持自然，不强行改成文言。
- 明确条件、否定、数量边界不能压掉，不用固定字数牺牲含义。

## 安装

```bash
npx skills add batespaige357-tech/caveman-cn --skill caveman-cn
```

也可以将 `skills/caveman-cn` 整个文件夹放进助手支持的技能目录。对助手说“使用 caveman-cn，开启简洁模式”；Codex 可用 `$caveman-cn`。

口令：`简洁模式`、`极简模式`、`文言模式`、`当前模式`、`退出简洁模式`。原有英文启停表达保留。无宿主模式状态时，只根据当前对话推断，不声称跨会话保存。

## 范围与验证

本项目是上游简洁回答 Skill 的中文适配，附带两种模式的规则参考；不打包 Caveman Code、代理、模型路由或浏览器压缩运行时。需要这些组件请访问上游。没有复制上游省费或性能成绩作为本项目成绩。

已检查技能格式、UTF-8 和引用完整性；未完成真实助手行为盲测或 token 成本测量。没有示例网页、效果截图，也没有安装全局技能或运行前端编译。

## 来源与许可

基于 [JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman)，由本仓库维护。 本仓库不由 Julius Brussee 维护。

沿用上游 Apache-2.0，保留 LICENSE、NOTICE、历史 MIT 许可说明与 LICENSING.md。修改范围、参考提交见 [CHANGES.md](CHANGES.md)。
