# 待办事项应用

一个使用 Jetpack Compose 开发的现代化待办事项应用。

## 功能特点

- 创建、编辑和删除待办事项
- 设置待办事项的优先级和截止日期
- 标记待办事项的状态（待办、进行中、已完成）
- 搜索和筛选待办事项
- 查看待办事项的统计信息
- 深色模式支持
- 数据导入导出
- 通知提醒

## 技术栈

- Kotlin
- Jetpack Compose
- Material Design 3
- Room 数据库
- DataStore
- Hilt 依赖注入
- Kotlin 协程和 Flow
- MVVM 架构

## 项目结构

```
app/
├── data/
│   ├── local/
│   │   ├── TodoDao.kt
│   │   ├── TodoDatabase.kt
│   │   └── Converters.kt
│   ├── model/
│   │   ├── Todo.kt
│   │   └── TodoStatus.kt
│   └── repository/
│       ├── TodoRepository.kt
│       └── SettingsRepository.kt
├── ui/
│   ├── screens/
│   │   ├── TodoScreen.kt
│   │   ├── TodoListScreen.kt
│   │   ├── StatsScreen.kt
│   │   └── SettingsScreen.kt
│   ├── theme/
│   │   ├── Color.kt
│   │   ├── Theme.kt
│   │   └── Type.kt
│   └── viewmodels/
│       ├── TodoViewModel.kt
│       └── SettingsViewModel.kt
└── TodoApplication.kt
```

## 开发环境要求

- Android Studio Hedgehog | 2023.1.1
- JDK 17
- Android SDK 34
- Gradle 8.1.0

## 构建和运行

1. 克隆项目
2. 在 Android Studio 中打开项目
3. 等待 Gradle 同步完成
4. 点击运行按钮或使用快捷键 Shift + F10

## 贡献

欢迎提交 Issue 和 Pull Request。

## 许可证

MIT License 