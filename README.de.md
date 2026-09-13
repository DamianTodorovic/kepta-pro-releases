<p align="center"><img src="kepta-logo.svg" width="96" alt="KEPTA"></p>
<h1 align="center">KEPTA Enterprise</h1>
<p align="center"><strong>Deine KI vergisst dich nach jedem Chat.<br>KEPTA erinnert sich — auf deinem eigenen Rechner, in einer verschlüsselten Datei.</strong></p>

<p align="center"><sub>Die Desktop-App für das Gedächtnis deiner KI · lokal · verschlüsselt · keine Cloud · kein Konto · keine Telemetrie</sub></p>

<p align="center">
  <a href="https://github.com/DamianTodorovic/kepta-enterprise-releases/releases/latest"><img alt="Download" src="https://img.shields.io/github/v/release/DamianTodorovic/kepta-enterprise-releases?label=Download&color=b3543f"></a>
  <img alt="macOS" src="https://img.shields.io/badge/macOS-Apple%20silicon%20%7C%20Intel-lightgrey">
  <img alt="Verschlüsselt" src="https://img.shields.io/badge/verschl%C3%BCsselt-SQLCipher%204%20%C2%B7%20AES--256-green">
  <img alt="MCP" src="https://img.shields.io/badge/MCP-Claude%20%C2%B7%20Cursor%20%C2%B7%20jeder%20Client-blue">
  <a href="https://github.com/DamianTodorovic/kepta"><img alt="Offener Kern" src="https://img.shields.io/badge/offener%20Kern-AGPL--3.0-blue"></a>
</p>

<p align="center">
  <a href="https://github.com/DamianTodorovic/kepta-enterprise-releases/releases/latest"><b>⬇️ Für den Mac herunterladen</b></a> &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/damian-todorovic-244235434"><b>🔑 Lizenz holen</b></a> &nbsp;·&nbsp;
  <a href="README.md"><b>🇬🇧 English</b></a>
</p>

<p align="center"><img src="docs/demo.gif" alt="Der Wissensgraph von KEPTA Enterprise wechselt zwischen seinen zwei Ansichten: Force, in der verbundene Notizen sich physikalisch zusammenfinden, und Tree, ein Baum von der Wurzel über die Wissensart bis zur Notiz" width="900"></p>

---

## 😩 Kennst du das?

Du erklärst ChatGPT oder Claude dein Projekt. Deinen Mandanten. Die Entscheidung von letzter Woche und warum. Wie du Dinge gern erledigt hast.

Am nächsten Tag öffnest du einen neuen Chat — und er weiß nichts davon. Also erklärst du es wieder. Und wieder. Jeder Assistent, jeder Chat, jeden Tag.

## ✨ Mit KEPTA weiß er es einfach

- **Du sagst Claude, dass dein Mandant quartalsweise abrechnet.** Zwei Wochen später fragst du in einem ganz neuen Chat nach der Rechnung — und er weiß es schon.
- **Du legst ein PDF in einen Ordner.** Dein Assistent zitiert daraus.
- **Du ziehst um.** Die neue Adresse ersetzt die alte, und die alte kommt nicht mehr zurück — sie bleibt als Verlauf erhalten, wird aber nie mehr als aktuell ausgegeben.
- **Du fragst dich, was du im März wusstest.** Zieh den Zeitregler zurück, und dein Wissensgraph zeigt genau diesen Tag.
- **Du wechselst von Claude zu Cursor.** Dasselbe Gedächtnis. Was ein Assistent lernt, weiß der nächste schon.

Du musst ihn nie briefen. Auf deinem Rechner liegt eine Datei; deine Assistenten lesen darin und schreiben hinein, während du arbeitest — von selbst.

## 👀 So sieht es aus

