# Rabljena Sedla

Ta repozitorij vsebuje preprosto spletno trgovino z rabljenimi in novimi sedli. Stran uporablja [Bootstrap](https://getbootstrap.com/) za hitro oblikovanje elementov.

## Struktura projekta

```
<<<<<<< HEAD
website/
  index.html       - domača stran s ponudbo sedel
  about.html       - informacije o trgovini
  contact.html     - kontaktni obrazec
  admin.html       - preprosto orodje za urejanje ponudbe
  assets/
    style.css      - dodatni stili
```

## Uporaba

Odprite `website/index.html` v brskalniku. V datoteki `index.html` lahko
zamenjate povezave do slik in uredite opise sedel po svoji meri.

Za urejanje sedel je na voljo stran `admin.html`. Dostop je zaščiten z enostavnim geslom `sedlo123`. Na strani lahko dodate ali odstranite izdelke ter vsakič naložite več slik preko povleci in spusti. Spremembe se shranijo v brskalnikov `localStorage`.

<<<<<<< HEAD
> **Opomba**
> Lokalno shranjevanje med datotekami deluje le, če sta strani naloženi prek strežnika (npr. `python3 -m http.server`). Če jih odprete neposredno kot lokalne datoteke, brskalnik vsakemu URL-ju dodeli svoj prostor in shranjeni izdelki se na glavni strani ne bodo prikazali.


