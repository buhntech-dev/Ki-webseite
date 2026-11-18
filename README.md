Freiburg V2 – Fraktionsverwaltung

Moderne Fraktions-Webseite für den Discord-Bot aus buhntech-dev/DC-Bilder.

Funktionen:
- Discord-OAuth-Anmeldung; nur Mitglieder des verbundenen Discord-Servers
- Dienst anmelden und abmelden
- Fraktionsliste und Mitgliederübersicht
- Dienstzeiten und Protokoll
- Leitung kann Fraktionen anlegen sowie Mitglieder und Ränge verwalten
- Standard: Polizei, Feuerwehr, Rettungsdienst, ADAC, Mechaniker, Taxi, Regierung, Justiz, Ordnungsamt und Presse

Veröffentlichung:
1. GitHub Pages für main im Root-Verzeichnis aktivieren.
2. config.js: FRACTION_API_BASE auf die Railway-Domain des Botdienstes setzen.
3. Im Discord Developer Portal OAuth2 Redirect URL exakt als https://DEIN-RAILWAY-DOMAIN/api/auth/callback eintragen.
4. Railway-Variablen setzen: DISCORD_CLIENT_ID, DISCORD_CLIENT_SECRET, FRACTION_GUILD_ID, FRACTION_SESSION_SECRET (langer zufälliger Wert), FRACTION_API_URL, FRACTION_WEB_URL (https://buhntech-dev.github.io/Ki-webseite).
5. Railway Volume unter /data mounten und FRACTION_DATA_FILE=/data/fractions.json setzen, damit Daten Deployments überleben.

Geheimnisse niemals in GitHub speichern. Das Dashboard wird erst nach Railway-Konfiguration und Deployment nutzbar.