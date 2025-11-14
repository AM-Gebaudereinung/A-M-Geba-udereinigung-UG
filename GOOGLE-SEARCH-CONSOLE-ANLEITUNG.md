# Google Search Console - Schritt-für-Schritt Anleitung

## 📋 Wichtig: Voraussetzungen
- ✅ Ihre Website muss online gehostet sein
- ✅ Sie benötigen ein Google-Konto
- ✅ Sie benötigen Zugriff auf Ihre Domain (für Verifizierung)

---

## 🚀 Schritt 1: Google Search Console öffnen

1. Gehen Sie zu: **https://search.google.com/search-console**
2. Melden Sie sich mit Ihrem Google-Konto an
3. Falls Sie noch kein Konto haben, erstellen Sie eines unter: https://accounts.google.com/signup

---

## 📝 Schritt 2: Property hinzufügen

1. Klicken Sie oben links auf **"Property hinzufügen"**
2. Wählen Sie **"URL-Präfix"**
3. Geben Sie Ihre Domain ein:
   ```
   https://am-gebaudereinigung.de
   ```
4. Klicken Sie auf **"Weiter"**

---

## ✅ Schritt 3: Domain verifizieren

Sie haben mehrere Optionen zur Verifizierung. Wir empfehlen **Methode 1 oder 2**:

### **Methode 1: HTML-Datei hochladen (EINFACHSTE)**
1. Google gibt Ihnen eine Datei: `google######.html`
2. Laden Sie diese Datei in das **Root-Verzeichnis** Ihrer Website hoch
   - Pfad: `https://am-gebaudereinigung.de/google######.html`
3. Klicken Sie auf **"Verifizieren"**

### **Methode 2: HTML-Tag (ALTERNATIVE)**
1. Kopieren Sie den HTML-Meta-Tag den Google anbietet
2. Fügen Sie ihn im `<head>` Bereich Ihrer `index.html` ein:
   ```html
   <meta name="google-site-verification" content="HIER_DER_CODE" />
   ```
3. Speichern, hochladen und klicken Sie auf **"Verifizieren"**

### **Methode 3: DNS-Eintrag**
1. Melden Sie sich bei Ihrem Domain-Provider an (z.B. GoDaddy, Strato, etc.)
2. Fügen Sie den DNS TXT-Record hinzu, den Google anbietet
3. Warten Sie 24-48 Stunden auf Propagation

---

## 📍 Schritt 4: Sitemap einreichen

1. Nach erfolgreicher Verifizierung gehen Sie auf die **Property-Startseite**
2. Klicken Sie im Menü auf: **"Sitemaps"** (Menü → Sitemaps)
3. Geben Sie folgende URL ein:
   ```
   https://am-gebaudereinigung.de/sitemap.xml
   ```
4. Klicken Sie auf **"Senden"**
5. Warten Sie, bis der Status auf **"Erfolg"** wechselt

---

## 🔍 Schritt 5: Index-Anfrage (Optional)

1. Gehen Sie zu **"URL-Inspektion"**
2. Geben Sie ein:
   ```
   https://am-gebaudereinigung.de
   ```
3. Klicken Sie auf **"Indexierung anfordern"**
4. Wiederholen Sie das für weitere Seiten:
   - https://am-gebaudereinigung.de/ueber-uns
   - https://am-gebaudereinigung.de/leistungen
   - https://am-gebaudereinigung.de/kontakt

---

## 📊 Schritt 6: Überwachung

Nach der Einrichtung können Sie in der Search Console folgende Daten sehen:
- **Leistung**: Klicks, Impressionen, Suchmaschinen-Rankings
- **Coverage**: Welche Seiten indexiert sind
- **Mobile Usability**: Sind Ihre Seiten mobil-freundlich?
- **Sicherheitsprobleme**: Falls vorhanden

---

## ⏱️ Wie lange dauert es?

- **Verifizierung**: 5 Minuten - 24 Stunden
- **Sitemap-Verarbeitung**: 1-7 Tage
- **Indexierung**: 1-4 Wochen
- **Ranking**: 4-12 Wochen

---

## 💡 Tipps für besseres Google-Ranking

1. **Qualitativ hochwertige Inhalte** schreiben
2. **Keywords** in Titel und Beschreibung nutzen
3. **Mobile-Freundlich** sein (✓ bereits erledigt)
4. **Schnelle Ladezeiten** (Bilder optimieren)
5. **Backlinks** von anderen Websites erhalten
6. **Regelmäßig aktualisieren** (Blog-Artikel)
7. **Strukturierte Daten** nutzen (✓ bereits erledigt)

---

## 🆘 Probleme?

Falls Sie Probleme haben:
- Überprüfen Sie, dass Ihre Website **online ist**
- Verifizieren Sie die **korrekte Domain**
- Warten Sie **24 Stunden** nach Verifizierung
- Überprüfen Sie die **robots.txt** in der Search Console
- Nutzen Sie das **URL-Inspektions-Tool** zur Fehlersuche

---

## 📞 Kontakt

Für Fragen:
- **E-Mail**: info@am-gebaudereinigung.de
- **Telefon**: +49 123 456789

---

**Viel Erfolg bei der Einrichtung!** 🎉
