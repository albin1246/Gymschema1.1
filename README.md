# GymSchema PWA

En fristående, svensk gymapp som fungerar på iPhone via Safari och även på Windows.

## Publicera gratis med GitHub Pages

1. Skapa ett GitHub-konto och ett nytt **publikt** repository, t.ex. `gymschema`.
2. Packa upp ZIP-filen och ladda upp **innehållet** i mappen `GymSchema-PWA` till repositoryts rot.
3. Gå till **Settings → Pages**, välj **Deploy from a branch**, `main`, `/ (root)` och tryck **Save**.
4. När sidan publicerats, öppna länken `https://DITT-NAMN.github.io/gymschema/` i Safari på iPhone.
5. Tryck på delningssymbolen → **Lägg till på hemskärmen** → **Lägg till**.

Appen kräver HTTPS för offline-stöd och installation på hemskärmen. Öppning av `index.html` direkt från filsystemet ger inte full PWA-funktion.

## Funktioner
- Tre rullande helkroppspass A/B/C, utan fasta veckodagar.
- Registrering av kilo, repetitioner och avklarade set.
- Träningshistorik och automatiskt nästa pass.
- Kostmål och kroppsvikt.
- Offline-cache och lokal lagring i webbläsaren.
- Export/import av säkerhetskopia i JSON.

**Obs:** Träningsdata lagras lokalt på enheten, inte i molnet. Exportera regelbundet en säkerhetskopia. Rensa inte webbplatsdata utan backup.

Övningssymbolerna är enkla ikoner, inte instruktionsfotografier. Riktiga övningsbilder kan läggas till i en senare version.


## Version 1.1
Tryck på det limegröna **!** vid varje övning för en offline-guide med schematisk illustration, startposition, rörelse och vanliga teknikfel. Befintliga träningsdata ligger kvar (samma localStorage-nyckel). Uppdatera samtliga filer i GitHub och vänta på Pages-publiceringen.
