<!--
N.B.: Questo README è stato automaticamente generato da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON DEVE essere modificato manualmente.
-->

# Searx per YunoHost

[![Livello di integrazione](https://dash.yunohost.org/integration/searx.svg)](https://dash.yunohost.org/appci/app/searx) ![Stato di funzionamento](https://ci-apps.yunohost.org/ci/badges/searx.status.svg) ![Stato di manutenzione](https://ci-apps.yunohost.org/ci/badges/searx.maintain.svg)

[![Installa Searx con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=searx)

*[Leggi questo README in altre lingue.](./ALL_README.md)*

> *Questo pacchetto ti permette di installare Searx su un server YunoHost in modo semplice e veloce.*  
> *Se non hai YunoHost, consulta [la guida](https://yunohost.org/install) per imparare a installarlo.*

## Panoramica

Privacy-respecting, hackable metasearch engine.

As of 2023-09-07, SearX is now unmaintained upstream (cf. [commit](https://github.com/searx/searx/commit/276ffd3f01cdd823f75676c51231fad4040059d3)).
Installation is discouraged.

SearXNG is a potential alternative, already packaged for YunoHost.


**Versione pubblicata:** 1.1.0~ynh3

**Prova:** <https://demo.yunohost.org/searx/>

## Screenshot

![Screenshot di Searx](./doc/screenshots/Screenshot.png)

## :red_circle: Anti-funzionalità

- **Applicazione non mantenuta**: Questo software non è più mantenuto. Ci si può aspettare che con il passare del tempo smetta di funzionare, sia esposto a falle di sicurezza, ecc.

## Documentazione e risorse

- Sito web ufficiale dell’app: <https://searx.github.io/searx/>
- Documentazione ufficiale per gli amministratori: <https://github.com/searx/searx/wiki>
- Repository upstream del codice dell’app: <https://github.com/searx/searx>
- Store di YunoHost: <https://apps.yunohost.org/app/searx>
- Segnala un problema: <https://github.com/YunoHost-Apps/searx_ynh/issues>

## Informazioni per sviluppatori

Si prega di inviare la tua pull request alla [branch di `testing`](https://github.com/YunoHost-Apps/searx_ynh/tree/testing).

Per provare la branch di `testing`, si prega di procedere in questo modo:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/searx_ynh/tree/testing --debug
o
sudo yunohost app upgrade searx -u https://github.com/YunoHost-Apps/searx_ynh/tree/testing --debug
```

**Maggiori informazioni riguardo il pacchetto di quest’app:** <https://yunohost.org/packaging_apps>
