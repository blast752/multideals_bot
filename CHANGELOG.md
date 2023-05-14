# Changelog
## [0.1.0] - 2023-05-14

### Aggiunto

- Funzione `get_title_amazon` per estrarre il titolo del prodotto da Amazon.
- Funzione `get_price_amazon` per estrarre il prezzo del prodotto da Amazon.
- Funzione `get_original_price_amazon` per estrarre il prezzo originale del prodotto da Amazon.
- Funzioni equivalenti per estrarre informazioni sui prezzi da eBay e AliExpress (`get_price_ebay`, `get_original_price_ebay`, `get_price_aliexpress`, `get_original_price_aliexpress`).
- Funzione `send_telegram_message` per inviare messaggi tramite il bot di Telegram.
- Funzione `check_price` per verificare il prezzo e la disponibilità di sconti su una lista di prodotti.
- Logica principale che esegue la funzione `check_price` ogni ora.
- Funzione `send_welcome_message` per inviare un messaggio di benvenuto all'utente con un pulsante "Versione".
- Funzione `handle_updates` per gestire gli aggiornamenti in arrivo dal bot di Telegram, come il pulsante "Versione" premuto dall'utente.
- Logica principale che combina l'esecuzione delle funzioni `handle_updates` e `check_price` in un ciclo continuo.
- Supporto per la gestione delle versioni attraverso la variabile `VERSION`.
- Supporto per un URL del changelog esterno attraverso la variabile `CHANGELOG_URL`.
