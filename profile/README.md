# Welcome in MusicalTwin! :star:
## What does this application do?
By logging in with your Spotify account, you will be able to find people who listen to your same music (less or more)!

## Technology used
- React
- Java -> maven, mvc, jpa, spring-boot
- MySql
- Spotify API

:stars:




# Development setup

## [Installer MySQL](https://dev.mysql.com/get/Downloads/MySQLInstaller/mysql-installer-community-8.0.29.0.msi)

- Installa MySQL server e MySQL connection (per **python** ovviamente)
- Metti la password del root (non la mettiamo qua che magari è poco sicuro) :)

# Per il venv

buona fortuna

# Setup

> Per il backend

```
pip install -r requirements.txt
```

#

> Per il frontend

```
npm install
```

# Development ToDos

- [x] Strutturato il database per i generi, sesso e gli eventuali match
- [ ] Strutturato il database per i messaggi ecc.
- [ ] Pagina Registrati/Loggati
- [ ] Trovare un modo per gestire il login con spotify
- [ ] Algoritmo di suggerimento utenti, quindi di matchup
- [x] Backend (Non si sa bene in che linguaggio, ma probabilmente python)
- [x] Fatta la funzione per risparmiare 3 caratteri nel commit del database (`.db`)
- [x] Compilata la tabella `tutti_generi` --> `rap genovese` incluso
- [ ] Fare un API che funzioni
- [ ] La sicurezza (anche se visto che è una demo sticazzi)
- [ ] ~Arrendersi~ (W)
- [ ] Gestire match e rifiuto (quindi che si resettino dopo x tempo)
- [ ] Le chat
- [ ] Possibilità di personalizzare il profilo
- [ ] Trovare altre cose da aggiungere alla lista
- [x] Avere la certezza matematica che non finiremo mai in tempo

## frontend
- [ ] Form per login con sesso, a quale sesso è interessato(anche più di uno)
- [ ] Login Spotify (https://www.npmjs.com/package/react-spotify-auth) senza lasciare le credenziali in chiaro
- [ ] Cards (cardId, id dell'utente da swipare)
- [ ] Codice pulito :)
