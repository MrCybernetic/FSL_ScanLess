Feel free to join the chat / N'hésite pas à venir discuter : 

[![Join the chat at https://gitter.im/FSL_ScanLess/community](https://badges.gitter.im/FSL_ScanLess/community.svg)](https://gitter.im/FSL_ScanLess/community?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

# SCANLESS
![XDrip Principe](https://github.com/MrCybernetic/FSL_ScanLess/blob/master/img/scanless_principe.png?raw=true) 

![EN Flag](https://github.com/MrCybernetic/FSL_ScanLess/blob/master/img/en.png?raw=true) EN

Designing an open source PCB to turn your Freestyle Libre into a wireless CGM (continuous glucose monitor) based on LimiTTer ([Limitter Original Project](https://github.com/JoernL/LimiTTer)). Hardware inside :
+ BM019 NFC tag reader ([BM019 from Solutions Cubed](http://www.solutions-cubed.com/bm019/), see BM019 folder to see documentation and schematics)
+ HM17 BLE Module
+ Atmega328P (Arduino Pro Mini compatible)
+ USB to Serial Converter to program the Arduino (CP2104)
+ LiPo Charger (MCP73831)
+ LiPo Battery (3.7V)

SCANLESS is an open source Project NOT maintained by Abbott. It is a experimental DIY project. You can contribute in this project as you want.

## Project Progress

+ BM019 tested  :heavy_check_mark: 
+ Electronics : Schematics and PCB reviewed :heavy_check_mark: 
+ BLE to test :heavy_check_mark:
+ Arduino to test ([Keencave Github / LBridge Arduino Code](https://github.com/keencave/LBridge)) :heavy_check_mark:
+ XDrip to test :heavy_check_mark:
+ Design 3D printable enclosure :heavy_check_mark:

--- 

![FR Flag](https://github.com/MrCybernetic/FSL_ScanLess/blob/master/img/fr.png?raw=true) FR

Le but de ce projet est de concevoir un PCB en open source pour suivre votre glycémie via votre smartphone. Ce projet est basé sur celui-ci : LimiTTer ([JoernL Github / Projet Original Limitter](https://github.com/JoernL/LimiTTer)).
+ Lecteur de tag NFC BM019 ([BM019 de Solutions Cubed](http://www.solutions-cubed.com/bm019/), la doc du BM019 et son schéma est dans le dossier BM019)
+ module BLE HM17
+ Atmega328P (Compatible avec Arduino Pro Mini bootloader)
+ Convertisseur USB vers Série pour pouvoir programmer l'Arduino (CP2104)
+ circuit intégré pour charger la LiPo (MCP73831)
+ une batterie LiPo (3.7V, ???mAh pas encore définie)

SCANLESS est un projet open source non supporté par Abbott. C'est un projet DIY expérimental. N'hésitez surtout pas à proposer des améliorations.

# Avancement

+ Tester le fonctionnement du BM019 :heavy_check_mark:
+ Vérification des schémas électronique :heavy_check_mark: 
+ Tester le BLE :heavy_check_mark:
+ Tester le code Arduino ([Keencave Github / LBridge Arduino Code](https://github.com/keencave/LBridge)) :heavy_check_mark:
+ Tester l'appli XDrip :heavy_check_mark:
+ Concevoir une coque imprimable (3D) :heavy_check_mark:

![PCB](https://github.com/MrCybernetic/FSL_ScanLess/blob/master/SCANLESS/img/complete.jpg?raw=true)

*Actual state / état actuel*

# **#WeAreNotWaiting**