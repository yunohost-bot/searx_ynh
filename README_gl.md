<!--
NOTA: Este README foi creado automáticamente por <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON debe editarse manualmente.
-->

# Searx para YunoHost

[![Nivel de integración](https://dash.yunohost.org/integration/searx.svg)](https://dash.yunohost.org/appci/app/searx) ![Estado de funcionamento](https://ci-apps.yunohost.org/ci/badges/searx.status.svg) ![Estado de mantemento](https://ci-apps.yunohost.org/ci/badges/searx.maintain.svg)

[![Instalar Searx con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=searx)

*[Le este README en outros idiomas.](./ALL_README.md)*

> *Este paquete permíteche instalar Searx de xeito rápido e doado nun servidor YunoHost.*  
> *Se non usas YunoHost, le a [documentación](https://yunohost.org/install) para saber como instalalo.*

## Vista xeral

Privacy-respecting, hackable metasearch engine.

As of 2023-09-07, SearX is now unmaintained upstream (cf. [commit](https://github.com/searx/searx/commit/276ffd3f01cdd823f75676c51231fad4040059d3)).
Installation is discouraged.

SearXNG is a potential alternative, already packaged for YunoHost.


**Versión proporcionada:** 1.1.0~ynh3

**Demo:** <https://demo.yunohost.org/searx/>

## Capturas de pantalla

![Captura de pantalla de Searx](./doc/screenshots/Screenshot.png)

## :red_circle: Caraterísticas cuestionables

- **Upstream not maintained**: This software is not maintained anymore. Expect it to break down over time, be exposed to unfixed security breaches, etc.

## Documentación e recursos

- Web oficial da app: <https://searx.github.io/searx/>
- Documentación oficial para admin: <https://github.com/searx/searx/wiki>
- Repositorio de orixe do código: <https://github.com/searx/searx>
- Tenda YunoHost: <https://apps.yunohost.org/app/searx>
- Informar dun problema: <https://github.com/YunoHost-Apps/searx_ynh/issues>

## Info de desenvolvemento

Envía a túa colaboración á [rama `testing`](https://github.com/YunoHost-Apps/searx_ynh/tree/testing).

Para probar a rama `testing`, procede deste xeito:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/searx_ynh/tree/testing --debug
ou
sudo yunohost app upgrade searx -u https://github.com/YunoHost-Apps/searx_ynh/tree/testing --debug
```

**Máis info sobre o empaquetado da app:** <https://yunohost.org/packaging_apps>
