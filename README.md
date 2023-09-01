# How to export geoPDF from LeafletJS webmap
How to print geoPDF from a webmap in leaflet js to download maps from the web for Avenza.

TL:DR;
Leafletjs -> domtoimage -> GdalJS

With GDAL ported to WASM we can now convert leafletjs maps to geoPDF format for users to download and then load to Avenza. Massive companies rely on Avenza maps for people in the field to access small maps on their phone.

I couldn't find any complete resource for this and ran into 4 or 5 dead ends in SO/GH/Reddit on the topic and want to post this writeup to tie up those loose ends.
