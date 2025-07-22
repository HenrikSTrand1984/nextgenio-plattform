**Dokument-ID:** NTG-SEC-TOOL-0001  
**Versjon:** 1.0  
**Status:** Aktiv  
**Dato:** 2025-07-22  
**Forfatter:** Henrik Strand / Norsain Technology Group  
**GitHub-sti:** `/00_admin/05_templates/09_documents/bitwarden_userguide.md`  
**Dropbox-sti:** `Norsain/00-Admin/05_Templates/09_Documents/bitwarden_userguide.md`  
**Kontakt:** info@norsain.com  
---

## 🎯 Formål

Dette dokumentet gir en komplett brukerveiledning for Bitwarden som passordhåndteringsverktøy brukt av Norsain Technology Group.  
Veiledningen dekker bruk av hvelv, objekttyper, mapper, sikker notatbruk, tofaktor, deling og sikkerhetspraksis.

---

## 📦 Innhold

1. [Hva er Bitwarden?](#hva-er-bitwarden)
2. [Oppsett og installasjon](#oppsett-og-installasjon)
3. [Hvelvtyper og bruk](#hvelvtyper-og-bruk)
4. [Mapper og struktur](#mapper-og-struktur)
5. [Sikker notis og API-nøkler](#sikker-notis-og-api-nøkler)
6. [Tofaktorautentisering (2FA)](#tofaktorautentisering-2fa)
7. [Deling og team-funksjoner](#deling-og-team-funksjoner)
8. [Anbefalt struktur for Norsain](#anbefalt-struktur-for-norsain)
9. [Backup og eksport](#backup-og-eksport)
10. [Sikkerhetsrutiner og tips](#sikkerhetsrutiner-og-tips)

---

## 📘 Hva er Bitwarden?

Bitwarden er et sikkerhetsverktøy for lagring og deling av:
- Passord
- API-nøkler
- Sensitive dokumenter og data
- Tofaktor-koder
- Identitetsinformasjon

Alle data er kryptert med Zero-Knowledge-arkitektur – kun du har tilgang med din hovednøkkel (masterpassord).

---

## 🛠️ Oppsett og installasjon

| Plattform     | Handling                                                                 |
|---------------|--------------------------------------------------------------------------|
| **Web Vault** | https://vault.bitwarden.com                                              |
| **Browser**   | Installer utvidelse for Chrome, Firefox, Edge, Safari                    |
| **Mobil**     | Last ned Bitwarden fra App Store / Google Play                          |
| **Desktop**   | Windows / macOS klient: https://bitwarden.com/download/                 |
| **CLI**       | For avansert bruk: https://bitwarden.com/help/cli/                      |

---

## 🔍 Hvelvtyper og bruk

Navigasjonsmenyen inneholder ulike **typer objekter** – disse brukes slik:

| Type           | Bruk                                                                 |
|----------------|----------------------------------------------------------------------|
| 🧑‍💻 **Innlogging**    | Brukernavn/passord + URL til innlogginger                   |
| 💳 **Kort**           | Kredittkort, betalingskort – for autofyll og sikker lagring   |
| 🧾 **Identitet**      | Fullt navn, adresse, mobil, e-post – autofyll i skjemaer      |
| 🗒 **Sikker notis**    | API-nøkler, lisensnøkler, sensitive tekster – kryptert notat |
| 🖥 **SSH-nøkkel**      | Privat nøkkel (.pem / .ssh) + tilhørende passphrase           |

---

## 🗂️ Mapper og struktur

Mapper gir manuell struktur i hvelvet ditt. Bruk mapper for:

| Bruksområde        | Eksempler                           |
|--------------------|--------------------------------------|
| Organisasjonsdeling| `Norsain`, `Privat`, `GK`            |
| Prosjekter         | `SUS-Stavanger`, `OpenAI-Integrasjon`|
| Rollebasert        | `DevOps`, `R&D`, `Admin`, `API`      |

---

## 🛡 Sikker notis og API-nøkler

For lagring av nøkler som **OpenAI**, **GitHub**, **Supabase**, gjør følgende:

1. Velg **"Sikker notis"** som type
2. Tittel: `OpenAI_API_KEY`
3. Lim inn nøkkelen i notatfeltet
4. Legg evt. til `Custom Field` eller **Tag:** `api-key`, `prod`, `test`

📌 *Tips: Ikke legg API-nøkler i fritekst eller e-post!*

---

## 🔐 Tofaktorautentisering (2FA)

Aktiveres slik:
- Gå til **"Innstillinger > To-trinns pålogging"**
- Velg: `Authenticator App` (TOTP) eller `YubiKey`
- Skriv ut/generér backupkoder

🎯 Anbefalt: Bruk **Authy**, **Aegis** (Android) eller **1Password Authenticator**

---

## 👥 Deling og team-funksjoner

Bitwarden støtter **Organizations** og **Collections**:

| Element         | Bruk                                                        |
|-----------------|-------------------------------------------------------------|
| Organization    | Hele teamet / firmaet – inviter med roller                  |
| Collections     | Delte mapper: `DevOps`, `Kunder`, `Intern tilgang`          |
| Roller          | Admin / Manager / User / Viewer                             |

📎 Sikker deling skjer *kun* internt – aldri del via e-post!

---

## 🧱 Anbefalt struktur for Norsain

| Bruk            | Type         | Eksempeldata                         | Mappe         |
|-----------------|--------------|--------------------------------------|---------------|
| GitHub innlogging | Innlogging    | Brukernavn/passord + 2FA             | `DevOps`      |
| Supabase API    | Sikker notis | `supabase_key: sk-abc123...`        | `API`         |
| SSH-nøkkel VPS  | SSH-nøkkel   | `.pem-fil`, `passphrase`             | `Infrastructure` |
| Personlig info  | Identitet    | Fullt navn, e-post, tlf              | `Privat`      |
| Bedriftskort    | Kort         | Visa Business, utløp, CVC            | `Finance`     |

---

## 📤 Backup og eksport

- **Eksport Vault**: `Verktøy > Eksport Vault`  
  🔒 *NB: Filen er ukryptert – må beskyttes!*

- **Automatisk backup**: Kun mulig med selvhostet eller CLI/script

---

## 🚨 Sikkerhetsrutiner og tips

| Tiltak                    | Anbefaling                                                 |
|---------------------------|------------------------------------------------------------|
| 🧠 Masterpassord          | Minimum 14 tegn, ikke bruk samme som andre tjenester       |
| 🔐 2FA                    | Aktiver alltid                                             |
| 📂 Mapper                | Bruk mapper for jobb/privat-deling                         |
| 🔄 Synkronisering         | Manuell synk anbefales ved endringer på flere enheter      |
| 🕒 Autolås                | Sett 1–5 minutter inaktivitet                             |
| 🛠 Passordhelse          | Bruk "Password Health Reports" i Vault Tools              |
| 🧾 Metadata               | Dokumentér `API keys`, `tag`, `miljø`, `roller`            |

---

## 📚 Eksterne ressurser

- Bitwarden Hjelpesenter: https://bitwarden.com/help/
- CLI dokumentasjon: https://bitwarden.com/help/cli/
- Open Source kode: https://github.com/bitwarden

---

## 📄 Dokumentkontroll

| Felt               | Innhold                              |
|--------------------|---------------------------------------|
| Opprettet av       | Henrik Strand                         |
| Revidert dato      | 2025-07-22                            |
| Versjon            | 1.0                                   |
| Status             | Aktiv                                 |
| GitHub-plassering  | `/00_admin/05_templates/bitwarden_userguide.md` |
| Dropbox-plassering| `Norsain/00-Admin/05_Templates/bitwarden_userguide.md` |
| Kontakt            | info@norsain.com                      |

---
