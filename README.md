# HoshinoBot-Massive

forked from [Ice-Cirno/HoshinoBot](https://github.com/Ice-Cirno/HoshinoBot)

HoshinoBot 与一些社区插件的集合

## 使用方法

请参照原版 Hoshino 说明

注意：由于本仓库使用了 `submodule` 管理，克隆本仓库时建议加上 `--recurse-submodules` 参数，推荐的克隆指令为：

```sh
git clone https://github.com/pcrbot/HoshinoBot-Massive.git --recurse-submodules --depth=1
```

## 已加入的额外插件列表

| 仓库                                                                 | 作者                                         |
| -------------------------------------------------------------------- | -------------------------------------------- |
| [yobot](https://github.com/pcrbot/yobot)                             | [@yuudi](https://github.com/yuudi)           |
| [plugins-for-Hoshino](https://github.com/pcrbot/plugins-for-Hoshino) | [@shewinder](https://github.com/shewinder)   |
| [Genshin_Impact_bot](https://github.com/pcrbot/Genshin_Impact_bot)   | [@H-K-Y](https://github.com/H-K-Y)           |
| [music](https://github.com/pcrbot/music)                             | [@laipz8200](https://github.com/laipz8200)   |
| [erinilis-modules](https://github.com/pcrbot/erinilis-modules)       | [@yuyumoko](https://github.com/yuyumoko)     |
| [cappuccilo_plugins](https://github.com/pcrbot/cappuccilo_plugins)   | [@Cappuccilo](https://github.com/Cappuccilo) |
| [pcr-wiki](https://github.com/pcrbot/pcr-wiki)                       | [@Cappuccilo](https://github.com/Cappuccilo) |
| [image-generate](https://github.com/pcrbot/image-generate)           | [@xhl6666](https://github.com/xhl6666)       |
| [group-manager](https://github.com/pcrbot/group-manager)             | [@xhl6666](https://github.com/xhl6666)       |

## 贡献此合集

请使用 `git submodule` 进行管理，方便后续更新

1. 进入 `hoshinobot/modules` 目录，使用 `git submodule add <仓库名> <路径名>` 命令，路径名可省略。如果仓库名中有连字符，请指定 `路径名` 为不包含连字符的名称。
2. 进入 [\_\_bot\_\_.py](./hoshino/config_example/__bot__.py)，在 `MODULES_ON` 中添加模块名。如果模块在仓库内部，可以使用点号连接路径名。
3. 如果新模块需要额外的依赖，请进入 [requirements.txt](./requirements.txt) 添加依赖。
4. 提交 [pull request](https://github.com/pcrbot/HoshinoBot-Massive/pull/new/master)
