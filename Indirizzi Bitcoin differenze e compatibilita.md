## **Introduzione**

Negli ultimi anni, Bitcoin ha guadagnato sempre più popolarità come forma di valuta digitale decentralizzata ma ancor di più come riserva di valore. Gli indirizzi Bitcoin sono un aspetto fondamentale del sistema, permettendo agli utenti di ricevere e inviare fondi in modo sicuro. Tuttavia, con lo sviluppo della tecnologia e l’introduzione di nuove funzionalità, sono emersi diversi tipi di indirizzi Bitcoin, come Legacy (inizia con 1), SegWit (inizia con 3), Native SegWit (inizia con bc1q) e Taproot (inizia con bc1p). In questo articolo, esploreremo i vari tipi di indirizzi Bitcoin, i loro formati e le differenze tra di essi, concentrandoci sulla compatibilità tra Legacy, SegWit e Taproot.

Ogni volta che creiamo un wallet otteniamo una seed phrase dalla quale vengono generate coppie di chiavi pubbliche e private, e relativi indirizzi pronti per l’uso.

Abbiamo probabilmente notato che **gli indirizzi di Bitcoin non sono sempre nello stesso formato** e che a volte ci viene presentata l’opzione per scegliere il tipo desiderato. Questo può creare confusione in quanto, nelle varie piattaforme e portafogli con cui capita di interagire non appena si iniziano a fare un po’ di operazioni, non c’è molta continuità.

Ad oggi, 2023, esistono ben quattro formati; è facile quindi che possano sorgere dubbi e soprattutto il timore di perdere le proprie monete se mandate a un indirizzo di tipo non compatibile.

Le versioni più recenti si distinguono per la maggiore efficienza, velocità e risparmio di fees.

A livello di protocollo sono tutti compatibili, in quanto **non c’è niente nel codice di Bitcoin che impedisca di inviare o ricevere tra diversi formati**. Possiamo quindi inviare e ricevere da un tipo all’altro senza problemi. Bisogna però verificare che il wallet/exchange/piattaforma supporti il formato che vogliamo usare.

**Se ti imbatti in un problema non si tratta di limiti di Bitcoin bensì di mancanze del software**, **wallet o piattaforma che stai usando**.

- **Legacy** (P2PKH): gli indirizzi **iniziano con 1** – in uso dal 2009;
- **SegWit** (P2SH): gli indirizzi **iniziano con 3** – in uso dal 2012;
- **Native SegWit** (P2WPKH, Bech32): gli indirizzi **iniziano con bc1q** – in uso dal 2018;
- **Taproot** (P2TR, Bech32m): gli indirizzi **iniziano con bc1p** – in uso dal 2021.

### **Tipologie in dettaglio**

**Indirizzi Bitcoin Legacy**

Gli indirizzi Bitcoin Legacy sono il formato originale degli indirizzi Bitcoin. Sono comunemente noti come P2PKH (Pay-to-Public-Key-Hash) e iniziano con il numero “1”. Questi indirizzi sono ancora ampiamente utilizzati e supportati dalla maggior parte dei portafogli e degli exchange. Tuttavia, presentano alcune limitazioni, come la mancanza di supporto per alcune funzionalità avanzate come la riduzione delle commissioni di transazione.

**Indirizzi Bitcoin SegWit**

SegWit, acronimo di Segregated Witness, è stata una proposta di aggiornamento del protocollo Bitcoin per affrontare i problemi di scalabilità e ridurre le commissioni di transazione. Gli indirizzi Bitcoin SegWit iniziano con il numero “3” o “bc1”. Questi indirizzi utilizzano una struttura di dati modificata all’interno delle transazioni, consentendo di memorizzare più transazioni in un blocco e riducendo così il costo delle transazioni.

