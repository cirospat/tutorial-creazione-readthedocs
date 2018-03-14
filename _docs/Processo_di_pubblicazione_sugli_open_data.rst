===========================
Processo di pubblicazione sugli open data
===========================

Metodologia per la pubblicazione dei dati in formato open
---------------------------------------------------------
La metodologia per la pubblicazione dei dati in formato Open Data fa riferimento al modello operativo discusso precedentemente e si pone l’obiettivo di pianificare le azioni da intraprendere per raggiungere la pubblicazione dei dati a 5 stelle, secondo la classificazione presentata in Appendice B. Questo obiettivo si raggiungerà per passi individuando un primo sotto-obiettivo nella pubblicazione dei dati a 3 stelle, per poi passare gradualmente alle 5 stelle. Ovviamente affinché il processo sia efficiente occorre progettarlo tenendo in considerazione fin dall’inizio l’obiettivo finale della pubblicazione dei dati a 5 stelle. 

Ad oggi la maggior parte dei dataset sono pubblicati con formato catalogabile a 3 stelle.

La metodologia proposta si basa sulle metodologie descritte nelle “Linee Guida per l'Interoperabilità Semantica attraverso i Linked Open Data” pubblicate dall'agenzia per l'Italia Digitale e nel documento di Villazón-Terrazas “Methodological guidelines for publishing linked data”. Entrambi i documenti individuano azioni specifiche che occorre intraprendere affinché i dati della pubblica amministrazione possano essere pubblicati come Linked Open Data. 

L’approccio che verrà seguito riprende al suo interno le fasi previste dalle metodologie citate, ma differisce da queste in quanto si prevede una *milestone* intermedia relativa alla pubblicazione dei dati in formato a 3 stelle, per consentire una prima valorizzazione dei dati pubblicati attraverso la realizzazione di applicazioni specifiche. Nelle fasi successive verranno intraprese le azioni necessarie per la pubblicazione dei dati in formato Linked Open Data. Il seguente elenco mostra i passi dell’approccio proposto:

1. individuazione e selezione dei dataset negli uffici;

2. bonifica dei dataset ove si ritenga necessario per il rispetto dei requisiti minimi per la pubblicazione;

3. arricchimento tramite metadati ai sensi dello standard DCAT_AP_IT 2016;

4. validazione e pubblicazione (dati almeno 3 stelle);

5. analisi e modellazione;

6. linking con dataset esterni;

7. validazione e pubblicazione (dati a 4 e 5 stelle).

------

Modalità di individuazione (e selezione) dei dati da pubblicare in formato open
-------------------------------------------------------------------------------
Saranno oggetto di pubblicazione in formato aperto, tendenzialmente, tutti i dati e i documenti contenenti dati che il Comune di Palermo ha acquisito o prodotto nell’ambito dell’esercizio delle proprie funzioni istituzionali e di cui il medesimo è titolare, o di cui è nella piena disponibilità anche tenendo conto (ma non limitatamente) della normativa vigente in tema di pubblicazione di dati in formato aperto e del rispetto della privacy degli individui. 

A tale proposito viene effettuato, attraverso i Dirigenti e/o i referenti open data di Settore, Servizio o Unità Organizzativa,  un censimento delle raccolte di dati create dalle strutture comunali in funzione delle competenze specifiche e delle attività relative.
A ogni Dirigente e alla Società comunale dei servizi informatici SISPI SpA viene chiesto di compilare una scheda, anche online, per ogni raccolta di dati che ne individui la tipologia, il formato, il livello di privacy, l’ubicazione, la data di creazione, la data dell’ultimo aggiornamento, ecc. (vedi scheda in Appendice C).
Il team Open Data, durante le riunioni periodiche, esamina le raccolte di dati e ne individua la priorità di pubblicazione (in funzione della pubblica utilità, ecc.). 

