# Cybersecurity: Privacy Preserving Contact Tracing

Questo progetto è stato realizzato per il corso di Cyber Security tenuto all’università degli studi di Salerno. Lo scopo del progetto consiste nel modellare ed implementare la parte di sicurezza e privacy di un sistema di tracciamento dei contatti che avvengono tra gli utenti. 

L’idea del progetto nasce durante la prima ondata della pandemia Covid-19, periodo durante il quale gli stati dei vari paesi hanno finanziato diverse applicazioni mobile che tenessero traccia dei contatti tra gli utenti. La maggiorparte di queste applicazioni erano però vulnerabili ad attacchi informatici ad esempio attacchi “Man in the middle”.
L’obiettivo del progetto era quindi quello di partire dal funzionamento base di queste applicazioni ed aggiungere, in maniera teorica, strumenti di crittografia che permettessero di mantenere la privacy. 

In particolare, è stato usato l’algoritmo AES128 in modalità CBC per la fase di encryption, la funzione SHA256 per ottenere la “Message Authentication”, è stata implementata una gerarchia di certificati digitali per la verifica delle entità in gioco, è stato utilizzato il protocollo di commitment per evitare determinate falle nel sistema.
