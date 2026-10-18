# idlheim-maj

Mises à jour automatiques du jeu **Idlheim**.

Le jeu (v3.4 et plus) lit `info.json` au lancement. Si le numéro de build est plus récent que le sien, il télécharge `game.pck`, vérifie sa signature (`game.pck.sig`) et redémarre sur la nouvelle version.

Un patch qui n'est pas signé avec la clé privée du jeu est refusé.
