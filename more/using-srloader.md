---
title: Utilisation de SRLoader
layout: single
sidebar:
  nav: "side"
---

nds-bootstrap est actuellement un prototype, et est loin d'être complet. Attendez-vous à des temps de chargement longs et à des problèmes de compatibilité. Il est hautement recommandé de verifier et ajouter a vos favoris la [compatibility chart](https://docs.google.com/spreadsheets/d/1M7MxYQzVhb4604esdvo57a7crSvbGzFIdotLW0bm0Co/edit#gid=0){:target="_blank"}.
{: .notice--info}

SRLoader est un homebrew qui vous permez de lancer des homebrews, ainsi que des ROMs commerciale en utilisant [nds-bootstrap](https://github.com/ahezard/nds-bootstrap){:target="_blank"}. SRLoader a egalement divers emulateurs intégrés, ainsi qu'un lanceur GBA, qui vous permettent de lancer des ROMs Gameboy Color, NES and GBA.

Vous pouvez en apprendre davantage [here](https://gbatemp.net/threads/srloader-gui-for-flashcards-also-a-nds-app-for-dsi.472200/){:target="_blank"}.

## Téléchargements

- La dernière version de [SRLoader](https://github.com/Robz8/SRLoader/releases)

## Installation
1. Insérer la carte SD de votre DSi dans votre ordinateur
2. Copiez le contenu du ficher `.7z` twlnf à la racine de votre carte SD
  - Si il vous est demandé de remplacer boot.nds, répondez oui
3. Copiez les ROMS dans leur dossiers respectifs
  - Mettez les roms Gameboy dands `/roms/gb`
  - Mettez les roms NDS dans `/roms/nds`
  - Mettez les roms NES dans in `/roms/nes`
  - Pour la GBA, créez un dossier `gba` dans le dossier `roms` et mettez les roms dedans
  - Le lanceur GBA demande une copie du BIOS GBA nommée `bios.bin` a la racine de votre carte SD,  et ne supporte la sauvegarde actuellement

## Utilisation
1. Launch SRLoader using your homebrew entrypoint of choice
2. You will now see a list of your NDS ROMs
  - Press **Y** to launch homebrew applications without nds-bootstrap
  - Press **A** to launch commercial/homebrew ROMs using nds-bootstrap (Homebrew with DSi-extended header will not be ran by bootstrap)
  - Press **SELECT** to set a donor ROM when the compatibility list asks for one
  - Press **UP** or **DOWN** to toggle between NDS ROMs and DSiWare
  - Press **START**, then navigate to **Start GBARunner2** to run GBA ROMs
  - Press **B** to return to the DSi Menu
