UPDATE 07.11.2026 – DATENSCHUTZ ERWEITERT

Die Datei datenschutz.html ist nun als ausführlicher, ohne sichtbare Platzhalter
formulierter Datenschutz-ENTWURF enthalten. Behandelt werden:
- Betreiberin und Kontakt
- GitHub-Pages-Hosting/IP-Protokollierung und Drittländer
- Kein eigenes Cookie-Tracking, kein Kontaktformular auf dieser statischen Site
- E-Mail-Anfragen und Aufbewahrungskriterien
- Lokale Videoverarbeitung
- Nur optionale, freigabeabhängige TikTok-OAuth- und Content-Posting-Funktionen
- Datenschutzrechte/Beschwerdemöglichkeit

WICHTIG: Dies ist keine anwaltlich geprüfte Datenschutzberatung.
VOR Veröffentlichung bitte prüfen, ob der beschriebene technische Ablauf
mit der jeweils installierten Desktop-Version übereinstimmt – insbesondere
TikTok-Token-Speicherung, Account-Trennung, Löschung, Datenabrufe und etwaige
zusätzliche Analysedienste. Wenn die App mehr Daten überträgt als hier
beschrieben, MUSS der Text vor der Freigabe angepasst werden.

Daneben offen: Der Entwurfs-Hinweis in nutzungsbedingungen.html und die
Frage eines zusätzlichen schnellen elektronischen Kontaktwegs im Impressum.
Daher nicht als juristisch endgültig geprüft darstellen.

GitHub: Die Adresse und Kontakt-E-Mail sind durch Veröffentlichung in
einem PUBLIC Repository weltweit sichtbar, ggf. dauerhaft in Git-Historie.

GITHUB PAGES: Alle Dateien im ZIP (außer README, der auch hochgeladen werden
kann, aber nicht nötig ist) direkt ins Root von Repository
nina-creator-studio-web hochladen. Nicht den übergeordneten Ordner.

Unter Repository > Settings > Pages > Deploy from branch > main > / (root)
GitHub Pages aktivieren. Danach erst die drei echten HTTPS-URLs bei
TikTok hinterlegen und deren Eigentumsprüfung durchführen.

TIKTOK:
Description: Manage and edit gameplay videos, create short clips, and prepare social media posts in one desktop app.
Platform: Desktop
Login Kit Redirect URI: http://127.0.0.1:8791/callback
Website: tatsächliche GitHub Pages Root-URL
Terms: tatsächliche Root-URL + nutzungsbedingungen.html
Privacy: tatsächliche Root-URL + datenschutz.html

TikTok genehmigt nach seinen aktuellen Review-Regeln keine reine
Eigengebrauchs-App für öffentliches Direct Posting. Eine veröffentlichte
Website garantiert KEINE API-Genehmigung.
