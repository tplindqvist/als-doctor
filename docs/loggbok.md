# Loggbok

## 2026-10-10

**Mål idag:**

Skapa ett skelett av en solution med Core och CLI för att separera logiken från gränssnittet - motorn från rattarna.

**Vad jag gjorde:**

- Avgrändsade projektet till en funktion: lista plugins, uppdelat i native, externa och Mac for Live.
- Skapade solution med två projekt: AlsDoctor.Core och AlsDoctor.Cli.
- La en projektreferens från Cli till Core.
- Pushade branch.

**Vad som gick fel:**

**Hur jag löste det:**

**Vad jag lärde mig:**

Regex klarar inte nästlad XML (racks innehåller egna <Devices>, så en icke-greedy matchning tappade en fjärdedel av devicerna).

**Källor:**

**Nästa steg:**

Ta reda på hur en .als faktiskt ser ut inuti och anteckna vad jag hittar - hitta sökvägar, plugin-referenser, live-version och format osv.

## 2026-10-06

**Mål idag:**

Sätta upp projektet - verktyg, repo på Github, README och första committen.

**Vad jag gjorde:**
- Skapade repot als-doctor på GitHub med .gitignore-mall.
- Skrev README.
- Startade den här loggboken.

**Vad som gick fel:**

**Hur jag löste det:**

**Vad jag lärde mig:**

**Källor:**

**Nästa steg:**

Ta reda på hur en .als faktiskt ser ut inuti och anteckna vad jag hittar - hitta sökvägar, plugin-referenser, live-version och format osv.