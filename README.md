# Odin 红点插件工具

统一导入 `RedDotSystem_Odin.unitypackage`，包含框架源码、红点树工作台、示例和工具使用说明。

1. 目标 Unity 工程先安装 Odin Inspector，插件包不包含 Odin。
2. 导入插件包，打开 `Tools > RedDotSystem > 红点树工作台`。
3. 在“操作”中创建配置或选择已有配置，单击节点编辑属性、右键添加和删除，点击右下角“保存”。
4. 点击“操作 → 使用说明文档”查看完整工具操作手册。
- [工具使用说明](Assets/Plugins/RedDotSystem/红点插件工具使用说明文档.md)
- 示例场景：`Assets/Plugins/RedDotSystem/Samples/RedDotSample.unity`
- 示例配置：`Assets/Plugins/RedDotSystem/Samples/RedDotSampleConfig.asset`

测试代码保留在本地源码目录 `Assets/Plugins/RedDotSystem/Tests`，不随插件导出。当前编译验证环境为 Unity 2022.3.62f2；其他版本需在目标工程确认兼容性。
