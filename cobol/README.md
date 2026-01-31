# COBOL – Hello World

## English 🇬🇧

This folder contains a simple **Hello World** program written in **COBOL**, compiled using **GnuCOBOL**.
The example is part of the **hello_world_100** project, which demonstrates basic programs in multiple programming languages.

### Files

- `hello.cob` – COBOL source file that prints `Hello, World!`

### Requirements (Windows)

- MSYS2
- MSYS2 **UCRT64** environment
- GnuCOBOL (`cobc`)

GnuCOBOL is installed via MSYS2 and must be run inside the **UCRT64 shell**.

### Required environment variable

When using GnuCOBOL with MSYS2 UCRT64, the following environment variable is required:

```bash
# Required for GnuCOBOL in MSYS2 UCRT64
export COB_CONFIG_DIR=/ucrt64/share/gnucobol/config
```

You can add this permanently to `~/.bashrc`.

### Compile and run

From the MSYS2 UCRT64 shell, navigate to the COBOL directory of the project:

```bash
cd <your_project_path>/hello_world_100/cobol
cobc -x hello.cob
./hello.exe
```

Replace `<your_project_path>` with the directory where the project is located on your system
(for example: `/c/dev/hello_world_100/cobol`). Path examples are shown using MSYS2-style paths.

### Output

```text
Hello, World!
```

### Notes

- GnuCOBOL configuration handling differs slightly in MSYS2 compared to Linux.
- The `COB_CONFIG_DIR` environment variable is required for correct operation.
- This example uses free format COBOL, which is automatically detected by GnuCOBOL.
- This example focuses on demonstrating the toolchain setup rather than COBOL language features.

---

## Suomi 🇫🇮

Tämä kansio sisältää yksinkertaisen **Hello World** -ohjelman, joka on kirjoitettu **COBOL**illa ja käännetty **GnuCOBOL**-kääntäjällä.
Esimerkki on osa **hello_world_100** -projektia, jossa esitellään perusohjelmia useilla eri ohjelmointikielillä.

### Tiedostot

- `hello.cob` – COBOL-lähdekoodi, joka tulostaa `Hello, World!`

### Vaatimukset (Windows)

- MSYS2
- MSYS2 **UCRT64** -ympäristö
- GnuCOBOL (`cobc`)

GnuCOBOL asennetaan MSYS2:n kautta ja sitä tulee käyttää UCRT64-shellissä.

### Tarvittava ympäristömuuttuja

Kun GnuCOBOLia käytetään MSYS2 UCRT64 -ympäristössä, seuraava ympäristömuuttuja on asetettava:

```bash
# Vaaditaan GnuCOBOLille MSYS2 UCRT64 -ympäristössä
export COB_CONFIG_DIR=/ucrt64/share/gnucobol/config
```

Rivin voi lisätä pysyvästi tiedostoon `~/.bashrc`.

### Kääntäminen ja ajaminen

Siirry MSYS2 UCRT64 -shellissä projektin COBOL-hakemistoon:

```bash
cd <oma_projektipolku>/hello_world_100/cobol
cobc -x hello.cob
./hello.exe
```

Korvaa `<oma_projektipolku>` sillä hakemistolla, johon projekti on omalla koneellasi tallennettu
(esimerkiksi: `/c/dev/hello_world_100/cobol`). Polkuesimerkit on esitetty MSYS2:n käyttämässä muodossa.

### Tuloste

```text
Hello, World!
```

### Huomioita

- GnuCOBOLin konfiguraation käsittely eroaa MSYS2:ssa hieman Linuxista.
- `COB_CONFIG_DIR`-ympäristömuuttuja on välttämätön oikean toiminnan kannalta.
- Tämä esimerkki käyttää free format -COBOLia, jonka GnuCOBOL tunnistaa automaattisesti.
- Tämä esimerkki keskittyy erityisesti työkaluketjun käyttöönottoon eikä COBOL-kielen ominaisuuksiin.

---
