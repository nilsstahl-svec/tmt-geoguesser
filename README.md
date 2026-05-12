# TMT Geoguessr Prototyp

Das ist ein einfacher Test-Prototyp mit:

- drei festen Block-Seiten:
  - /block-rot/
  - /block-blau/
  - /block-gruen/
- einer Regie-Seite:
  - /regie/
- drei Testfragen
- Live-Auswertung über Firebase Firestore

## Wichtig

GitHub Pages allein speichert keine Antworten. Dafür brauchst du Firebase Firestore.

## Schritte

1. Firebase-Projekt erstellen.
2. In Firebase eine Web-App anlegen.
3. Firestore Database aktivieren.
4. Die Firebase-Konfiguration in `firebase-config.js` eintragen.
5. Dateien in dein GitHub-Repo hochladen.
6. GitHub Pages aktivieren.
7. Mit mehreren Handys testen.

## Test-Links

Wenn dein Repo z. B. `tmt-geoguessr` heißt:

- `https://nilsstahl-svec.github.io/tmt-geoguessr/block-rot/`
- `https://nilsstahl-svec.github.io/tmt-geoguessr/block-blau/`
- `https://nilsstahl-svec.github.io/tmt-geoguessr/block-gruen/`
- `https://nilsstahl-svec.github.io/tmt-geoguessr/regie/`

## Hinweis zu Sicherheit

Dieser Prototyp ist bewusst simpel. Für den echten Abend sollte man noch ergänzen:

- Fragen nur freigeben, wenn die Moderation sie aktiviert.
- Pro Gerät möglichst nur eine Antwort pro Frage zulassen.
- Firestore-Regeln sauber setzen.
- Test mit vielen Handys machen.