| Alles, was du weißt, nach Art geordnet | Suche, die nach Bedeutung sortiert |
|---|---|
| ![Der Index von KEPTA Enterprise](docs/screenshots/01-index.png) | ![Die Suche in KEPTA Enterprise](docs/screenshots/06-search.png) |
| **Der Wissensgraph — jede Notiz ein Knoten, jeder Link eine Kante** | **Dasselbe Wissen als Baum** |
| ![Der Wissensgraph, Ansicht Force](docs/screenshots/03-graph.png) | ![Der Wissensgraph, Ansicht Tree](docs/screenshots/04-dendrogram.png) |
| **Der Editor — Wissensart, `[[Links]]`, Gültigkeit** | **Einstellungen — Systemstatus, Verschlüsselung, Device Sync** |
| ![Der Editor](docs/screenshots/04-editor.png) | ![Die Einstellungen mit dem Systemstatus](docs/screenshots/05-setup.png) |

<sub>KEPTA Enterprise 2.11 mit einem erfundenen Demo-Bestand — jeder Name und jeder Eintrag ist für diese Bilder ausgedacht.</sub>

## 💎 Warum es sich anders anfühlt

| | |
|---|---|
| 🧠 **Ein Gehirn für jede KI** | Claude Desktop, Cursor und jeder andere MCP-Client teilen dasselbe Gedächtnis. Der MCP-Server steckt in der App — kein Node.js, kein npm, ein Block zum Einfügen. |
| 🕰️ **Wissen mit Datum** | Jede Erinnerung hat ein Gültigkeitsfenster und eine Konfidenz. Ein neuer Fakt löst den alten ab; abgelaufenes Wissen wird markiert statt als aktuell ausgegeben. |
| 🔍 **Suche, die versteht, was du meinst** | Volltext, Bedeutung (Vektoren) und Wissensgraph in einer Rangfolge. Der beste Treffer steht oben — für dich und für deine Agenten, über denselben Code. |
| 🕸️ **Du siehst, was du weißt** | Ein interaktiver Wissensgraph in zwei Ansichten, Force und Tree, mit Zeitregler. Er bleibt flüssig bei 3 000 Notizen und 9 500 Verbindungen, mit 60 fps. |
| 📥 **Alles kommt mühelos hinein** | PDFs und Dokumente hineinziehen, Webseiten ausschneiden, einen Eingangsordner beobachten, ein Obsidian-Vault importieren — oder KEPTA die Dokumente finden lassen, die schon auf deinem Rechner liegen, mit Vorschau vorher. |
| 🔒 **Deins, und nur deins** | Eine verschlüsselte Datei auf deiner Festplatte. Der Schlüssel liegt im macOS-Schlüsselbund. Kein Konto, keine Telemetrie, keine Cloud — KEPTA ruft nirgends an, nicht einmal zur Lizenzprüfung. |

## 🧩 Alles, was KEPTA Enterprise kann

<details open>
<summary><strong>🔒 Sicherheit &amp; Datenschutz</strong></summary>

