# SwitchModderSHOP — licenze

Directory per le autorizzazioni firmate. Il pannello Admin pubblica un file `SM-<32 caratteri esadecimali>.json` per console. Ogni record contiene `payload` e `signature` in Base64 (ECDSA P-256/SHA-256). Le revoche sostituiscono il record con un payload firmato che indica `revoked: true`.

Nessuna licenza è stata emessa durante l’inizializzazione. Non pubblicare chiavi private, token GitHub, nominativi, username Telegram o seriali originali. Gli identificativi pseudonimi e la cronologia dei record sono pubblici.
