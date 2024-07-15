<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# CAERP YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/caerp.svg)](https://ci-apps.yunohost.org/ci/apps/caerp/) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/caerp.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/caerp.maintain.svg)

[![Instalatu CAERP YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=caerp)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek CAERP YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

enDI is a business management software package. It is the management tool for
economic and social activity entirely dedicated to CAEs as well as to any
company and group of independent entrepreneurs.

It's the software behind the enDi and MoOGLi services.

### Features

- Social management of entrepreneurs
- Social and statistical management of support for reporting to funders
- Support for the entrepreneurial journey and commercial activity of entrepreneurs


**Paketatutako bertsioa:** 2024.07.12~ynh1

**Demoa:** <https://demo.endi.coop>

## Pantaila-argazkiak

![CAERP(r)en pantaila-argazkia](./doc/screenshots/accueil.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://endi.coop>
- Erabiltzaileen dokumentazio ofiziala: <https://doc.endi.coop>
- Jatorrizko aplikazioaren kode-gordailua: <https://framagit.org/caerp/caerp>
- YunoHost Denda: <https://apps.yunohost.org/app/caerp>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/caerp_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/caerp_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/caerp_ynh/tree/testing --debug
edo
sudo yunohost app upgrade caerp -u https://github.com/YunoHost-Apps/caerp_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
