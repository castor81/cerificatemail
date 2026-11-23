# cerificatemail

Oklevélküldés: szervezeti címtár (NKE HHK KTVK). A Storyline oklevél képét az n8n a hallgató által beírt szervezet alapján küldi el a megfelelő e-mail címre; hiba vagy nem egyértelmű egyezés esetén a tartalék címre (alapértelmezés: VargaTamas@uni-nke.hu).

- `index.html`: a címtár-kezelő oldal (aktuális verzió: 1.1, 2026-11-23)
- `versions/`: a verziózott másolatok (`szervezet-cimtar_vX.Y_ÉÉÉÉ-HH-NN.html`)

Az oldal az n8n `Oklevélküldés – címtár API` workflow-jához kapcsolódik (`CONFIG.API_URL`), a belépőkódot az n8n ellenőrzi. Az adatok az n8n `cimtar_egysegek` és `cimtar_beallitasok` Data Table-jeiben vannak. Üres `API_URL` esetén az oldal bemutató módban fut (adatok csak a böngészőben). Az API leírása az `index.html` fejlécében található kommentben van.