Nel primo periodo di attuazione dei contenuti delle Linee Guida comunali open data approvate con Deliberazione di Giunta Municipale n. 252 del 13.2.2013, per avviare il processo di pubblicazione dei dataset comunali, è stata seguita la procedura del metodo `MoSCoW <http://en.m.wikipedia.org/wiki/MoSCoW_Method>`_ di seguito schematizzato.

+-----------------------+-----------------------+-----------------------+
| Priorità              | Descrizione           | Fattori               |
|                       |                       | identificativi        |
+=======================+=======================+=======================+
| M - MUST              | Indica un dataset che | Ampio interesse per   |
|                       | ha la massima         | il dataset da parte   |
|                       | priorità di           | della collettività.   |
|                       | pubblicazione         | Best Practice in      |
|                       | affinché il servizio  | altre PA              |
|                       | Open Data possa       |                       |
|                       | essere considerato un |                       |
|                       | caso di successo.     |                       |
+-----------------------+-----------------------+-----------------------+
| S - SHOULD            | Indica un dataset ad  | Medio interesse per   |
|                       | alta priorità che, se | il dataset da parte   |
|                       | possibile, dovrebbe   | della collettività.   |
|                       | essere incluso nella  | Pubblicato da altre   |
|                       | lista di              | PA                    |
|                       | pubblicazione         |                       |
|                       | attuale.              |                       |
+-----------------------+-----------------------+-----------------------+
| C - COULD             | Indica un dataset che | Ridotto interesse per |
|                       | si ritiene di         | il dataset da parte   |
|                       | auspicabile           | della collettività.   |
|                       | pubblicazione ma non  | Pubblicato da qualche |
|                       | necessario. Questo    | PA                    |
|                       | sarà incluso se il    |                       |
|                       | tempo e le risorse lo |                       |
|                       | consentiranno.        |                       |
+-----------------------+-----------------------+-----------------------+
| W - WON’T             | Indica un dataset che | Non si riscontra      |
|                       | che non sarà inserito | interesse per il      |
|                       | nella lista di        | dataset da parte      |
|                       | pubblicazione         | della collettività.   |
|                       | attuale, ma che può   | Non sono stati        |
|                       | essere considerato    | pubblicati dataset    |
|                       | per il futuro.        | simili in altre PA    |
+-----------------------+-----------------------+-----------------------+
(tabella convertita da CSV a Markdown a RST con `Pandoc 2.1.2 <http://pandoc.org/try>`_)

Tale metodo è stato usato dal Team Open Data nelle riunioni periodiche e aperte al pubblico dal dicembre 2015 al dicembre 2016 per l’individuazione dei dataset tematici da pubblicare. 
Con cadenza annuale ogni Dirigente provvederà, se necessario, all’aggiornamento dell’elenco delle raccolte di dati di sua competenza.

L’attività di individuazione dei dati oggetto di pubblicazione in formato aperto dovrà essere, in ogni caso, condotta in modo tale da escludere quelli che, per il tipo di riutilizzo o per le modalità con cui si intende realizzarlo, potrebbero violare:

- la sicurezza pubblica, la difesa nazionale, lo svolgimento di indagini penali o disciplinari;

- il diritto di terzi al segreto industriale, statistico e commerciale, o altri vincoli di segretezza fissati in obblighi di legge;

- i diritti di proprietà intellettuale;

- il diritto alla protezione dei dati personali.

In ogni caso, per assicurare la trasparenza amministrativa garantendo, al contempo, la protezione dei dati personali o coperti da segreto, il Comune procederà, quando necessario, alla pubblicazione di dati aggregati o resi anonimi in modo da non consentire alcuna identificazione, nemmeno indiretta, dei soggetti a cui tali dati si riferiscono, coerentemente con la normativa vigente in materia.

------

Modalità di produzione dei dataset e formato di pubblicazione
-------------------------------------------------------------
(In parte da “Allegato B - `Formati aperti e metadati per il riutilizzo e la diffusione dei dati pubblici” della Provincia di Trento <http://www.innovazione.provincia.tn.it/binary/pat_innovazione/notizie/AllegatoB_formati_21Dicembre_def.1356705197.pdf>`_)
Il Comune di Palermo metterà a disposizione i dati pubblici, ove possibile, in modalità elettronica e nei seguenti formati aperti che favoriscano l'interoperabilità:

