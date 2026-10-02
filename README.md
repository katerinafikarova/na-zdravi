# Na zdraví, Smíchove – AR zážitek

Statický web pro GitHub Pages. Obsah složky:

- `index.html` – celý AR zážitek v jednom souboru
- `kompilace.html` – jednorázově vygeneruje soubor pro rozpoznávání mostu (`target.mind`)
- `qr.html` – vytvoří QR kód na zveřejněnou adresu
- `assets/ar2/target.jpg` – grafika mostu pro kompilaci
- `.nojekyll` – technický soubor pro GitHub Pages (může být skrytý)

## Nasazení krok za krokem

1. Rozbal staženou složku.
2. Založ si zdarma účet na https://github.com a přihlas se.
3. Vpravo nahoře klikni na **+ → New repository**. Název třeba `na-zdravi`, zvol **Public**, klikni **Create repository**.
4. Na stránce nového repozitáře klikni na odkaz **uploading an existing file**. Přetáhni do okna **obsah** rozbalené složky (soubory i složku `assets`). Dole klikni **Commit changes**.
5. Otevři **Settings → Pages**. U *Source* zvol **Deploy from a branch**, u *Branch* **main** a **/ (root)**, klikni **Save**.
6. Počkej 1–2 minuty a obnov stránku. Nahoře se objeví adresa ve tvaru `https://TVOJE-JMENO.github.io/na-zdravi/`.
7. Otevři adresu v telefonu, projdi úvod a povol kameru. Na počítači použij **Přehrát bez kamery**.

## Zrychlení rozpoznávání (doporučeno)

8. Otevři `https://TVOJE-JMENO.github.io/na-zdravi/kompilace.html`, klikni **Zkompilovat** a stáhni `target.mind`.
9. V repozitáři otevři složku `assets` → `ar2`, klikni **Add file → Upload files**, nahraj `target.mind` a dej **Commit changes**.

Bez tohoto souboru si ho připraví každý telefon sám při prvním spuštění (desítky sekund).

## QR kód

10. Otevři `https://TVOJE-JMENO.github.io/na-zdravi/qr.html`, zkontroluj adresu a stáhni PNG. Před tiskem ho otestuj fotoaparátem telefonu.

## Úpravy

Novou verzi nasadíš tak, že v repozitáři znovu nahraješ `index.html` (Add file → Upload files → Commit). Změna se projeví do pár minut.

Poznámky: kamera funguje jen přes HTTPS, což GitHub Pages splňuje. Jméno zůstává jen v zařízení. Veřejný repozitář je vidět komukoli, včetně grafiky.
