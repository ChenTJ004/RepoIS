Applicate modifiche alla classe originale AuthController.java.

Aggiunto l'endpoint REST mappato su @PostMapping("/login").

Il servizio accetta richieste JSON tramite la classe CreateUserRequest.

Effettua la verifica delle credenziali confrontandole con i dati nella mappa 'users'.

Ritorna una stringa di testo pari a "OK" in caso di successo o "NOT OK".

