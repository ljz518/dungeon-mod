# 地牢游戏
![GitHub Release](https://img.shields.io/github/v/release/3944Realms/EroticDungeonGame) [![License](https://img.shields.io/badge/license-Apache%20License%202.0%20|%20CC%20BY--NC--SA%204.0-green)]()

[![CurseForge Download](https://img.shields.io/curseforge/dt/1445908?logo=curseforge&label=CurseForge)](https://www.curseforge.com/minecraft/mc-mods/dungeon-game)
[![Modrinth Download](https://img.shields.io/modrinth/dt/oaqKSBPT?logo=modrinth&label=Modrinth)](https://modrinth.com/mod/dungeongame)
## todo:
- [ ] Metal Frame 镐子没法加速挖掉、无法掉落
- [x] Metal Frame 破坏逻辑有问题
- [ ] secret片元着色器删除

# 对于开发者

**导入仓库:**

```groovy
repositories {
	maven {
		name = "LTD Maven"
		url = "https://nexus.bot.leisuretimedock.top/repository/maven-public/"
    }
}
```

**导入依赖**

请自行寻找相关前置依赖
```groovy
dependencies {
	implementation("top.r3944realms.eroticdungeongame:eroticdungeongame:1.20.1-26H8")
}
```
# 许可证说明

## 重要声明

本项目采用**双许可证结构**，不同部分适用不同的许可证：

1. **整体项目** - CC BY-NC-SA 4.0（非商业性共享）
2. **所有代码和脚本** - Apache License 2.0（允许商业使用）
3. **Minecraft材质** - 遵循Mojang EULA

## 许可证详情

### 1. 整体项目许可证
当您将本项目作为一个整体分发时（包括源代码、资源文件等），适用 **CC BY-NC-SA 4.0**。

**您可以：**
- 分享和传播本项目
- 改编和创作衍生作品

**您必须：**
- 注明原作者（署名）
- 非商业使用
- 以相同许可证分享衍生作品

**完整许可证：** [https://creativecommons.org/licenses/by-nc-sa/4.0/](https://creativecommons.org/licenses/by-nc-sa/4.0/)

### 2. 代码许可证
所有源代码、配置文件、构建脚本使用 **Apache License 2.0**。

**这意味着：**
- 您可以自由使用、修改、分发代码
- 可以用于商业项目
- 可以申请专利授权
- 需要保留原始版权声明

**完整许可证：** [https://www.apache.org/licenses/LICENSE-2.0](https://www.apache.org/licenses/LICENSE-2.0)

### 3. Minecraft资源许可证
项目中包含的Minecraft游戏材质归 Mojang Studios 所有，使用需遵循《Mojang最终用户许可协议》。

**重要限制：**
- 不得单独分发这些材质文件
- 仅能在遵守Minecraft EULA的条件下使用
- Mojang拥有对这些材质的完整版权

**官方EULA：** [https://www.minecraft.net/zh-hans/eula](https://www.minecraft.net/zh-hans/eula)

## 如何使用本项目

### 对于玩家：
1. 下载并使用本项目 → 遵循 CC BY-NC-SA 4.0
2. 使用时请勿用于商业目的
3. 分享时请保持署名

### 对于开发者：
1. 使用代码进行开发 → 遵循 Apache 2.0
2. 可以在商业项目中使用代码
3. 使用Minecraft材质时 → 遵循 Mojang EULA

### 对于分发者：
1. 分发整体项目包 → 遵循 CC BY-NC-SA 4.0
2. 不得单独提取和分发Minecraft材质
3. 必须在显著位置包含本许可证说明

## 文件分类

| 文件类型 | 适用许可证 |
|---------|-----------|
| 编译后的模组文件（.jar） | CC BY-NC-SA 4.0 |
| Java/Kotlin 源代码（.java, .kt） | Apache 2.0 |
| 构建脚本（build.gradle, .kts） | Apache 2.0 |
| 配置文件（.json, .toml, .properties） | Apache 2.0 |
| 文档文件（.md） | Apache 2.0 |
| Minecraft 材质文件 | Mojang EULA |
| 非Minecraft的原创材质 | CC BY-NC-SA 4.0 |
| 项目整体包 | CC BY-NC-SA 4.0 |

## 版权声明
地牢游戏 © [2025-2026] [R3944Realms]

源代码部分基于 Apache License 2.0 许可

整体项目基于 CC BY-NC-SA 4.0 许可

包含的Minecraft材质 © Mojang Studios，遵循Mojang EULA