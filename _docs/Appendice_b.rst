=============================
Appendice B: catalogazione dei set di dati con il metodolo delle stelle
=============================

(Classificazione di Tim Berners-Lee, tratto da http://5stardata.info/en/)

Per distinguere i diversi formati utilizzabili nella codifica dei set di dati, è stato proposto in seno al W3C (proposta di Tim Berners Lee, Presidente del W3C e ideatore del World Wide Web ) un modello di catalogazione che li classifica in base alle loro caratteristiche su una scala di valori da 1 (una stella) a 5 (cinque stelle). Tale scala viene ripresa più avanti per indicare il livello di apertura che si vuole raggiungere nella pubblicazione dei dataset del Comune di Palermo. 

(★) Una Stella.

È il livello base, costituito da file non strutturati: ad esempio un’immagine in formato grezzo (formati come .gif, .jpg, .png), un documento in formato Microsoft Word, un file in formato Adobe Pdf. 
Una sola stella indica la semplice disponibilità di una informazione e di un dato on line, in un formato qualsiasi, purché distribuito con licenza aperta. I dati distribuiti in questo formato sono leggibili e stampabili dagli utenti, possono essere conservati localmente su un PC e sono semplici da pubblicare. Tuttavia non sono un formato aperto in quanto non è possibile effettuare su di essi alcuna elaborazione.

(★★) Due Stelle.

Questo livello indica dati strutturati ma codificati con un formato proprietario. Ad esempio un documento in formato Microsoft Excel. 
Due stelle indicano, oltre alle possibilità offerte dai dati contraddistinti da una sola stella, la possibilità di effettuare elaborazioni sui dati, a patto di disporre del software necessario a gestire un file codificato con un formato proprietario. I dati caratterizzati dalle due stelle non sono un formato aperto in quanto per elaborarli è necessario un software proprietario, tuttavia di norma possono essere convertiti – essendo dati strutturati – in dati aperti. 

(★★★) Tre Stelle.

Questo livello indica dati strutturati e codificati in un formato non proprietario. Ad esempio il formato .csv (Comma Separated Values) al posto – ad esempio – del formato Microsoft Excel utilizzato nel caso precedente. 
Tre stelle indicano, oltre alle possibilità offerte dai dati contraddistinti da due sole stelle, la possibilità di effettuare elaborazioni sui dati senza esser costretti ad utilizzare software proprietario. Quello caratterizzato dalle tre stelle è il formato più semplice di dati aperti. 

(★★★★) Quattro Stelle.

Questo livello indica dati strutturati e codificati in un formato non proprietario che sono dotati di un URI8 che li rende indirizzabili sulla rete e quindi utilizzabili direttamente online, attraverso l’inclusione in una struttura basata sul modello RDF (Resource Description Framework) . 
Quattro stelle indicano quindi il fatto che il singolo dato di un dataset, disponibile on line in un formato aperto (tipicamente XML/RDF) può essere richiamato attraverso un URL (Uniform Resource Locator) specifico. 
Ciò consente di puntare al dato o ad un insieme di dati da un'applicazione o accedervi dall’interno di un programma che può poi elaborarlo in vari modi. 
Si pensi, ad esempio, a un dataset contenente gli indirizzi dei monumenti di una città opportunamente codificati: da qualsiasi software – finanche dal browser – è possibile collegarsi all’URL che indica il singolo monumento, potendolo ad esempio georeferenziare su una mappa. 

(★★★★★) Cinque Stelle.

Questo livello indica quelli che vengono definiti Linked Open Data (LOD). Quei dati aperti, cioè, che – dal punto di vista del formato – oltre a rispondere alle caratteristiche indicate al punto precedente (classificazione a quattro stelle) presentano anche, nella struttura del dataset, collegamenti ad altri dataset. In altri termini, grazie al ricorso al già citato modello di descrizione dei dati RDF, è possibile collegare dinamicamente tra loro più dataset, incrociando così informazioni provenienti da fonti diverse, eventualmente gestite da diverse Amministrazioni. Si pensi ad esempio al caso del dataset contenente gli indirizzi dei monumenti di una città alla quale si è fatto riferimento in precedenza. Tale dataset, pubblicato dall’Amministrazione A, potrebbe essere collegato al dataset di un altro Ente – l’Amministrazione B – che dispone dell’archivio delle opere d’arte presenti all’interno di ogni monumento. In questo caso un sistema software potrebbe, dopo aver chiesto all’utente i suoi gusti e le sue preferenze in fatto di arte, strutturare un percorso georeferenziando i monumenti a partire dalle informazioni presenti nel dataset disponibile presso l’Amministazione A, dopo averli preselezionati in base alle opere d’arte in essi contenute, identificate nel dataset dell’Amministrazione B.

I Linked Open Data, quindi, consentono di combinare i contenuti di dataset diversi grazie a costrutti formali formulati secondo il modello RDF in uno dei diversi formati esistenti (XML/RDF, N3, ecc…). Ciò aumenta esponenzialmente il valore dei dataset reciprocamente correlati, consentendo il passaggio dal livello dei dati a quello dell’informazione e quindi a quello della conoscenza e fornendo così un quadro di contesto strutturato a partire dalla correlazione di informazioni provenienti da fonti diverse. 
