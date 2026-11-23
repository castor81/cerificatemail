# cerificatemail

Oklevélküldés: szervezeti címtár (NKE HHK KTVK). A Storyline oklevél képét az n8n a hallgató által beírt szervezet alapján küldi el a megfelelő e-mail címre; hiba vagy nem egyértelmű egyezés esetén a tartalék címre (alapértelmezés: VargaTamas@uni-nke.hu).

- `index.html`: a címtár-kezelő oldal (aktuális verzió: 1.0, 2026-11-23)
- `versions/`: a verziózott másolatok (`szervezet-cimtar_vX.Y_ÉÉÉÉ-HH-NN.html`)

Éles használathoz az `index.html` elején a `CONFIG.API_URL` mezőbe az n8n webhook címét kell írni. Üresen az oldal bemutató módban fut (adatok csak a böngészőben). Az API leírása az `index.html` fejlécében található kommentben van.