+-----------------------+-----------------------+-----------------------+
| **Nome (Acronimo) -   | **Tipo di Dato**      | **Estensione del      |
| Descrizione**         |                       | file**                |
+=======================+=======================+=======================+
| **Comma Separated     | Dato tabellare        | .csv                  |
| Value (CSV) - Formato |                       |                       |
| testuale per          |                       |                       |
| l’interscambio di     |                       |                       |
| tabelle, le cui righe |                       |                       |
| corrispondono a       |                       |                       |
| record e i cui valori |                       |                       |
| delle singole colonne |                       |                       |
| sono separati da una  |                       |                       |
| virgola (o punto e    |                       |                       |
| virgola)**            |                       |                       |
+-----------------------+-----------------------+-----------------------+
| **Geographic Markup   | Dato geografico       | .gml                  |
| Language (GML) -      | vettoriale            |                       |
| Formato XML utile     |                       |                       |
| allo scambio di dati  |                       |                       |
| territoriali di tipo  |                       |                       |
| vettoriale**          |                       |                       |
+-----------------------+-----------------------+-----------------------+
| **GeoJSON - E’ un     | Dato geografico       | Di solito .geojson,   |
| formato di testo      | vettoriale            | .topojson, o .json    |
| aperto, per la        |                       |                       |
| codifica di oggetti   |                       |                       |
| geografici e dei      |                       |                       |
| correlati attributi   |                       |                       |
| non spaziali, scritto |                       |                       |
| in JSON (JavaScript   |                       |                       |
| Object Notation).**   |                       |                       |
+-----------------------+-----------------------+-----------------------+
| **Keyhole Markup      | Dato geografico       | .kml                  |
| Language (KML) -      | vettoriale            |                       |
| Formato basato su XML |                       |                       |
| creato per gestire    |                       |                       |
| dati territoriali in  |                       |                       |
| tre dimensioni.**     |                       |                       |
+-----------------------+-----------------------+-----------------------+
| **Open Document       | Dato tabellare        | .ods                  |
| Format per dati       |                       |                       |
| tabellari (ODS) -     |                       |                       |
| Formato per           |                       |                       |
| l’archiviazione e lo  |                       |                       |
| scambio di fogli di   |                       |                       |
| calcolo**             |                       |                       |
+-----------------------+-----------------------+-----------------------+
| **Resource            | Dato strutturato      | .rdf                  |
| Description Framework |                       |                       |
| (RDF) - Basato su     |                       |                       |
| XML, e’ lo strumento  |                       |                       |
| base proposto da      |                       |                       |
| World Wide Web        |                       |                       |
| Consortium (W3C) per  |                       |                       |
| la codifica, lo       |                       |                       |
| scambio e il          |                       |                       |
| riutilizzo di         |                       |                       |
| metadati strutturati  |                       |                       |
| e consente            |                       |                       |
| l’interoperabilità    |                       |                       |
| tra applicazioni che  |                       |                       |
| si scambiano          |                       |                       |
| informazioni sul      |                       |                       |
| Web**                 |                       |                       |
+-----------------------+-----------------------+-----------------------+
| **ESRI Shapefile      | Dato geografico       | .shp, .shx, .dbf,     |
| (SHP) - Lo Shapefile  | vettoriale            | .prj                  |
| ESRI è un popolare    |                       |                       |
| formato vettoriale    |                       |                       |
| per sistemi           |                       |                       |
| informativi           |                       |                       |
| geografici. Il dato   |                       |                       |
| geografico viene      |                       |                       |
| distribuito           |                       |                       |
| normalmente           |                       |                       |
| attraverso tre o      |                       |                       |
| quattro files (se     |                       |                       |
| indicato il sistema   |                       |                       |
| di riferimento delle  |                       |                       |
| coordinate). Il       |                       |                       |
| formato è stato       |                       |                       |
| rilasciato da ESRI    |                       |                       |
| come formato (quasi)  |                       |                       |
| aperto**              |                       |                       |
+-----------------------+-----------------------+-----------------------+
| **Tab Separated Value | Dato tabellare        | .tsv                  |
| (TSV) - Formato       |                       |                       |
| testuale per          |                       |                       |
| l’interscambio di     |                       |                       |
| tabelle, le cui righe |                       |                       |
| corrispondono a       |                       |                       |
| record e i cui valori |                       |                       |
| delle singole colonne |                       |                       |
| sono separati da un   |                       |                       |
| carattere di          |                       |                       |
| tabulazione**         |                       |                       |
+-----------------------+-----------------------+-----------------------+
| **Extensible Markup   | Dato strutturato      | .xml                  |
| Language (XML) - E’   |                       |                       |
| un formato di markup, |                       |                       |
| ovvero basato su un   |                       |                       |
| meccanismo che        |                       |                       |
| consente di definire  |                       |                       |
| e controllare il      |                       |                       |
| significato degli     |                       |                       |
| elementi contenuti in |                       |                       |
| un documento o in un  |                       |                       |
| testo attraverso      |                       |                       |
| delle etichette       |                       |                       |
| (markup)**            |                       |                       |
+-----------------------+-----------------------+-----------------------+
(tabella convertita da CSV a Markdown a RST con `Pandoc 2.1.2 <http://pandoc.org/try>`_)

