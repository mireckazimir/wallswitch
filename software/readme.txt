Multisenzorový modul pro Raspberry Pi Zero
Bc. Miroslav Kažimír (xkazim00)

Adresár "wallswitch" obsahuje obslužný softvér pre monitor miestnosti.
Softvér je pripravený pre vývojové prostredie esp-idf, ktoré je možné
získať z: https://docs.espressif.com/projects/esp-idf/en/latest/esp32/get-started/index.html

Podrobné pokyny k inštalácii sú dostupné na tejto stránke:
https://docs.espressif.com/projects/esp-idf/en/latest/esp32/get-started/index.html#installation

Podadresár main obsahuje:
- knižnicu SCD4x
- knižnicu button na obsluhu stlačenia tlačidiel
- hlavný obslužný program main.cpp
- konfiguračné súbory a súbory určené na preklad