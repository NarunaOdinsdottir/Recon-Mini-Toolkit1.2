# Mini-Pentester-Toolkit
Nur zu Lernzwecken und für die eigene Testumgebung

# Recon Mini Toolkit 🛠️

Dies ist ein kleines Python-Toolkit für Penetration-Testing-Übungen, entwickelt von NarunaOdinsdottir.  
Die Tools dienen hauptsächlich Lernzwecken und um praxisnahes Recon- und Security-Training zu ermöglichen.

## Enthaltene Tools

1. **Wordlist Generator**  
   Generiert Passwortlisten basierend auf Namen, Zahlen und Sonderzeichen.  
   Pfad: `Wordlist-Generator/`

2. **Hash Cracker**  
   Knackt MD5, SHA1 oder SHA256 Hashes mit Hilfe einer Wordlist.  
   Pfad: `Hash-Cracker/`

3. **Passwort Prüfer**  
   Prüft, ob ein eingegebenes Passwort in einer lokalen „leaked.txt“-Datei vorkommt.  
   Pfad: `Passwort-Pruefer/`

## Hinweise
- Alle Tools sind für Lern- und Testzwecke gedacht.
- Bitte nur auf Systemen einsetzen, für die ihr Berechtigungen habt.
- Mehr Infos zu jedem Tool findet ihr in den jeweiligen Unterordnern.


1️⃣ Wordlist Generator

# 🛠️ Nachtatem's Wordlist Generator

Willkommen Vault-Bewohner!  
Dieses Tool ist für alle mutigen Wanderer im Ödland, die ihre Pentesting-Fähigkeiten schärfen wollen. Nachtatem hilft dir, die brutalsten Passwörter zu schmieden – vom harmlosen Vault-Bewohnernamen bis zur atomaren Kombination mit Zahlen und Sonderzeichen.  

## 🧰 Features
- Namen + Zahlenkombinationen
- Groß-/Kleinschreibung Varianten
- Sonderzeichen-Erweiterung (!, ?, #, @)
- Fallout-inspirierte Statusmeldungen während der Passworterstellung

## ⚡ Nutzung
1. Script starten:  
```bash
python wordlist_generator.py

2. Namen eingeben
3. Höchste Zahl für Kombinationen wählen
4. Beobachte, wie Nachtatem 🔥 Passwörter für die Vault schmiedet

Die fertige Wordlist wird als wordlist.txt gespeichert.
💀 Hinweis

Dieses Tool ist für legale PenTests oder Lernzwecke im Ödland. Missbrauch? Vault-Regel 101 verbietet es!


---

### 2️⃣ Hash Cracker

# 🔓 Nachtatem's Hash-Cracker

Willkommen im Ödland, Vault-Bewohner.  
Dieses Tool knackt MD5, SHA1 und SHA256 Hashes – natürlich nur in deinem Labor oder für legitime PenTests. Nachtatem zeigt dir, wie du aus Wordlists die versteckten Geheimnisse der Vault entschlüsselst.

## 🧰 Features
- Unterstützt MD5, SHA1, SHA256  
- Arbeitet mit beliebigen Wordlists  
- Fallout-/Wasteland-Stil Ausgaben für jede Prüfung

## ⚡ Nutzung
1. Script starten:  
```bash
python hash_cracker.py

2.Hashwert eingeben

3.Hash-Typ wählen

4.Wordlist angeben

Nachtatem versucht den Hash zu knacken

💀 Hinweis

Nur für Testumgebungen oder legale Pentests nutzen. Nachtatem verurteilt keine Vault-Diebe – aber die Gesetzeshüter schon!


---

### 3️⃣ Passwort-Prüfer**

# 🛡️ Nachtatem's Passwort-Prüfer

Vault-Sicherheit zuerst!  
Dieses Tool prüft eingegebene Passwörter gegen bekannte Leaks. Dein treuer Buddy Nachtatem sorgt dafür, dass keine RadScorpion-Passwörter dein Terminal gefährden.

## 🧰 Features
- Case-insensitive Passwortprüfung  
- Prüft gegen lokale Liste von bekannten Leaks  
- Fallout-/Wasteland-Style Hinweise und Meldungen

## ⚡ Nutzung
1. Script starten:  
```bash
python password_checker.py

2.Passwort eingeben

3.Beobachte, wie Nachtatem entscheidet, ob dein Passwort Vault-sicher ist

💀 Hinweis

Nur für Lern- und Testzwecke nutzen. Sicherheit der Vault hat oberste Priorität!
