BobBot
Per farlo partire, avviare una PowerShell o riga di comando in questa cartella e usare:
-jar bot.jar -c config.yml -d data

-jar specifica il nome del .jar del bot
-c è il file di config con il token per puntare al bot giusto (fornito da BotFather)
-d è la cartella dove salva i dati di gruppi/messaggi etc

repo originale: https://github.com/ClockVapor/markov-telegram-bot

comandi:
/msg (@NomeUtente parola)
invia un messaggio usando i dati di un singolo utente. Si può specificare una parola "seed" da cui partire per generare la frase, sennò
sceglie a random

/msgall (parola)
genera un messaggio usando i dati di tutto il gruppo. Anche qua si può scegliere da dove partire

/stats
mostra una lista delle 5 parole più usate da ogni persona