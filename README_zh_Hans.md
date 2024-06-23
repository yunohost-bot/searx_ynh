<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Searx

[![集成程度](https://dash.yunohost.org/integration/searx.svg)](https://dash.yunohost.org/appci/app/searx) ![工作状态](https://ci-apps.yunohost.org/ci/badges/searx.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/searx.maintain.svg)

[![使用 YunoHost 安装 Searx](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=searx)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Searx。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Privacy-respecting, hackable metasearch engine.

As of 2023-09-07, SearX is now unmaintained upstream (cf. [commit](https://github.com/searx/searx/commit/276ffd3f01cdd823f75676c51231fad4040059d3)).
Installation is discouraged.

SearXNG is a potential alternative, already packaged for YunoHost.


**分发版本：** 1.1.0~ynh3

**演示：** <https://demo.yunohost.org/searx/>

## 截图

![Searx 的截图](./doc/screenshots/Screenshot.png)

## :red_circle: 负面特征

- **Upstream not maintained**: This software is not maintained anymore. Expect it to break down over time, be exposed to unfixed security breaches, etc.

## 文档与资源

- 官方应用网站： <https://searx.github.io/searx/>
- 官方管理文档： <https://github.com/searx/searx/wiki>
- 上游应用代码库： <https://github.com/searx/searx>
- YunoHost 商店： <https://apps.yunohost.org/app/searx>
- 报告 bug： <https://github.com/YunoHost-Apps/searx_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/searx_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/searx_ynh/tree/testing --debug
或
sudo yunohost app upgrade searx -u https://github.com/YunoHost-Apps/searx_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
