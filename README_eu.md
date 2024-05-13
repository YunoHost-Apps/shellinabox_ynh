<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Shell In A Box YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/shellinabox.svg)](https://dash.yunohost.org/appci/app/shellinabox) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/shellinabox.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/shellinabox.maintain.svg)

[![Instalatu Shell In A Box YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=shellinabox)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Shell In A Box YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Shell In A Box implements a web server that can export arbitrary command line tools to a web based terminal emulator. This emulator is accessible to any JavaScript and CSS enabled web browser and does not require any additional browser plugins.


**Paketatutako bertsioa:** 2.21~ynh5

## Pantaila-argazkiak

![Shell In A Box(r)en pantaila-argazkia](./doc/screenshots/screenshot.gif)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://code.google.com/archive/p/shellinabox/>
- Erabiltzaileen dokumentazio ofiziala: <https://code.google.com/p/shellinabox/wiki/shellinaboxd_man>
- Administratzaileen dokumentazio ofiziala: <https://github.com/shellinabox/shellinabox/wiki/shellinaboxd_man>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/shellinabox/shellinabox>
- YunoHost Denda: <https://apps.yunohost.org/app/shellinabox>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/shellinabox_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/shellinabox_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/shellinabox_ynh/tree/testing --debug
edo
sudo yunohost app upgrade shellinabox -u https://github.com/YunoHost-Apps/shellinabox_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
