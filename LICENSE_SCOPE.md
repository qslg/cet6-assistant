# 许可范围 / License scope

本项目由 qslg 有权授权的程序代码和项目说明采用 MIT 许可证，完整许可文本见 [LICENSE](./LICENSE)。

MIT 适用于本项目的学习界面、搜索与筛选、复习安排、强化记忆本、学习记录导入导出等程序实现。MIT 允许使用、修改、分发和商业使用这些代码，须保留许可证及版权声明。

以下内容不属于 qslg 在本项目中作出的 MIT 授权：

- **词库与学习资料数据**：`src/data.json`，以及 JavaScript 发布文件中内嵌的词条、中文释义、短语、例句和学习关联数据。数据包含用户提供的《大学英语六级词汇完整带音标-可打印-可编辑-正序版》《赠-大学英语六级-高频词汇》《赠-英语六级高频词组》及《普通高中英语课程标准（2017年版2020年修订）》附录等资料的整理结果。当前没有核实第三方资料可再授权的许可证；相关权利归各自权利人所有，本项目未对这些资料授予新的再使用或再分发许可。
- **第三方软件与图标**：React、React DOM、Scheduler、Lucide、Tailwind CSS 等组件遵循各自许可证；完整版权及许可声明见 [THIRD_PARTY_NOTICES.md](./THIRD_PARTY_NOTICES.md)。它们不因本项目的许可证而改变授权人或原许可条件。
- **外部发音服务和音频**：有道发音按需联网播放，不随源码包分发。外部音频和服务不属于本项目的 MIT 授权范围；使用时须遵守提供方的条款。
- **原始资料文件**：原始 PDF、电子书和其他来源资料（包括以后可能新增的 `sources/`）不纳入本项目的 MIT 授权。

`cet6-assistant-source.zip` 内采用相同的许可范围。编译 JavaScript 混合了程序代码、第三方组件和词库数据，打包形式不会改变各部分的许可。

需要复用完整词库时，请先核实相应来源的授权；也可以在 MIT 程序代码上替换为有权使用的数据。

Project code and documentation that qslg has the right to license are provided under the MIT License. The vocabulary dataset (`src/data.json` and data embedded in built JavaScript), source study materials, and external pronunciation audio are excluded from this project's MIT grant. Third-party software retains its own licenses and copyright notices. This scope also applies to `cet6-assistant-source.zip` and compiled distributions; bundling does not change the licenses of their constituent parts.
