---
created: 2025-10-02T16:00:55+02:00
modified: 2025-10-08T14:12:58+02:00
type: Journal
---

# Progettazione integrazione BlockChain di log&trace in infrastruttura DCMS

Problemi progettuali da affrontare

L’attività definisce le caratteristiche dettagliate rispetto alla implementazione dei nodi BlockChain, la definizione e la modalità di scambio dati della rete peer to peer , il meccanismo del consenso e la distributed ledger *(cfr creare nodi distribuiti)* sulle macchine endpoint previste di DCMS. 
Che tecnologia di crittografia per la BC1 viene utilizzata? *(cfr cifratura adottata in Dapp_Project)*
dove risiedono i nodi della rete rispetto agli elementi dell'architettura DCMS?*(BC privata, wallet fungibili per più blockchain)*
Che tipologia di algoritmo per la BC1 viene scelto? *(Smart contract, uno per ogni segmentazione??)*
Come viene generato il consenso in presenza di nodi che è possibile “spegnere”?*(...??...)*
I nodi della rete mantengono un ledger completo o è prevista una separazione tra nodi con ledger completo e nodi con ledger parziale?
La BlockChain è privata o pubblica? In che limiti viene definita privata?

Inoltre: una volta chiariti gli aspetti chiave della BlockChain, come viene effettuato il deploy distribuito?
Infine: definizione degli smart contracts da attivare su BlockChain. Quali tipologie prevedere? con che ricorrenza vengono attivati?



*link*:

- https://www.excentio.com/articoli/creazione-di-una-rete-privata-ipfs/ *(schematico)*
- https://eleks.com/research/ipfs-network-data-replication/
- https://github.com/elek/easypin
- Qui c'è una descrizione del processo e anche un link al tutorial video
(anche se usano come tool per compilare e fare deploy in locale dello
smart contract un tool che si chiama truffle, che ora non è più usato in
genere, meglio usare hardhat) https://elearning.di.unipi.it/pluginfile.php/31679/mod_resource/content/3/06-05-20-4-Eth%20IPFS.pdf
- link hadhat: https://hardhat.org/
- https://tooploox.com/using-ipfs-with-ethereum-for-data-storage
- https://github.com/textileio/textile
- https://storage.chainsafe.io/ *(soluzione alternativa a Storacha)*

**PAPER**:
https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9705291
