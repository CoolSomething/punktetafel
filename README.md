# Punktetafel 11

Schüler tragen ihre Notenpunkte (0–15) pro Fach ein. Pro Fach wird der Schnitt gebildet, alle Fachschnitte werden addiert, und das Scoreboard sortiert nach dieser Summe.

- Hosting: GitHub Pages (statische Dateien aus diesem Repo)
- Login: Firebase Authentication (E-Mail/Passwort; der Username wird intern als <username>@punktetafel.app gespeichert, es werden keine Mails verschickt)
- Daten: Cloud Firestore, Collection `scores`, ein Dokument pro Nutzer (ID = UID)
- Sicherheitsregeln: `firestore.rules` (in der Firebase-Konsole unter Firestore > Regeln einfügen)

Auf dem Scoreboard erscheint nur der selbst gewählte Spitzname.
