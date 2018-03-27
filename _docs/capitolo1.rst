=================
Capitolo 1 - Caricare il progetto editoriale su Github (lavorando online su Github)
=================

(Modalità per lavorare su Github online, adatto per chi ha poca familiarità con gli strumenti di controllo versione)

|

Si inizia con lo starter kit
----------------------------

Questa http://guida-docs-italia.readthedocs.io/it/latest/index/starter-kit.html è la versione che dovremmo usare come modello di base, proposto dal Team Trasformazione Digitale, per riprodurre il nostro documento su Read the Docs.

.. figure:: /img/img2.png

   `la guida dello starter kit <http://guida-docs-italia.Read the Docs.io/it/latest/index/starter-kit.html>`_
   
Cliccando su `scarica lo Starter kit <https://github.com/italia/docs-italia-starter-kit>`_ si viene rimandati al repository del progetto sulla piattaforma Github, cioè qui https://github.com/italia/docs-italia-starter-kit.

.. figure:: /img/img3.png

|

Importare il progetto dello "starter kit" nel proprio account Github
---------------------------------------------------------------------

L'azione da avviare ora è l'importazione del progetto dello starter kit nel proprio account Github, dando un nome al progetto a cui si vuole lavorare.
Quindi andare dentro le directory del progetto per personalizzare i contenuti e i metadati del nostro progetto. Ora vedremo come.

|

Nel progetto Github abbiamo
----------------------------

- una directory ``repo-configurazione`` che contiene due file dove dobbiamo inserire un po di metadati sul progetto che andiamo a pubblicare, come: titolo, descrizione, tags, sito web ente che pubblica il documento;

- una directory **repo-documento** dove si trovano i file:
   - ``conf.py`` dove dobbiamo inserire il titolo del nostro documento che vogliamo visualizzare successivamente su Read the Docs. Importante: su settings_project_name  usare un titolo non molto lungo e non usare parole accentate come à,è,ì,ò,ù, scegliendo il simbolo ' per accentare le vocali. Altra cosa importante settings_basename = 'titolo-documento' cioè su settings_basename e settings_file_name usare parole delimitate dal simbolo - (trattino).
   - ``document_settings.yml`` dove dobbiamo inserire un po di metadati sul progetto che andiamo a pubblicare: titolo, descrizione, tags, sito web ente che pubblica il documento;
   - ``requirements.txt`` che non dobbiamo toccare perché contiene l'istruzione che permette di visualizzare il progetto che stiamo andando a creare all'interno del template di Docs Italia, dove si trovano anche tutti gli altri documenti pubblicati dal Team Trasformazione Digitale, cioè https://docs.developers.italia.it/, 
   
- un file ``AUTHORS`` dove va scritto il nome dell'ente che pubblica il documento e della persona che ha lavorato;

- ``README.md`` un file dove descriviamo brevemente il nostro progetto di pubblicazione del documento;

- ``LICENSE`` un file dove andremo ad inserire il tipo di licenza adottata per pubblicare il nostro documento che verrà visualizzato su Read the Docs;

- ``_docs`` una directory che contiene le pagine del nostro documento, cioè i contenuti veri e propri, che possono essere: testo, immagini, tabelle. Questa directory contiene file di tipo **RST** (reStructuredText). Nel paragrafo che segue approfondiremo questo tipo di file;

- ``_img``: una la directory dove andare a caricare le immagini che si vuole vengano visualizzate poi sulle pagine html di Read the Docs. E' importante nel testo dei file RST fissare le immagini (dentro il testo) usando la seguente sintassi:

:: 

``.. figure:: _img/immagine1.png``
   Quando si vuole inserire un'immagine, è importante dopo aver scritto
   ``.. figure:: _img/immagine1.png``
   
   andare due volte a capo
      
      e lasciare tre spazi vuoti prima di inserire il testo
   
|

La directory _docs e i file RST
-------------------------------

La directory ``_docs`` contiene i file che sono le pagine del nostro documento (e i relativi contenuti) che visualizzeremo sulle pagine html di Read the Docs. 
Questi file sono di tipo **RST (reStructuredText)**, un linguaggio di programmazione molto semplice per sintassi utilizzata.

Un ottima **guida alla sintassi usata dal linguaggio RST** è questa http://docutils.sourceforge.net/docs/user/rst/quickref.html dalla quale è possibile apprendere la sintassi corretta per le nostre necessità di pubblicazione del testo (e immagini, tabelle) nella pagina.

Alcune sintassi del linguaggio ``RST`` per gli usi più comuni di scrittura:

:: 

   Title
   ======  
per il titolo capitolo

|

:: 

   Subtitle 
   --------    
per il titolo paragrafo

|

:: 

   **testo marcato** 
per il **testo marcato**

|

:: 

   *testo in italico* 
per il *testo in italico*

|

:: 

   .. figure:: _image/immagine1.png  

| per inserire un'immagine
| (il titolo del file immagine è ad esempio ``immagine1.png``. Il file dovrà essere caricato in una directory denominata ``img``, è consigliabile caricare questa director contenente le immagini dentro la directory principale del progetto Github)

|

:: 

   `link <https://www.link.it>`_
per inserire un collegamento ipertestuale. Per editare il carattere  `````  è necessario usare contemporaneamente i tasti  ``Alt+96`` da Windows

|

:: 

   .. important::

per inserire testo, se volete inserire una **nota** colorata all'interno del testo nella pagina, verrà visualizzato come di seguito:
   
.. figure:: /img/img4.png

| quando si usa questa **nota** colorata è importante dopo aver scritto
| ``.. important::``
| andare due volte a capo
|    e lasciare tre spazi vuoti prima di scrivere il testo

|

**Nota sui file RST**

Guardando i file ``RST`` di qualsiasi pagina su Github (per esempio di questa pagina) capirete immediatamente come editare la sintassi corretta per le vostre necessità di rappresentazione di testo, immagini, tabelle, note, ecc.

Per tutte le necessità specifiche di editing nel documento (es.: tabelle) vedere `questo elenco di strumenti <http://samba-digitale-pa.readthedocs.io/it/latest/CapitoloOtto.html#strumenti-utilizzati-per-creare-questo-report>`_. 


------

.. raw:: html
   :file: disqus.html