I dati saranno resi disponibili da ciascuna Area in un formato aperto che li renda riutilizzabili direttamente da programmi di elaborazione di calcolo da parte di una macchina (formato machine-readable) e, ove possibile, in formato standard pubblici, leggibili e basati su specifiche pubbliche ed esaustive tali da permetterne l'interpretazione da parte di persone (formati human-readable). I dati saranno resi disponibili accompagnati dai relativi metadati, salvo specifiche e motivate eccezioni, indicate per ciascun dataset da ciascuna Area nell’ambito dell’individuazione periodica dei dati che saranno rilasciati in formato aperto, secondo quanto indicato al punto precedente delle presenti Linee Guida.


------

Modalità di produzione dei dataset dalle piattaforme ICT del PON METRO Palermo
------------------------------------------------------------------------------
Il PON METRO Palermo è un programma di interventi che, tra gli altri, prevede, dal 2017 al 2020, la realizzazione di 7 piattaforme digitali tematiche che riguardano i seguenti ambiti: ambiente e territorio, lavoro e formazione, tributi, edilizia e catasto, cultura e tempo libero, assistenza e sostegno sociale, lavori pubblici. Al momento della redazione delle presenti linee guida comunali open data, l’Amministrazione comunale ha avviato la progettazione esecutiva propedeutica alla realizzazione delle piattaforme ICT alle quali saranno agganciati i processi amministrativi e i servizi degli uffici/aree competenti. 
Al fine di ottimizzare la generazione e pubblicazione dei dataset in open data concernenti le tematiche delle piattaforme digitali del PON METRO, e al fine di stimolarne il riuso, si ritiene valido strutturare le stesse in maniera tale da ospitare, e quindi rendere disponibili, le API (Application Programming Interface) per ogni tipologia di riuso creativo, sia interno all’Amministrazione o esterno da parte della società.

------

I Metadati con il profilo nazionale DCAT_AP_IT
----------------------------------------------
I dati aperti pubblicati attualmente dal Comune di Palermo utilizzano lo schema di metadati definito nelle precedenti linee guida comunali. 
In accordo con le linee guida nazionali per la valorizzazione del patrimonio informativo pubblico è necessario recepire le indicazioni relativo all'utilizzo del profilo nazionale `DCAT-AP_IT <http://www.dati.gov.it/content/dcat-ap-it-v10-profilo-italiano-dcat-ap-0>`_.

