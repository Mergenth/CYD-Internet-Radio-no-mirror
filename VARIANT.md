# CYD-Internet-Radio-no-mirror

Variante von [Carlo47/CYD_InternetRadio](https://github.com/Carlo47/CYD_InternetRadio) (Public Domain / Unlicense) für ESP32-2432S028R („Cheap Yellow Display“, Version mit einer Micro-USB-Buchse), bei der der Text in der Originalversion gespiegelt erscheint.

**Änderung:** Display-Spiegelung entfernt (offset_rotation 0) in `include/lgfx_esp32-2432S028R.h`.

Weitere Anpassungen für den Build unter Linux/pioarduino: korrigierte Include-Schreibweise (`WiFi.h`, `ESP32AutoConnect.h`), Plattform pioarduino 55.03.38 (Arduino 3.3.8 / ESP-IDF 5.5.4), Libraries per GitHub-URL gepinnt.

**Fertiges Image:** `firmware/CYD-Internet-Radio-no-mirror.merged.bin` – ESP32, 4 MB, DIO, 40 MHz, flashen ab Offset 0x0.

**WLAN:** Keine Zugangsdaten im Image. Nach dem Flashen den Hotspot „AutoConnectAP“ verbinden und unter 192.168.4.1 das eigene WLAN eintragen.
