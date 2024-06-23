<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Searx YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/searx.svg)](https://dash.yunohost.org/appci/app/searx) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/searx.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/searx.maintain.svg)

[![Instalatu Searx YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=searx)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Searx YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Privacy-respecting, hackable metasearch engine.

As of 2023-09-07, SearX is now unmaintained upstream (cf. [commit](https://github.com/searx/searx/commit/276ffd3f01cdd823f75676c51231fad4040059d3)).
Installation is discouraged.

SearXNG is a potential alternative, already packaged for YunoHost.


**Paketatutako bertsioa:** 1.1.0~ynh3

**Demoa:** <https://demo.yunohost.org/searx/>

## Pantaila-argazkiak

![Searx(r)en pantaila-argazkia](./doc/screenshots/Screenshot.png)

## :red_circle: Ezaugarri zalantzagarriak

- **Jatorrizko garapena utzita**: Software honek ez du arduradunik. Denborak aurrera egin ahala funtzionatzeari utziko dio, konpondu gabeko segurtasun arazoak izango ditu, etab.

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://searx.github.io/searx/>
- Administratzaileen dokumentazio ofiziala: <https://github.com/searx/searx/wiki>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/searx/searx>
- YunoHost Denda: <https://apps.yunohost.org/app/searx>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/searx_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/searx_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/searx_ynh/tree/testing --debug
edo
sudo yunohost app upgrade searx -u https://github.com/YunoHost-Apps/searx_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
