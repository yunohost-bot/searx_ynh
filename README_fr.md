<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Searx pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/searx.svg)](https://dash.yunohost.org/appci/app/searx) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/searx.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/searx.maintain.svg)

[![Installer Searx avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=searx)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Searx rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Privacy-respecting, hackable metasearch engine.

As of 2023-09-07, SearX is now unmaintained upstream (cf. [commit](https://github.com/searx/searx/commit/276ffd3f01cdd823f75676c51231fad4040059d3)).
Installation is discouraged.

SearXNG is a potential alternative, already packaged for YunoHost.


**Version incluse :** 1.1.0~ynh3

**Démo :** <https://demo.yunohost.org/searx/>

## Captures d’écran

![Capture d’écran de Searx](./doc/screenshots/Screenshot.png)

## :red_circle: Anti-fonctionnalités

- **Application non maintenue **: Ce logiciel n'est plus maintenu. Attendez-vous à ce qu'il ne fonctionne plus avec le temps, et que l'on découvre des failles de sécurité qui ne seront pas corrigées, etc.

## Documentations et ressources

- Site officiel de l’app : <https://searx.github.io/searx/>
- Documentation officielle de l’admin : <https://github.com/searx/searx/wiki>
- Dépôt de code officiel de l’app : <https://github.com/searx/searx>
- YunoHost Store : <https://apps.yunohost.org/app/searx>
- Signaler un bug : <https://github.com/YunoHost-Apps/searx_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/searx_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/searx_ynh/tree/testing --debug
ou
sudo yunohost app upgrade searx -u https://github.com/YunoHost-Apps/searx_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
