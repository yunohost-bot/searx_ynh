<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# Searx para Yunohost

[![Nivel de integración](https://dash.yunohost.org/integration/searx.svg)](https://dash.yunohost.org/appci/app/searx) ![Estado funcional](https://ci-apps.yunohost.org/ci/badges/searx.status.svg) ![Estado En Mantención](https://ci-apps.yunohost.org/ci/badges/searx.maintain.svg)

[![Instalar Searx con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=searx)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarSearx rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

Privacy-respecting, hackable metasearch engine.

As of 2023-09-07, SearX is now unmaintained upstream (cf. [commit](https://github.com/searx/searx/commit/276ffd3f01cdd823f75676c51231fad4040059d3)).
Installation is discouraged.

SearXNG is a potential alternative, already packaged for YunoHost.


**Versión actual:** 1.1.0~ynh3

**Demo:** <https://demo.yunohost.org/searx/>

## Capturas

![Captura de Searx](./doc/screenshots/Screenshot.png)

## :red_circle: Características no deseables

- **Upstream not maintained**: This software is not maintained anymore. Expect it to break down over time, be exposed to unfixed security breaches, etc.

## Documentaciones y recursos

- Sitio web oficial: <https://searx.github.io/searx/>
- Documentación administrador oficial: <https://github.com/searx/searx/wiki>
- Repositorio del código fuente oficial de la aplicación : <https://github.com/searx/searx>
- Catálogo YunoHost: <https://apps.yunohost.org/app/searx>
- Reportar un error: <https://github.com/YunoHost-Apps/searx_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [`branch testing`](https://github.com/YunoHost-Apps/searx_ynh/tree/testing

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/searx_ynh/tree/testing --debug
o
sudo yunohost app upgrade searx -u https://github.com/YunoHost-Apps/searx_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