Un aspetto importante degli indirizzi SegWit è che supportano la retrocompatibilità con gli indirizzi Bitcoin Legacy. Ciò significa che è possibile inviare fondi da un indirizzo SegWit a un indirizzo Legacy senza alcun problema. Tuttavia, l’invio di fondi da un indirizzo Legacy a un indirizzo SegWit potrebbe richiedere l’uso di commissioni leggermente più elevate.

**Indirizzi Bitcoin Taproot**

Taproot rappresenta un ulteriore sviluppo nel protocollo Bitcoin che introduce miglioramenti in termini di privacy e scalabilità. Gli indirizzi Bitcoin Taproot iniziano con “bc1p”. Questi indirizzi sono progettati per essere più compatti e offrire maggiore privacy rispetto agli indirizzi precedenti.

La caratteristica principale degli indirizzi Taproot è la capacità di nascondere le informazioni all’interno delle transazioni. L’idea è che le transazioni Taproot sembrino transazioni standard, rendendo difficile distinguere tra transazioni complesse e semplici. Ciò può portare a una maggiore privacy per gli utenti di Bitcoin.

Compatibilità tra Legacy, SegWit e Taproot

Una delle preoccupazioni principali per gli utenti di Bitcoin è la compatibilità tra i diversi tipi di indirizzi. Fortunatamente, esiste una certa compatibilità tra Legacy, SegWit e Taproot, che consente agli utenti di inviare fondi tra di essi senza problemi significativi.

Gli indirizzi Legacy possono inviare fondi agli indirizzi SegWit, ma potrebbero richiedere l’uso di commissioni leggermente più elevate. D’altra parte, gli indirizzi SegWit possono inviare fondi sia agli indirizzi Legacy che agli indirizzi Taproot senza alcun problema.

Tuttavia, è importante notare che gli indirizzi Legacy non possono inviare fondi direttamente agli indirizzi Taproot. È necessario che gli indirizzi Legacy inviino fondi agli indirizzi SegWit, che a loro volta possono inviare fondi agli indirizzi Taproot. Questo processo richiede l’utilizzo di più transazioni e potrebbe comportare una leggera maggiorazione delle commissioni.

Conclusioni

Gli indirizzi Bitcoin Legacy, SegWit e Taproot rappresentano diverse fasi di sviluppo del protocollo Bitcoin, ciascuna con i propri vantaggi e caratteristiche. Mentre gli indirizzi Legacy sono ancora ampiamente utilizzati, gli indirizzi SegWit e Taproot offrono funzionalità avanzate come la riduzione delle commissioni e una maggiore privacy.

La buona notizia è che esiste una certa compatibilità tra questi tipi di indirizzi, consentendo agli utenti di inviare fondi tra di essi senza problemi significativi. Gli indirizzi Legacy possono inviare fondi agli indirizzi SegWit, mentre gli indirizzi SegWit possono inviare fondi sia agli indirizzi Legacy che agli indirizzi Taproot.

Tuttavia, è importante tenere presente che gli indirizzi Legacy non possono inviare fondi direttamente agli indirizzi Taproot. Per inviare fondi agli indirizzi Taproot da un indirizzo Legacy, è necessario passare attraverso un indirizzo SegWit. Questo processo richiede l’utilizzo di più transazioni e potrebbe comportare un leggero aumento delle commissioni.

***In conclusione***, gli indirizzi Bitcoin Legacy, SegWit e Taproot rappresentano diverse evoluzioni nel sistema degli indirizzi di Bitcoin. Mentre gli indirizzi Legacy sono ancora ampiamente utilizzati, gli indirizzi SegWit e Taproot offrono funzionalità avanzate come la riduzione delle commissioni e una maggiore privacy. Fortunatamente, esiste una certa compatibilità tra di loro, consentendo agli utenti di inviare fondi tra i diversi tipi di indirizzi senza problemi significativi. Con il continuo sviluppo della tecnologia Bitcoin, è possibile che nuovi tipi di indirizzi emergano in futuro, offrendo ulteriori miglioramenti e funzionalità per gli utenti della criptovaluta più popolare al mondo.
