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








Modalità di produzione dei dataset dalle piattaforme ICT del PON METRO Palermo
------------------------------------------------------------------------------

I Metadati
----------

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
