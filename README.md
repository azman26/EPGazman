# Źródła EPG dla polskich kanałów

Zbiór źródeł EPG dla polskich kanałów TV SAT, IPTV, kablowej i naziemnej. Dodatkowo EPG dla kanałów radiowych z satelitów Hot Bird 13°E i Astra 19.2°E oraz radia internetowego. Przeznaczone dla pluginu EPG-Importer w oprogramowaniu E2.

## Opis plików

*   `polandAzman.sources.xml` - Główny plik ze źródłami dla pluginu EPG Importer.
*   `azman.channels.xml` - Zestawienie referencji dla wszystkich kanałów, dla których tworzone jest EPG.
*   `azman_channels_mappings.py` - Plik wykorzystywany przez e2k do mapowania referencji podczas generowania bukietów.

## Źródła [azman] Poland XMLTV

Dostępne są następujące pakiety EPG:

*   **Podstawowy**
    Zawiera EPG dla wszystkich kanałów SAT PL z 13°E i 19.2°E oraz TV Kablowej i Naziemnej.
    *(Liczba kanałów: 196)*

*   **Dodatkowy**
    Pozostałe kanały PL z innych pozycji SAT oraz wybrane kanały zagraniczne.
    *(Liczba kanałów: 13)*

*   **IPTV**
    Zawiera EPG dla niektórych kanałów IPTV PL, przekazów z YouTube oraz kanałów z WP Pilot i Telewizji Online.
    *(Liczba kanałów: 62)*

*   **Radio**
    Zawiera EPG Radia PL z 13°E i 19.2°E oraz niektórych internetowych streamów radiowych.
    *(Liczba kanałów: 72)*

---

### Informacje dodatkowe

Plik `rytec.sources.xml` został zmodyfikowany i zawiera dodatkowe wpisy do źródeł EPG dla kanałów PolsatBox VOD, iTVN (Timezone) oraz Private Azman FAST TV.