# Dati di terze parti inclusi

Oltre alle librerie elencate in [rust-licenses.md](rust-licenses.md) e [npm-licenses.md](npm-licenses.md), Horizon include questi dati.

| Dati | Dove | Fonte | Licenza |
|---|---|---|---|
| Elenco delle 10.000 password più usate (almeno 10 caratteri, minuscole) | `crates/api-core/data/common-passwords.txt`, nell'eseguibile del server e delle app | SecLists, Daniel Miessler e collaboratori: `Passwords/Common-Credentials/xato-net-10-million-passwords-1000000.txt` (dati di xato.net) | MIT, © 2018 Daniel Miessler |
| Certificati delle autorità di certificazione | Immagine del container: `/etc/ssl/certs/ca-certificates.crt` | Mozilla, distribuiti da curl (<https://curl.se/ca/cacert.pem>) | MPL-2.0, non modificati |
| Carattere Inter | Esportazioni PDF e PNG | Rasmus Andersson | SIL Open Font License 1.1 |

**ClamAV** non è incluso: chi gestisce il server lo installa a parte (GPL-2.0, processo separato) e Horizon gli parla con il protocollo `clamd`.
