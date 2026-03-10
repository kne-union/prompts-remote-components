# Prompts 文档索引

本项目包含多个 AI prompts 文档，用于指导生成特定类型的代码模块。

## 文档列表

### 1. BizUnit使用指南

**功能**: 生成基于 BizUnit 架构模式的完整前端业务模块

**适用场景**: 当你需要生成一个包含完整 CRUD 功能、国际化支持、文档示例和可复用组件结构的前端业务模块时使用

**核心内容**:
- 模块目录结构规范（List、Detail、FormInner、TabDetail、Actions 等组件）
- 核心组件实现规范（根组件、列表页、表单组件、详情页、Tab 详情页）
- 国际化文件规范（中英文语言包）
- API 集成规范
- 文档示例规范

**使用方式**: 阅读 [BizUnit使用指南](./prompts/BizUnit使用指南.md) 了解完整的模块生成规范

---

### 2. RemoteLoader使用指南

**功能**: 远程模块加载库的使用指南，基于 Webpack 5 Module Federation

**适用场景**: 
- 构建微前端架构
- 需要在运行时动态加载远程模块
- 多团队独立开发部署模块的场景

**核心内容**:
- 四种使用方式：RemoteLoader 组件、withRemoteLoader HOC、useLoader Hook、createWithRemoteLoader
- 模块标记格式详解
- API 参考（preset、loadModule、safeLoadModule、parseToken 等）
- 缓存机制
- 错误处理和调试
- 性能优化

**使用方式**: 阅读 [RemoteLoader使用指南](./prompts/RemoteLoader用指南.md) 了解完整的使用方法

---

### 3. FormInfo使用指南

**功能**: 基于 React 和 Ant Design 的企业级表单组件库

**适用场景**:
- 构建复杂的表单页面
- 需要表单验证、动态字段、弹窗/抽屉表单
- 分步表单向导

**核心内容**:
- 核心组件：Form、FormInfo、SubmitButton、CancelButton
- 字段类型：Input、TextArea、Select、DatePicker、Upload 等
- 校验规则配置
- 列表组件：List（卡片式）、TableList（表格）
- 弹窗与抽屉：FormModal、FormDrawer
- 分步表单：FormSteps、FormStepModal
- 表单 Hook：useFormModal、useFormDrawer、useFormStepModal
- 国际化支持

**使用方式**: 阅读 [FormInfo使用指南](./prompts/FormInfo使用指南.md) 了解完整的使用方法

---

## 如何选择

| 需求 | 使用文档 |
|------|----------|
| 生成完整的业务模块（列表+表单+详情） | BizUnit使用指南 |
| 加载远程组件/微前端 | RemoteLoader使用指南 |
| 构建表单页面（验证、动态字段、弹窗） | FormInfo使用指南 |
