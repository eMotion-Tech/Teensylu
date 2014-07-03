Pour utiliser correctement la Teensylu, il vous faudra jour avec le fichier "pins.h"
Malheureusement, de base l'adressage des entrées/sorties ne sont pas correct ni dans Repetier-firmware ni dans Marlin, il vous faudra donc copier le pins.h dans le dossier firmware de Repetier. 
Si jamais vous souhaitez utiliser Marlin, il vous faudra manuellement copié les bonnes configurations de ce fichier pins.h à l’intérieur du pins.h du firmware Marlin

In order to use properly the Teensylu board, you need to copy all Teesnylu’s pin configuration from our pins.h file to your firmware. Our pins.h firmware is originally from Repetier-firmware.
So if you are using Repetier-firwmare, just copy the pins.h file into the right folder.
