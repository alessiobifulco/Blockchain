# Analisi dei Primitivi Crittografici nella Tecnologia Blockchain

Progetto per il corso di Crittografia focalizzato sull'analisi dei meccanismi e degli algoritmi crittografici che garantiscono la sicurezza, l'integrità e il non ripudio nelle blockchain.

---

## Obiettivo del Progetto

L'obiettivo di questo progetto è analizzare le fondamenta crittografiche che rendono possibile il funzionamento di una blockchain. Lo studio si concentra sui singoli componenti crittografici, il loro ruolo specifico e come la loro interazione crei un sistema distribuito sicuro e affidabile.

## Concetti Crittografici Analizzati

Il progetto esplora i seguenti pilastri della crittografia applicata alla blockchain:

* **Funzioni di Hash Crittografico (es. SHA-256):**
    * Si analizza il loro ruolo nel garantire l'immutabilità dei dati. Ogni blocco della catena è legato al precedente tramite l'hash, creando una dipendenza che rende estremamente difficile alterare la cronologia delle transazioni. Vengono inoltre usate per il processo di mining (Proof-of-Work).

* **Crittografia a Chiave Pubblica (Asimmetrica):**
    * Viene studiato il meccanismo delle coppie di chiavi (pubblica e privata) come base per la creazione dei "wallet". La chiave pubblica funge da indirizzo per ricevere fondi, mentre la chiave privata, mantenuta segreta, è l'unica in grado di autorizzare transazioni.

* **Firme Digitali (es. ECDSA):**
    * Si approfondisce come le firme digitali vengano utilizzate per autenticare le transazioni. Il proprietario di un wallet firma una transazione con la propria chiave privata, dimostrando in modo matematicamente verificabile di possedere i fondi, senza mai rivelare la chiave stessa.

* **Alberi di Merkle (Merkle Trees):**
    * Viene esaminata la struttura dati ad albero basata su hash che permette di riassumere tutte le transazioni di un blocco in un'unica "impronta" (Merkle Root). Questa tecnica consente una verifica efficiente e sicura dell'inclusione di una transazione in un blocco.

## Tecnologie di Riferimento

* **Algoritmi di Hash:** SHA-256 (Bitcoin), Keccak-256 (Ethereum)
* **Algoritmi di Firma:** ECDSA (Elliptic Curve Digital Signature Algorithm)
* **Piattaforme Blockchain Analizzate:** Bitcoin, Ethereum

## Contatti
* Alessio Bifulco: `alessio.bifulco@studio.unibo.it`
