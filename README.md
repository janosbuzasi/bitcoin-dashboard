
# Bitcoin Dashboard

Ein privates Dashboard zum Verfolgen von Bitcoin-Preisen, Blockchain-Netzwerkaktivitäten und Kursreaktionen, ähnlich wie auf Yahoo Finance oder Google.

## Funktionen

- **Live-Bitcoin-Kursanzeige**: Verfolgt den aktuellen Bitcoin-Preis in Echtzeit.
- **Diagramme für Preisentwicklung**: Zeigt historische Bitcoin-Preisbewegungen in einem grafischen Format an.
- **Netzwerkstatistiken**: Zeigt wichtige Blockchain-Metriken wie Transaktionsvolumen, Hashrate und Netzwerkgebühren.
- **Benachrichtigungen**: Optionales Feature zur Benachrichtigung bei bestimmten Kursänderungen.

## Technologien

Das Projekt verwendet die folgenden Technologien:

- **Frontend**: HTML, CSS, JavaScript
- **API**: CoinGecko API (für Preis- und Marktdaten), CoinMarketCap oder Binance API
- **Charts**: Chart.js für die Visualisierung der Kursentwicklung
- **Versionskontrolle**: Git und GitHub

## Voraussetzungen

Um das Dashboard lokal auszuführen, benötigst du folgende Tools:

- [Node.js](https://nodejs.org/en/) (falls du einen Server oder weitere Backend-Funktionalitäten hinzufügen möchtest)
- Git für Versionskontrolle
- Ein API-Schlüssel von [CoinGecko](https://www.coingecko.com/de/api) oder [CoinMarketCap](https://coinmarketcap.com/api/) für den Zugriff auf Kursdaten (optional)

## Installation

1. **Repository klonen**:
   ```bash
   git clone https://github.com/username/bitcoin-dashboard.git
   cd bitcoin-dashboard
   ```

2. **Abhängigkeiten installieren** (optional, falls du Node.js verwendest):
   ```bash
   npm install
   ```

3. **Starten**:
   - Öffne die `index.html` im Browser oder starte den Server mit Node.js (falls ein Server verwendet wird):
   ```bash
   node server.js
   ```

## Verwendung

- Besuche die Seite im Browser, um den aktuellen Bitcoin-Preis und die Preisentwicklung in Echtzeit zu verfolgen.
- Verwende die API-Schlüssel von CoinGecko oder CoinMarketCap, um die Kursdaten zu personalisieren.
- Das Dashboard aktualisiert sich automatisch bei Änderungen.

## Geplante Erweiterungen

- **Mobile-Optimierung**: Verbesserung der Darstellung für mobile Geräte.
- **Weitere Kryptowährungen**: Unterstützung für zusätzliche Kryptowährungen.
- **Benachrichtigungsfunktion**: E-Mail oder SMS-Benachrichtigungen bei starken Kursänderungen.

## Lizenz

Dieses Projekt steht unter der MIT-Lizenz. Weitere Informationen findest du in der [LICENSE](LICENSE)-Datei.