Nel  caso  di  dati  geografici  il  profilo  di metadatazione  da  adottare  è  quello  del  `Repertorio Nazionale  dei  Dati  Territoriali (RNDT) <http://www.rndt.gov.it/RNDT/home/index.php?option=com_content&view=article&id=37&Itemid=190>`_,  conforme  alla direttiva `INSPIRE <http://www.agid.gov.it/sites/default/files/leggi_decreti_direttive/01_direttiva_inspire_2007_2_ce.pdf>`_.

In aggiunta, l’insieme dei metadati del profilo DCAT-AP_IT è stato integrato con metadati aggiuntivi ritenuti rilevanti per migliorare il riuso  dei dati pubblicati, come già previsto dalle linee guida nazionali: "*Le pubbliche amministrazioni possono integrare i  metadati previsti dal modello DCAT-AP_IT con metadati aggiuntivi, secondo le proprie necessità seppur nel pieno rispetto delle regole di conformità come definite nella specifica DCAT-AP_IT*".

Questa sezione, non ha lo scopo di approfondire i dettagli tecnici della specifica DCAT-AP_IT, già ampiamente discussi nei documenti ufficiali, ma si focalizza su due aspetti specifici che riguardano l’introduzione della specifica DCAT-AP_IT nel contesto della pubblicazione dei dati aperti del comune di Palermo. Nello specifico in questa sezione verranno presentate: a) le relazioni tra i metadati della specifica DCAT-AP_IT e lo schema di metadati adottato fino adesso, in accordo alla precedente versione delle linee guida comunali,  al fine di consentire l’adeguamento dei metadati già pubblicati, al profilo nazionale della specifica DCAT-AP_IT; b) le integrazioni adottate dal comune di Palermo ai metadati della specifica DCAT-AP_IT.

La specifica DCAT-AP_IT propone una struttura di metadati, basata sui concetti principali di *Catalogo, Dataset e Distribuzione*. Il *Catalogo* rappresenta un insieme di dataset, e pertanto i metadati relativi ad esso riguardano le proprietà dell’intero insieme di dataset (es. Organizzazione che pubblica i dati). Al *Catalogo* sono associati i *Dataset* che lo compongono.  A sua volta ogni *Dataset*, può avere a sé associate diverse Distribuzioni, che si differenziano per il formato usato per la pubblicazione dei dati, la licenza utilizzata, e così via. Ogni *Distribuzione* prevede quindi metadati specifici per descrivere queste proprietà. 
Relativamente al *catalogo*, la versione attuale delle linee guida non prevede dei metadati specifici per l’intero catalogo, pertanto per rendere la pubblicazione dei dati conforme alle specifiche DCAT-AP_IT i metadati relativi al *catalogo* dovranno essere resi disponibili. La seguente tabella riporta i metadati previsti dalla specifica DCAT-AP_IT per la descrizione del *Catalogo*. 

**Metadati per la descrizione del Catalogo (dcatapit:Catalog)** (* Obbligatorio)

