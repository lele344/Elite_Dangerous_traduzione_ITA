# 🇮🇹 Elite Dangerous — Traduzione Italiana

Traduzione **non ufficiale in italiano** di *Elite Dangerous*, accompagnata da uno strumento dedicato per applicare la localizzazione e mantenerla aggiornata dopo gli aggiornamenti del gioco.

> **Nota:** questo è un progetto amatoriale e non è affiliato, sponsorizzato o approvato da Frontier Developments.

---

## ☕ Supporta il progetto

Se utilizzi questa traduzione e vuoi supportarne lo sviluppo e gli aggiornamenti, puoi offrirmi un caffè:

[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-%E2%98%95-yellow?style=for-the-badge)](https://www.buymeacoffee.com/lele344)

Grazie per il supporto! 

---

## Download

Scarica l'ultima versione completa della traduzione dalla sezione **Releases**:

[Scarica Elite Dangerous — Traduzione Italiana](https://github.com/lele344/Elite_Dangerous_traduzione_ITA/releases/latest)

---

## Avvio

1. Avvia **`Elite Dangerous Italiano Avanzamento.exe`**.
2. Accetta la richiesta **UAC** di Windows.
3. Avvia *Elite Dangerous* e attendi di arrivare al menu principale.
4. Premi **“Applica italiano”** nell'applicazione.

La traduzione verrà applicata ai file del gioco.

---

## Dopo un aggiornamento del gioco

Dopo un aggiornamento di *Elite Dangerous*, alcuni testi potrebbero essere stati aggiunti o modificati.

Per verificare e aggiornare la traduzione:

1. Premi **“Scansiona aggiornamenti”**.
2. Controlla i conteggi mostrati nella schermata.
3. Se **NUOVE RIGHE** e/o **TESTI MODIFICATI** hanno un valore maggiore di zero, premi **“Apri JSON”** accanto alla relativa voce.
4. Nei file JSON aperti, traduci il campo **`it`** di ogni voce.

   Il testo originale inglese è disponibile nel campo:

   - **`en`** → testo inglese attuale
   - **`oldEn`** → precedente testo inglese, nel caso di righe modificate
   - **`previousIt`** → precedente traduzione italiana, utile come riferimento

5. Salva i file JSON modificati.
6. Torna nell'applicazione e premi **“Ricostruisci catalogo italiano completo”**.
7. Se la ricostruzione termina senza errori, premi **“Applica italiano”**.

> 📁 **I file da tradurre vengono mostrati nella GUI con il loro percorso completo.**

---

## ⚠️ Importante

- Modifica **solo il campo `it`** dei file da tradurre.
- Non modificare gli altri campi dei JSON.
- Non spostare o rinominare le cartelle **`tools`** e **`translation`**.
- La procedura di ricostruzione verifica automaticamente la traduzione.
- I testi non tradotti vengono segnalati/bloccati.
- La ricostruzione controlla anche che i **segnaposto** presenti nel testo originale non vengano modificati o rimossi accidentalmente.

---

## Contenuto della cartella

L'applicazione è distribuita in modo da non richiedere installazioni aggiuntive.

- **`Elite Dangerous Italiano Avanzamento.exe`** include il runtime .NET necessario.
- **`node.exe`** è incluso e viene utilizzato per le operazioni di estrazione e ricostruzione.
- Le cartelle **`tools`**, **`translation`** e **`localizzazione`** contengono gli script e i dati richiesti dall'applicazione.

**Non è necessario installare Node.js separatamente.**

---

## Limitazione di responsabilità

Questo progetto è fornito “così com’è”, senza alcuna garanzia esplicita o implicita.

L’utilizzo della traduzione e degli strumenti inclusi avviene a proprio rischio e responsabilità. L’autore non potrà essere ritenuto responsabile per eventuali problemi, malfunzionamenti, perdita o corruzione di dati, modifiche indesiderate ai file di gioco, incompatibilità con aggiornamenti futuri o qualsiasi altro danno diretto o indiretto derivante dall’utilizzo del progetto.

Prima di utilizzare la traduzione è consigliato effettuare un backup dei file importanti.

L’utilizzo del progetto implica l’accettazione di queste condizioni.

---

## Licenze e attribuzioni

Questo software è un **progetto amatoriale non ufficiale** e non è affiliato a Frontier Developments.

### Node.js

Node.js è distribuito secondo la licenza MIT e le licenze dei relativi componenti.

Licenza ufficiale:

https://github.com/nodejs/node/blob/v24.15.0/LICENSE

Una copia delle informazioni di licenza utilizzate dal progetto è disponibile nel file:

**`LICENZE-NODE.txt`**

### .NET

Gli avvisi e le informazioni relative ai componenti .NET distribuiti con l'applicazione sono disponibili nel file:

**`LICENZE-DOTNET.txt`**

---

## Disclaimer

*Elite Dangerous* e tutti i relativi marchi, nomi, contenuti e proprietà intellettuali appartengono ai rispettivi proprietari.

Questo progetto fornisce esclusivamente una **traduzione italiana non ufficiale** e gli strumenti necessari alla sua gestione.

