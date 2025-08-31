**Languages / Lingue:** [English](#description-english) | [Italiano](README_it.md)
# 🛠️ GitPyVersion

*Versione*: 1.0
*Licenza*: Freeware
*Copyright © 2025 AlandLab*

---

## 📝 Descrizione

GitPyVersion è un'utility da riga di comando per Windows che verifica le versioni installate di `Git` e `Python` e se sono disponibili aggiornamenti, permette di scaricarli e installarli rapidamente.

---

## ✨ Caratteristiche principali

- Verifica le versioni di Git e Python installate sul sistema.
- Estrae automaticamente le ultime versioni disponibili dalle pagine ufficiali di Git e Python.
- Se richiesto, scarica e installa le nuove versioni (`-d` per scaricare, `-di` per scaricare e installare).
- Installa Git e/o Python anche se mancanti sul sistema.
- Mostra una barra di progresso durante i download.

---

## ⚡ Installazione

1. Scarica l’ultima versione di `GitPyVersion`.
2. Copia il file in una cartella a tua scelta.
3. Puoi rinominare l'eseguibile in un nome più breve, ad esempio gpv.exe, tutte le opzioni si adatteranno automaticamente al nuovo nome.

* La ridistribuzione con nome modificato non è consentita.

---

## 💡 Uso
```
GitPyVersion.exe [opzione] [target]
```

### ⚙️ Opzioni

| Opzione           | Descrizione                                                                   |
| ----------------- | ----------------------------------------------------------------------------- |
| `-h`, `--help`    | Mostra questo messaggio di aiuto.                                             |
| `-v`, `--version` | Mostra la versione del programma.                                             |
| `-l`, `--license` | Mostra la licenza e le istruzioni per visualizzare le licenze di terze parti. |
| `-d`              | Scarica l’aggiornamento per il target.                                        |
| `-di`             | Scarica e installa l’aggiornamento per il target.                             |
| `-ad`             | Scarica gli aggiornamenti per entrambi i target.                              |
| `-adi`            | Scarica e installa gli aggiornamenti per entrambi i target.                   |

### 🎯 Target

| Target         | Descrizione      |
| -------------- | ---------------- |
| `git`          | Aggiorna Git.    |
| `py`, `python` | Aggiorna Python. |

---

## 📌 Esempi

- Scarica l'aggiornamento per Git: `GitPyVersion.exe -d git`  
- Scarica e installa l'aggiornamento per Python: `GitPyVersion.exe -di py`  
- Scarica gli aggiornamenti per Git e Python: `GitPyVersion.exe -ad`  
- Scarica e installa gli aggiornamenti per Git e Python: `GitPyVersion.exe -adi`

---

## ✍️ Autore

AlandLab
✉️ [AlandLab3@Gmail.com](mailto:AlandLab3@Gmail.com)  
📍 (PV) Italia

---

## 🔄 Controllo aggiornamenti futuri

Nel caso sorgessero problemi nel rilevamento delle versioni, verificare eventuali aggiornamenti di GitPyVersion.

---

## 🛡️ Licenza

*Questo software è rilasciato gratuitamente e può essere utilizzato e ridistribuito senza modifiche.*
*Per dettagli completi, vedi `LICENSE.txt` e `THIRD_PARTY_LICENSES.txt`.*
