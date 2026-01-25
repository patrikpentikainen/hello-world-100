# COBOL – Hello World

## 🇬🇧 English

This folder contains a simple **Hello World** program written in **COBOL**, compiled using **GnuCOBOL**.

The example is part of the **hello_world_100** project, which demonstrates basic programs in multiple programming languages.

---

### Files

- `hello.cob` – COBOL source file that prints `Hello, World!`

---

### Requirements (Windows)

- MSYS2
- MSYS2 **UCRT64** environment
- GnuCOBOL (`cobc`)

GnuCOBOL is installed via MSYS2 and must be run inside the **UCRT64 shell**.

---

### Required environment variable

When using GnuCOBOL with MSYS2 UCRT64, the following environment variable is required:

```bash
export COB_CONFIG_DIR=/ucrt64/share/gnucobol/config
You can add this permanently to ~/.bashrc.
```

### Compile and run
From the MSYS2 UCRT64 shell, navigate to the cobol directory of the project:

```bash
cd <path-to-project>/hello_world_100/cobol
cobc -x hello.cob
./hello.exe
Replace <path-to-project> with the actual location of the project on your system.
```
### Output
- Hello, World!

---

### Notes
- GnuCOBOL configuration handling differs slightly in MSYS2 compared to Linux.

- The COB_CONFIG_DIR variable is required for correct operation.

- This example uses free format COBOL, which is automatically detected by GnuCOBOL.

---

## 🇫🇮 Suomi
Tämä kansio sisältää yksinkertaisen Hello World -ohjelman, joka on kirjoitettu COBOLilla ja käännetty GnuCOBOL-kääntäjällä.

Esimerkki on osa hello_world_100 -projektia, jossa esitellään perusohjelmia useilla eri ohjelmointikielillä.

---

### Tiedostot
- hello.cob – COBOL-lähdekoodi, joka tulostaa Hello, World!

---

### Vaatimukset (Windows)
- MSYS2

- MSYS2 UCRT64 -ympäristö

- GnuCOBOL (cobc)

GnuCOBOL asennetaan MSYS2:n kautta ja sitä tulee käyttää UCRT64-shellissä.

---

### Tarvittava ympäristömuuttuja
Kun GnuCOBOLia käytetään MSYS2 UCRT64 -ympäristössä, seuraava ympäristömuuttuja on asetettava:
```bash
export COB_CONFIG_DIR=/ucrt64/share/gnucobol/config
Rivin voi lisätä pysyvästi tiedostoon ~/.bashrc.
```
### Kääntäminen ja ajaminen
Siirry MSYS2 UCRT64 -shellissä projektin cobol-hakemistoon:
```bash
cd <polku-projektiin>/hello_world_100/cobol
cobc -x hello.cob
./hello.exe
Korvaa <polku-projektiin> oman koneesi projektihakemistolla.
```
### Tuloste
- Hello, World!

---

### Huomioita
- GnuCOBOLin konfiguraatio toimii MSYS2:ssa hieman eri tavalla kuin Linuxissa.

- COB_CONFIG_DIR on välttämätön oikean toiminnan kannalta.

- Tämä esimerkki käyttää free format -COBOLia, jonka GnuCOBOL tunnistaa automaattisesti.

---
