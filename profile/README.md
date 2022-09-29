# Welcome in MusicalTwin! :star:
## What does this application do?
By logging in with your Spotify account, you will be able to find people with the same musical taste as yours(kinda)!

## Technology used
- React
- Java -> maven, mvc, jpa, spring-boot
- MySql
- Spotify API

:stars:

# Anteprima UI
![Foto](https://github.com/musicalTwin/client/blob/master/STILEDEFINITIVO.png?raw=true)

# Average MusicalTwin user:
![Foto](https://github.com/musicalTwin/client/blob/master/giovanni.png?raw=true)



# Development setup

## [Installer MySQL](https://dev.mysql.com/get/Downloads/MySQLInstaller/mysql-installer-community-8.0.29.0.msi)

- Installa MySQL server e MySQL connection (per **python** ovviamente)
- Metti la password del root (non la mettiamo qua che magari è poco sicuro) :)
###[Local generated Api Docs](http://localhost:5000/swagger-ui/index.html)
# Setup

> Per il frontend
### (nella directory del frontend)
```
npm install
npm start
```
#### start port: [http://localhost:3000/](http://localhost:3000/) 

# Development ToDos

- [x] Strutturato il database per i generi, sesso e gli eventuali match
- [ ] Strutturato il database per i messaggi ecc.
- [ ] Pagina Registrati/Loggati
- [x] Trovare un modo per gestire il login con spotify
- [x] Algoritmo di suggerimento utenti, quindi di matchup
- [x] Backend (Non si sa bene in che linguaggio, ma probabilmente python)
- [x] Fatta la funzione per risparmiare 3 caratteri nel commit del database (`.db`)
- [x] Compilata la tabella `tutti_generi` --> `rap genovese` incluso
- [x] Fare un API che funzioni
- [ ] La sicurezza (anche se visto che è una demo sticazzi)
- [NEVER] ~Arrendersi~ (W)
- [x] Gestire match e rifiuto (quindi che si resettino dopo x tempo: TODO)
- [ ] Le chat
- [ ] Possibilità di personalizzare il profilo
- [ ] Trovare altre cose da aggiungere alla lista
- [x] Avere la certezza matematica che non finiremo mai in tempo
- [x] Avere 5 mesi di tempo per fare il progetto ma usare solo gli ultimi 15 giorni

## frontend
- [x] Form registrazione
- [ ] Homepage
- [x] Form per login con sesso, a quale sesso è interessato(anche più di uno)
- [x] Login Spotify (https://www.npmjs.com/package/react-spotify-auth) (senza lasciare le credenziali in chiaro TODO)
- [ ] Cards (cardId, id dell'utente da swipare)
- [ ] Codice pulito :)


