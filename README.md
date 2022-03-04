# Installation (trin-for-trin)

💡 **Sådan kommer du i gang med Moodygrams.dk**

**_OBS!_** _Det er ikke meningen, at du skal vide alt om, hvad du skal i denne guide._

---

**Trin:**

1. Download alle filer fra Github
2. Placer filerne et sted, der ikke synces med iCloud mm. og åbn projektet i VS Code
3. Åbn Terminalen i VS Code og kør et par kodestumper
4. Kør dev-server via Terminalen - og sluk igen:-)
6. Git shit: 
    Opret et repo på git
    Git init (initialiser git repo)
    git add --all
    git commit -m “beskrivelse af dit commit”
    git branch -M main
    git remote add origin https://github.com/stefangrage/moodygramstest.git (dit git repo)
    git push -u origin main

    Derefter kan du pushe og pulle til git som normalt
5. Brug Tailwind

---

## 1. Hent filer

Download filer fra: (link)

---

## 2. Åbn projekt



---

## 3. Åbn Terminalen i VS Code

Åbn terminalen via **View** i VS Code, og kopier derefter følgende kode ind i terminal-vinduet og tryk _Enter_

```
npm install
```

<details>
    <summary>Se eksempel</summary>

![SCR-20220119-lgw.png](/README/SCR-20220119-lgw.png)
![npm-i.jpg](/README/npm-i.jpg)

</details>

---

## 4. Kør dev-server via Terminalen

Setuppet virker ikke med den traditionelle Live-Sever. Så derfor skal vi køre vores egen dev-server. Det gør du ved at kopiere følgende ind i terminal-vinduet efterfulgt af _Enter_

```
npm run dev
```

💡 **OBS!** — Nogle gange er det nødvendigt at stoppe serveren, hvilket gøres ved at indtaste `ctrl+c` i terminal-vinduet.
Hvis du skal starte serveren igen, brug da `npm run dev` igen.

---

## 5. Brug Tailwind

Begynd at bruge Tailwinds hjælpeklasser til at style dit indhold. Find `index.html` under mappen `src`.

Navigér derefter til [Tailwinds dokumentation](https://tailwindcss.com/docs/), for at se alle hjælpeklasser samt øvrige opsætningsmuligheder.

![Untitled](/README/Untitled.png)

## NÆSTE. Note til selv: Fjern dark mode med regexp:
Søg efter:
dark:[a-z0-9-:]*

Vælg alle matches med option + enter
Slet alle options med option + delete

Så er dark mode væk:-)