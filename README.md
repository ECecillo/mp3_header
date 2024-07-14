# mp3_header

## Header informations

Total Length : 32 bits

- frame sync : Permet la synchronisation avec les autres frames du fichier audio, 12 bits
- MPEG Infos:
  - ID: Numéro de version MPEG, 1 bit.
  - LAYER : Indique quelle couche MPEG on a utilisé pour encoder le fichier MP3, 2 bits.
    - ‘01’ - Layer III
    - ‘10’ - Layer II
    - ‘11’ - Layer I
    - ‘00’ - Reserved
  - Protection bit : Indique si le bitestream est protégé par un contrôle de redondance cyclique (CRC) permettant de détecter les erreurs de transmission ou de transfert, 1 bit
    - '0' Protégé
    - '1' Pas protégé
  - Bitrate : Fréquence
  - Frequency :
  - Pad bit :
  - Priv bit :
  - Mode :
  - Mode extention :
  - Copy :
  - Home :
  - Emphasis :
  - Audio Data

