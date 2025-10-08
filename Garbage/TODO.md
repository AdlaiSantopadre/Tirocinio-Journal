---
created: 2025-10-02T16:00:55+02:00
modified: 2025-10-08T14:21:18+02:00
---

# ANALISI DEI Requisiti

CONTESTO e OBIETTIVI del PROGETTO:
Con il progetto SANICHAIN intendiamo progettare e dimostrare soluzioni di digitalizzazione avanzata dei *processi di pulizia, sanificazione e disinfezione in ambienti clinici ed ospedalieri*, che possano integrare sia l’utilizzo di strumentazioni robotizzate quali ad es. le soluzioni robotizzate di sanificazione UVC “SanisLight” (ma non solo), sia ovviamente le operazioni svolte dal personale, al fine di *massimizzare efficienza dei processi*, *accountability*, *(A)possibilità di controllo e verifica*, *(B)disponibilità di dati aggregati semplici da visualizzare* e che consentano la *(C)programmazione e l’esecuzione di azioni di sanificazioni mirate e precise*. **Un aspetto chiave** di una soluzione di questo tipo è *(D)la tracciabilità e la resilienza* delle informazioni relative alle operazioni di sanificazione condotte: pensiamo alle necessità di accountability e alle possibilità di audit ottenibili ed esprimibili da uno strumento del genere. Proprio per queste ragioni, riteniamo che lo strumento tecnologico da implementare in tali soluzioni con assoluta priorità sia quello della **BlockChain (distributed ledger)**, che esprime in pieno le caratteristiche desiderate.

L’obiettivo del progetto è quindi progettare e realizzare un *(1)prototipo di architettura digitale* **(Disinfection and Cleaning Management System, DCMS)**, con **(1a)** app su smartphone, **(2a)web interfaces**, e (3a)dimostratori di sensori / agenti robotizzati IoT-based , che possa servire come *(E)(scalabilità)* base di partenza di sistemi che potranno poi via via diventare più ampi complessi, e strutturati nel contesto dei processi Smart Cleaning e Disinfection, con 4(b)operazioni tracciate tramite BlockChain sui principali nodi rappresentati dai sensori / agenti robotizzati IoT-based. Tale architettura viene portata dal progetto a un Livello TRL pari a 7, partendo da un TRL 2.

Nel contesto del progetto, andremo quindi a  (3a)progettare e sviluppare alcuni dispositivi IOT che possano fungere da **sorgente di informazione rilevante**, e essere usati, con regole empiriche o, (3b)in futuro, con intelligenza artificiale:

(3a)integrazione dei robot di sanificazione UVC SanisLight (TRL di dispositivo: 9 senza tracciamento BlockChain ma 2 se consideriamo anche BlockChain; intendiamo portarlo a 7).

(3a)sviluppo dispositivi *semplici e a basso costo* per conteggio passaggi e presenze (per verificare l’”AFFOLLAMENTO” e tenere traccia di tutti i passaggi nelle stanze; ovviamente possiamo pensare di avere anche collegamento con sistemi di badge per accessi a locali specifici ((TRL di dispositivo: 9 senza tracciamento BlockChain ma 2 se consideriamo anche BlockChain; intendiamo portarlo a 7).

(3a)armadio intelligente dei prodotti chimici per pulizie e sanificazione, per tenerne sotto controllo l’effettivo utilizzo e l’evoluzione temporale dei quantitativi utilizzati. Sappiamo infatti che esistono prodotti specifici per eradicare batteri e virus specifici, e che un dato rischio è eliminabile o riducibile solo a fronte del corretto utilizzo dei prodotti (TRL di dispositivo: 6; intendiamo portarlo a 7).


**Gli obiettivi finali di progetto sono due**:

Obiettivo 1(1a, 2a , 4b): realizzare un dimostratore di piattaforma digitale DCMS (Digital and Cleaning Management System) che integra funzionalità di prescrizione, controllo e reportistica, azioni di pulizia e sanificazione sia attuate da personale che da robot, controllo dell'utilizzo dei prodotti chimici, e sensoristica ambientale, con tracciamento delle operazioni in BlockChain.

Obiettivo 2(3a, 4b): realizzare dimostratori IOT based di sensoristica e agenti robotizzati nel contesto delle operazioni di sanificazione, tutti dotati di compatibilità BlockChain per integrazione con piattaforma DCMS (operatività come *(4a)nodo SaniNode*): (3a1)sensori di presenza / passaggio,(3a2) robot di sanificazione UVC, (3a3)dispenser/distributori intelligenti di prodotti chimici per sanificazione.

Le **caratteristiche dei dimostratori** sono:

capacità dei nodi Saninode di operare tenendo distinte le informazioni relative a strutture cliniche differenti (ci si aspetta (E)**totale segregazione**);

capacità dei nodi Saninode di tracciare le (D) attività in blockchain in misura resiliente e non modificabile (ci si aspetta il massimo valore possibile);

(C)capacità dei dispenser/distributori  intelligenti di prodotti chimici per sanificazione di potere misurare con precisione le quantità di prodotto erogato (ci si aspetta totale precisione se erogatori di flaconi; precisione superiore al 10% in caso di erogazione diretta di liquidi).

Gli aspetti critici ed estremamente innovativi rispetto allo stato dell’arte, che generano valore aggiunto significativo, e su cui si concentrano le principali problematiche tecnico scientifiche (risolvibili grazie al know apportato dal partner accademico), sono inerenti alla integrazione di tecnologie BlockChain nella architettura DCMS nei nodi IOT, che, una volta risolti, abilitano funzioni chiave e completamente innovative quali:

l’integrazione di tutte le informazioni in una unica architettura di raccolta ed utilizzo dati quali il DCMS, che consente a tali dati integrati di essere utilizzati in maniera congiunta per prendere decisioni; ed 

tracciamento di tutti gli eventi e le azioni nel DCMS tramite BlockChain. Quest'ultimo punto è la novità assoluta e più rilevante del progetto, e riteniamo colga in pieno e attui la necessità di accountability di processo che guiderà la transizione digitale del settore, come peraltro già anticipato da analisi di trend e di mercato da parte di numerose società di consulenza .
------------------------------------
