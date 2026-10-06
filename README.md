# Krwawa Samsara: grafiki

Paczka grafik pobierana przez grę po instalacji (`AssetPack.java`).

- `manifest.json`: wersja paczki, nazwa pliku, rozmiar.
- `art-<wersja>.zip`: grafiki (webp/jpg), bez folderów.

Gra czyta: `https://raw.githubusercontent.com/bartekzawierucha-creator/krwawa-samsara-assets/main/manifest.json`.
Nową paczkę buduje `samsara/tools/make_pack.py` (podnieś w nim `VERSION`).