- **Verschlüsselt auf der Festplatte** — SQLCipher-4-Format: AES-256 und ein HMAC-SHA512 über jede Seite, das Write-Ahead-Log eingeschlossen. Wer nur die Datei hat, hat nichts Lesbares
- **Der Schlüssel wird automatisch erzeugt und im Schlüsselbund des Systems verwahrt** — kein Passwort zu tippen, und deine Agenten sehen ihn nie
- **Wiederherstellungsschlüssel mit einem Klick** (*Settings → System status*), bereit für deinen Passwort-Manager
- **Deine Einstellungen liegen in der verschlüsselten Datei** — der Schlüssel für deinen KI-Anbieter eingeschlossen
- **Nichts verlässt deinen Rechner**, außer du wählst im Chat eine Cloud-KI: die App lauscht nur auf `127.0.0.1`, ohne Konto und ohne Telemetrie
- **Gehärtete Desktop-Hülle** — kein Node im Fenster, Sandbox an, strenge Content Security Policy
- Ratenbegrenzung, Helmet und Eingabeprüfung auf jeder Route
- **Deine Daten sind nie Geisel:** ohne gültige Lizenz bleibt das Fenster gesperrt — nie die Daten. Die Datei bleibt auf der Festplatte, verschlüsselt, und lesbar für den [offenen Kern](https://github.com/DamianTodorovic/kepta)

</details>

<details open>
<summary><strong>📝 Notizen</strong></summary>

- Anlegen, bearbeiten, löschen — **ein echter Papierkorb mit Wiederherstellen**, nie endgültiges Löschen
- **Vier Wissensarten** — Fakt, Ereignis, Anleitung, Dokument — vergeben nach lesbaren Regeln, die ihren Grund nennen
- **Bestehende Notizen nachträglich nach Art sortieren**, mit Vorschau, bevor sich etwas ändert
- Tags, eine Konfidenz von 0 bis 1 und **automatisch erkannte Entitäten**
- **Scopes** — Nutzer, Agent, Sitzung — damit jede Erinnerung weiß, wem sie gehört
- **Gültigkeitsfenster** — abgelaufene Notizen werden markiert, nie still versteckt
- **Ablöseketten** — ein neuer Fakt verdrängt den alten, der Verlauf bleibt

</details>

<details open>
<summary><strong>📥 Aufnehmen &amp; importieren</strong></summary>

- **Dateien per Drag &amp; Drop** — PDF (mit den Zeichentabellen eingebetteter Schriften, damit Formulare als Buchstaben lesbar sind), Markdown, Text und JSON, in lesbare Teile zerlegt
- **Eingangsordner**, beobachtet und automatisch übernommen
- **Obsidian-Vault-Import** — Frontmatter bleibt erhalten, `[[Wiki-Links]]` werden Kanten im Graphen
- **URL-Clipper** — geschützt gegen Anfragen ins lokale Netz, entfernt Navigationszeilen und Cookie-Banner
- **Diesen Rechner durchsuchen** — nur auf Wunsch, Vorschau zuerst; Schlüssel, Zugangsdaten, Browserprofile, Schlüsselbunde und Wallets bleiben immer gesperrt
- **Auto-Learn** — den Kern einer Chat-Antwort als Notiz speichern (standardmäßig aus)
- **Importierte Dateien neu lesen**, wenn sie mit einer älteren Extraktion kamen — erst zählen, schreiben erst nach deiner Bestätigung
- **JSON-Import** ganzer Notizsammlungen, **Markdown-Export** in einen Ordner
- **Device Sync** — einen Scope zwischen deinen eigenen Geräten verschieben, als AES-256-GCM-verschlüsseltes Paket, mit einem manipulationssicheren Protokoll jeder Übertragung als Hash-Kette

</details>

<details open>
<summary><strong>🔍 Suche</strong></summary>

- **Hybride Suche** — Volltext (BM25), Vektoren und Entitäten, verschmolzen mit Reciprocal Rank Fusion
- **Lokales Nachsortieren** — Begriffsabdeckung, Phrasen, Titel und Tags; ohne Netz
- **Relevanz zuerst** — sobald du suchst, steht der beste Treffer oben
- **Suche nach Bedeutung** mit einem lokalen Modell über [Ollama](https://ollama.com), im Hintergrund berechnet — oder abschalten und nach Wörtern suchen
- **Ein Ergebnisregler** von 5 bis alle, und der Index sagt dir, wie viele Notizen passen
- **Zeitreise-Suche** — frag, was zu einem beliebigen Zeitpunkt bekannt war, über die API und MCP
- **Zeitliche Gewichtung** — abgelaufene Fakten zählen halb, abgelöste weniger
- **Stoppwörter auf Deutsch und Englisch**, damit eine Notiz nicht gewinnt, nur weil *die* oder *with* darin steht
- **Ein einziger Codepfad** für App, HTTP-API und MCP — deine Agenten bekommen genau die Qualität, die du bekommst

</details>

<details open>
<summary><strong>🕸️ Wissensgraph</strong></summary>

- **Zwei Ansichten** — *Force*, das physikalische Layout, und *Tree*, ein Baum von der Wurzel über die Wissensart bis zur Notiz; die Knoten gleiten von einer zur anderen
- **Eine unbegrenzte Fläche** — 3 000 Knoten und 9 500 Kanten bei 60 fps; zoomen, verschieben, ziehen, alles einpassen
- **Zeitregler** — der Graph, wie er an einem beliebigen Tag aussah
- **Farbe nach Art, Größe nach Verbindungen**, echte Links unterscheidbar von bloßer Ähnlichkeit
- Entitäten und Beziehungen aus `[[Wiki-Links]]` und automatischer Erkennung; **Doppelklick öffnet die Notiz**

</details>

<details open>
<summary><strong>🧹 Pflege</strong></summary>

- **Dubletten erkennen** nach Bedeutung, mit einem wortbasierten Ersatz, wenn kein lokales Modell läuft
- **Dubletten prüfen** — Gruppen nebeneinander, die reichste Fassung mit einem Klick behalten, ein Rückgängig für den ganzen Stapel
- **Zusammenführen löst ab, statt zu löschen** — nichts geht je verloren
- **Episodische Erinnerungen** wachsen aus deinem Chatverlauf
- **Aktivitätsverlauf** — was gespeichert wurde, von wem, wann

</details>

<details open>
<summary><strong>🤖 Agenten (MCP)</strong></summary>

- **Der MCP-Server steckt in der App** — Claude Desktop, Cursor und jeder MCP-Client verbinden sich ohne Node.js und ohne npm
- **MCP 2026-07-28**, kompatibel mit 2025-06-18 und 2024-11-05 — stdio und Streamable HTTP
- **Acht Werkzeuge** — suchen, speichern, ändern, löschen, auflisten, Graph, zusammenführen, vergessen — jedes mit `outputSchema` und `structuredContent`
- **Schreibschranke** (auf Wunsch) — ein lokales Modell entscheidet ADD, UPDATE, DELETE oder NOOP, bevor eine neue Erinnerung gespeichert wird, damit deine Agenten keine Dubletten stapeln
- Auch einzeln: der quelloffene Server auf npm (`kepta-mcp`, gelistet in der offiziellen MCP-Registry) und ein Python-Client (`pip install kepta`)

</details>

<details open>
<summary><strong>💬 Mit deinem Gedächtnis chatten</strong></summary>

- **20 Anbieter-Voreinstellungen** — Ollama, LM Studio, OpenAI, Anthropic, Gemini, Mistral, Groq, DeepSeek, xAI, Perplexity, Together, Fireworks, Cohere, Cerebras, Hugging Face, Novita, OpenRouter, GitHub Models, Azure und ein eigener Endpunkt
- **Modellsuche** für Ollama und LM Studio mit einem Klick, ohne Schlüssel
- **Streaming** mit Stopp-Knopf, Markdown-Darstellung
- **Quellenangaben** — jede Antwort zeigt, welche Erinnerungen sie benutzt hat
- **Datumsbewusste Anfragen** und ein sichtbares Token-Budget

</details>

<details open>
<summary><strong>🖥️ Die App</strong></summary>

- **Eine native App** für deinen Mac — Apple Silicon und Intel
- **Befehlspalette (⌘K)** — alles ohne Maus
- **Wissensliste** mit lesbarer Vorschau, der Quelle als Chip, Teilangaben (2/5) und *Open file*; gruppiert nach Datei, Art oder Zeitraum
- **Tag-Filter** mit Zählern
- **Einrichtungsassistent** mit Starterpaket — in einer Minute bereit
- **Systemstatus** — erkennt lokale KI, prüft den Speicher, zeigt, was fehlt und wie es sich beheben lässt
- **Hell und dunkel**, **Fokusmodus** und **Textgröße** 100 / 115 / 130 %
- **Lizenzschlüssel, offline geprüft** — vom Fenster und vom eigenen Server der App; an deinen Namen gebunden

</details>

## 🎯 Gemacht für Menschen, die täglich mit einer KI arbeiten

**Anwältinnen und Anwälte, Steuerberatung, Arztpraxen, Beratung, Forschung, Entwicklung** — alle, deren Wissen zu wertvoll ist, um es jeden Morgen zu wiederholen, und zu sensibel für den Server eines anderen.

- Dein Gedächtnis ist **eine verschlüsselte Datei auf deinem Rechner** — kein Dienst, kein Abo, kein Konto.
- **Scopes halten Mandanten auseinander**, und Device Sync verschiebt einen Scope nur zwischen *deinen eigenen* Geräten — du trägst die Datei, KEPTA sendet nichts.
- Der Chat ist **aus, bis du einen Schlüssel einträgst**. Erst dann geht, was du sendest, an den Anbieter deiner Wahl — das Gedächtnis selbst wird nie irgendwohin synchronisiert.

## 🛡️ Vertrauen ist gut, Nachprüfen ist besser

- **Die Engine ist Open Source** — [DamianTodorovic/kepta](https://github.com/DamianTodorovic/kepta), AGPL-3.0. Wer belegen muss, dass nichts abfließt, kann sie lesen, statt es zu glauben.
- **Verschlüsselung, die sich prüfen lässt** — die Datei liegt im offenen SQLCipher-4-Format; der Schlüssel berührt nie die Festplatte.
- **Kein Nach-Hause-Telefonieren** — kein Konto, keine Telemetrie; die Lizenz ist eine Ed25519-Signatur, geprüft auf deinem Rechner.
- **Jeder Download hat eine Prüfsumme** — jedes Release nennt die SHA-256 jeder Datei.

## 🚀 So bekommst du KEPTA Enterprise

1. **Lizenzschlüssel holen** — [schreib Damian Todorovic auf LinkedIn](https://www.linkedin.com/in/damian-todorovic-244235434). Der Schlüssel ist an deinen Namen gebunden.
2. **Herunterladen** — die Datei für deinen Mac aus dem [neuesten Release](https://github.com/DamianTodorovic/kepta-enterprise-releases/releases/latest).
3. **Installieren und öffnen** (siehe unten), Name und Schlüssel eintragen — die Aktivierung läuft offline.
4. **Deine KI verbinden** — ein Block, kopiert aus *Settings → MCP / API*.

### 📦 Welche Datei brauche ich?

| Dein Mac | Datei |
|---|---|
| Apple Silicon (M1 und neuer) | `KEPTA-<version>-mac-arm64.dmg` |
| Intel-Prozessor | `KEPTA-<version>-mac-x64.dmg` |

Unsicher? Apple-Menü → *Über diesen Mac*: „Apple M…“ heißt `arm64`, „Intel“ heißt `x64`. Windows oder Linux: [frag mich](https://www.linkedin.com/in/damian-todorovic-244235434).

**Download prüfen:** `shasum -a 256 ~/Downloads/KEPTA-*.dmg` muss die Zahl aus dem Release ausgeben.

### 🍎 Installation auf macOS

1. Die `.dmg` öffnen und **KEPTA** in **Programme** ziehen.
2. KEPTA einmal starten. macOS sagt, der Entwickler lasse sich nicht überprüfen: KEPTA ist noch nicht von Apple notarisiert — dafür braucht es ein kostenpflichtiges Apple-Entwicklerzertifikat. Die App selbst ist ad hoc signiert und unverändert; es fehlt nur Apples Stempel.
3. Einmal freigeben, auf einem der zwei Wege:
   - **Systemeinstellungen → Datenschutz & Sicherheit**, nach unten zur Meldung über KEPTA scrollen, **Trotzdem öffnen** klicken und mit dem Passwort bestätigen — oder
   - im Terminal: `xattr -dr com.apple.quarantine /Applications/KEPTA.app`
4. Namen und Lizenzschlüssel eintragen.

> Ältere Anleitungen sagen: Rechtsklick auf die App und *Öffnen*. Diesen Weg hat Apple in macOS 15 entfernt; nimm einen der zwei oben.

### 🤖 Claude Desktop oder Cursor verbinden

KEPTA bringt seinen eigenen MCP-Server mit — kein Node.js, kein npm. *Settings → MCP / API* zeigt den Block für deine Installation, mit Kopier-Knopf. Für KEPTA in *Programme* lautet er:

```json
{
  "mcpServers": {
    "kepta": {
      "command": "/Applications/KEPTA.app/Contents/MacOS/KEPTA",
      "args": ["/Applications/KEPTA.app/Contents/Resources/app.asar/dist/mcp-server.cjs"],
      "env": { "ELECTRON_RUN_AS_NODE": "1" }
    }
  }
}
```

Für Claude Desktop trägst du den Eintrag `kepta` unter `mcpServers` in `~/Library/Application Support/Claude/claude_desktop_config.json` ein und startest Claude neu. Danach lesen und schreiben alle Agenten dasselbe verschlüsselte Gedächtnis wie die App.

## ❓ Fragen

<details>
<summary><strong>Muss ich Entwickler sein?</strong></summary>

Nein. KEPTA ist ein ganz normales Fenster: eine Liste, ein Suchfeld, eine Einstellungsseite. Claude Desktop verbinden heißt, einen Block in eine Datei einzufügen — der Block liegt fertig zum Kopieren in der App.
</details>

<details>
<summary><strong>Ist das eine Notiz-App?</strong></summary>

Nicht wirklich — und genau darum geht es. Eine Notiz-App wartet darauf, dass du schreibst. KEPTA ist so gebaut, dass dein *Assistent* es füllt und nutzt. Du kannst alles lesen, ändern und ordnen, musst es aber nie.
</details>

<details>
<summary><strong>Mein KI-Assistent hat doch schon ein Gedächtnis. Wozu das?</strong></summary>

Ein eingebautes Chat-Gedächtnis gehört zu einem Assistenten und liegt bei einem Anbieter. KEPTA ist eine Datei auf deinem Rechner, die sich alle Assistenten teilen — mit Wissensarten, Gültigkeit, Quellen und einem Verlauf, den du sehen und korrigieren kannst.
</details>

<details>
<summary><strong>Funktioniert es offline?</strong></summary>

Ja. Dein Gedächtnis, die Suche, der Graph und die Lizenzprüfung laufen auf deinem Rechner. Nur wenn du im Chat einen Schlüssel für eine Cloud-KI einträgst, geht, was du sendest, an diesen Anbieter. Die Suche nach Bedeutung läuft mit einem lokalen Modell über Ollama komplett offline.
</details>

<details>
<summary><strong>Was passiert ohne Lizenz mit meinen Daten?</strong></summary>

Das Fenster bleibt gesperrt — nie die Daten. Deine Wissensbasis bleibt auf der Festplatte, verschlüsselt und lesbar für den quelloffenen Kern; mit deinem Wiederherstellungsschlüssel öffnest du sie auch auf einem neuen Rechner.
</details>

<details>
<summary><strong>Funktioniert es mit deutschen Notizen?</strong></summary>

Ja. Die Oberfläche ist englisch; deutsche Notizen und deutsche Fragen funktionieren so gut wie englische, und die Suche kennt deutsche Stoppwörter. Für die Suche nach *Bedeutung* auf Deutsch ist ein mehrsprachiges lokales Modell wie `bge-m3` die bessere Wahl.
</details>

<details>
<summary><strong>Windows oder Linux?</strong></summary>

Das aktuelle Release ist für macOS. Für Windows oder Linux [schreib mir](https://www.linkedin.com/in/damian-todorovic-244235434).
</details>

## 👋 Wer KEPTA baut

KEPTA baut **Damian Todorovic**. Fragen, eine Lizenz für dich, deine Praxis oder dein ganzes Team: **[schreib mir auf LinkedIn](https://www.linkedin.com/in/damian-todorovic-244235434)**.

## 📄 Lizenz

KEPTA Enterprise ist proprietär — siehe [LICENSE](LICENSE). Die Gedächtnis-Engine darunter ist Open Source unter der AGPL-3.0: [DamianTodorovic/kepta](https://github.com/DamianTodorovic/kepta). Fremdkomponenten und ihre Lizenzen: [THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md).

<p align="center"><sub><strong>KEPTA</strong> — behält, was zählt.</sub></p>