+-----------------------+-----------------------+-----------------------+
| **Metadato**          | **Proprietà           | **Descrizione**       |
|                       | DCAT-AP_IT**          |                       |
+=======================+=======================+=======================+
| titolo del catalogo\* | dct:title (M)         | Questa proprietà      |
|                       |                       | contiene un nome dato |
|                       |                       | al Catalogo. Questa   |
|                       |                       | proprietà può essere  |
|                       |                       | ripetuta per          |
|                       |                       | esprimere il titolo   |
|                       |                       | in diverse lingue.    |
+-----------------------+-----------------------+-----------------------+
| descrizione           | dct:description (M)   | Questa proprietà      |
| catalogo\*            |                       | contiene una sintesi  |
|                       |                       | con un testo libero   |
|                       |                       | delle caratteristiche |
|                       |                       | del catalogo. Questa  |
|                       |                       | proprietà può essere  |
|                       |                       | ripetuta per          |
|                       |                       | esprimere la          |
|                       |                       | descrizione in        |
|                       |                       | diverse lingue.       |
+-----------------------+-----------------------+-----------------------+
| home page catalogo    | foaf:homepage (R)     | Questa proprietà si   |
|                       |                       | riferisce ad una      |
|                       |                       | pagina web che funge  |
|                       |                       | da pagina principale  |
|                       |                       | per il Catalogo.      |
+-----------------------+-----------------------+-----------------------+
| lingua catalogo       | dct:language (R)      | Questa proprietà si   |
|                       |                       | riferisce a una       |
|                       |                       | lingua utilizzata nei |
|                       |                       | metadati testuali che |
|                       |                       | descrivono i titoli,  |
|                       |                       | le descrizioni, … dei |
|                       |                       | Dataset nel Catalogo. |
|                       |                       | Questa proprietà può  |
|                       |                       | essere ripetuta se i  |
|                       |                       | metadati sono forniti |
|                       |                       | in più lingue. Deve   |
|                       |                       | essere utilizzato il  |
|                       |                       | vocabolario           |
|                       |                       | http://publications.e |
|                       |                       | uropa.eu/mdr/authorit |
|                       |                       | y/language/           |
+-----------------------+-----------------------+-----------------------+
| temi del catalogo     | dcat:themeTaxonomy    | Questa proprietà si   |
|                       | (R)                   | riferisce ad un       |
|                       |                       | sistema di            |
|                       |                       | organizzazione della  |
|                       |                       | conoscenza (KOS)      |
|                       |                       | usato per             |
|                       |                       | classificare i        |
|                       |                       | dataset del Catalogo. |
|                       |                       | Il valore da          |
|                       |                       | utilizzare per questa |
|                       |                       | proprietà è l’URI del |
|                       |                       | vocabolario stesso    |
|                       |                       | (non gli URI dei      |
|                       |                       | concetti presenti nel |
|                       |                       | vocabolario). Nel     |
|                       |                       | caso del vocabolario  |
|                       |                       | EU Data Theme da      |
|                       |                       | utilizzare            |
|                       |                       | obbligatoriamente per |
|                       |                       | indicare i temi       |
|                       |                       | relativi ai Dataset,  |
|                       |                       | l’URI da indicare è   |
|                       |                       | il seguente:          |
|                       |                       | http://publications.e |
|                       |                       | uropa.eu/resource/aut |
|                       |                       | hority/data-theme     |
+-----------------------+-----------------------+-----------------------+
| editore del           | dct:publisher (M)     | Questa proprietà si   |
| catalogo\*            |                       | riferisce ad          |
|                       |                       | un’entità             |
|                       |                       | (organizzazione)      |
|                       |                       | responsabile a        |
|                       |                       | rendere disponibile   |
|                       |                       | il Catalogo.          |
+-----------------------+-----------------------+-----------------------+
| data rilascio         | dct:issued (R)        | Questa proprietà      |
| catalogo              |                       | contiene la data del  |
|                       |                       | rilascio formale (es. |
|                       |                       | pubblicazione) del    |
|                       |                       | Catalogo.             |
+-----------------------+-----------------------+-----------------------+
| data ultima           | dct:modified (R)      | Questa proprietà      |
| modificacatalogo      |                       | contiene la data più  |
|                       |                       | recente in cui il     |
|                       |                       | Catalogo è stato      |
|                       |                       | aggiornato.           |
+-----------------------+-----------------------+-----------------------+
(tabella convertita da CSV a Markdown a RST con `Pandoc 2.1.2 <http://pandoc.org/try>`_)










Modello di dati per i dati aperti
---------------------------------

I livelli del modello per i metadati
------------------------------------

Licenza per il riutilizzo
-------------------------

Frequenza di aggiornamento
--------------------------

Modalità di pubblicazione dei dataset sul sito web
--------------------------------------------------

Comunicazione e promozione dei dataset pubblicati
-------------------------------------------------
