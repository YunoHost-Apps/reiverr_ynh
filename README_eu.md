<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Reiverr YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/reiverr.svg)](https://dash.yunohost.org/appci/app/reiverr) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/reiverr.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/reiverr.maintain.svg)

[![Instalatu Reiverr YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=reiverr)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Reiverr YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Reiverr is a project that aims to create a single UI for interacting with TMDB, Jellyfin, Radarr and Sonarr, as well as be an alternative to Overseerr.

**Paketatutako bertsioa:** 1.1.1~ynh1

## Pantaila-argazkiak

![Reiverr(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## :red_circle: Ezaugarri zalantzagarriak

- **Alfa softwarea**: Garapenaren hasierako fasean dago. Ezaugarri aldakor edo ezegonkorrak, erroreak eta segurtasun-arazoak izan ditzazke.

## Dokumentazioa eta baliabideak

- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/aleksilassila/reiverr>
- YunoHost Denda: <https://apps.yunohost.org/app/reiverr>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/reiverr_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/reiverr_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/reiverr_ynh/tree/testing --debug
edo
sudo yunohost app upgrade reiverr -u https://github.com/YunoHost-Apps/reiverr_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
