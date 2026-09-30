# Third-party notices

*Wirefeed is Copyright (c) 2026 SignalWorx Labs, LLC. All rights reserved. See [LICENSE](LICENSE).*

The Wirefeed firmware is built with the open-source components below. Each remains under its own
license, and nothing in the Wirefeed license limits the rights those licenses grant. Versions are
the ones pinned in `platformio.ini`.

## Compiled into the firmware

| Component | Version | License | Copyright |
|---|---|---|---|
| [Arduino core for the ESP32](https://github.com/espressif/arduino-esp32) (via PlatformIO `espressif32@7.1.3`) | 2.0.17 | **LGPL-2.1** (core); some parts Apache-2.0 | Espressif Systems and contributors |
| [ESP-IDF](https://github.com/espressif/esp-idf), with FreeRTOS, lwIP, mbedTLS and LittleFS | 4.4 | Apache-2.0 (ESP-IDF, mbedTLS); MIT (FreeRTOS); BSD-3-Clause (lwIP, LittleFS) | Espressif Systems; Amazon; the lwIP, Arm Mbed TLS and LittleFS authors |
| [ESP32-HUB75-MatrixPanel-DMA](https://github.com/mrcodetastic/ESP32-HUB75-MatrixPanel-DMA) | see platformio.ini | MIT | Faptastic (mrcodetastic) |
| [Adafruit GFX Library](https://github.com/adafruit/Adafruit-GFX-Library) | see platformio.ini | BSD | Adafruit Industries |
| [Adafruit BusIO](https://github.com/adafruit/Adafruit_BusIO) | see platformio.ini | MIT | Adafruit Industries |
| [ArduinoJson](https://arduinojson.org) | 7.x | MIT | Benoit Blanchon |
| [PubSubClient](https://github.com/knolleary/pubsubclient) | 2.x | MIT | Nicholas O'Leary |
| [PNGdec](https://github.com/bitbank2/PNGdec) | see platformio.ini | Apache-2.0 | BitBank Software, Inc. |
| Root CA certificates in `src/update_certs.h` (USERTrust ECC, ISRG Root X1, Sectigo E46, ISRG Root YR) | - | Public certificates, distributed for verification | Sectigo / The USERTRUST Network; Internet Security Research Group |

### LGPL-2.1 (Arduino core for the ESP32)

Parts of the Arduino core for the ESP32 are licensed under the GNU Lesser General Public License,
version 2.1. The source code of those components is available from
<https://github.com/espressif/arduino-esp32/tree/2.0.17>. On request, SignalWorx Labs will provide
what the LGPL-2.1 requires so a recipient can relink the firmware with a modified version of those
components.

## Fonts and artwork

| Item | License | Notes |
|---|---|---|
| [Sora](https://github.com/sora-xor/sora-font) | SIL Open Font License 1.1 | The "wirefeed" wordmark on the LED splash (`src/splash_art.h`) is rendered from Sora. The settings page loads Sora from Google Fonts. |
| [IBM Plex Mono](https://github.com/IBM/plex) | SIL Open Font License 1.1 | Loaded by the settings page from Google Fonts. |

## Trademarks

League, team, tournament, company and news-source names and logos shown by Wirefeed are
trademarks of their respective owners. They are shown only for identification and imply no
affiliation with or endorsement by those owners.
