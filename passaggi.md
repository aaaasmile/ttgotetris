# TTGTetris
Questo è un semplice Tetris per TTGO
Come riferimento ho preso questi due progetti:
Codice del gioco:
https://github.com/VolosR/TTGOTetris
Codice del display:
https://github.com/Xinyuan-LilyGO/TTGO-T-Display

Il display l'ho dovuto copiare nella directory lib usando la directory tft_espi
del branch master della libreria. Qui non bisogna editare il file user_setup_select.h
in quanto è già a posto con la linea:
#include <User_Setups/Setup25_TTGO_T_Display.h>    // Setup file for ESP32 and TTGO T-Display ST7789V SPI bus TFT

Da notare che la libreria bodmer/TFT_eSPI@^2.3.85 non funziona, anche editando il file user_setup_select.h
il display non è corretto anche se si vede qualcosa.

## Comandi
I due bottoni della scheda servono per muovere a destra e a sinistra il blocco.
Se si premono i due pulsanti contemporaneamente i due pulsanti allora il blocco ruota.


