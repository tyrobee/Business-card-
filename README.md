# Business-card-
A PCB Business card
A personal Business Card designed as a PCB. It contains an integrated NFC tag to share contact information wirelessly, and uses energy harvesting from NFC field to light up the LED circuitry.The heart of this PCB is the NFC controller IC, the NT3H1101 from NXP Semiconductors.NFC (Near Field Communication) is a short-range radio technology that enables communication between devices that are held in close proximity (< 10 cm). NFC systems are based on traditional High Frequency (HF) RFID, operating at 13.56 MHz.The form factor is maintained as a standard credit/debit card, so you can carry it around normally in your wallet.I used the "Bitmap to Component Convertor" tool built in KiCAD to import my custom font text, Logo, QR code, etc. I imported them as Soldermask and Copper layer so that they'll be visible with nice HASL/ENIG finish. My suggestion would be to minimize the use of silkscreen, as the silkscreen print might not be of good quality for complex graphics.The NFC tag programming was done with Tagwriter app from NXP. This app has multiple options to write Website Links, Phone number, Email, etc into the NTAG IC which you can customize as per your requirement.
## Schematics

## Pcb

