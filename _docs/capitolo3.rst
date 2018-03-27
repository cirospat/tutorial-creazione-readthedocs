==================================
Capitolo 3 - Modalità Command Line (lavorando offline)
==================================

(Guida per chi usa Windows e non vuole fare a meno dei "piaceri" del terminale in stile bash). 

Il lavoro da terminale consente maggiore flessibilità ed è adatto ad utenti mediamente esperti, questa modalità consente di lavorare avendo il contenuto della repository in locale sul proprio pc, modificare i file e ricaricarli modificati con soli tre comandi e avere così aggiornata la versione del documento su Read the Docs. Interessanti sono anche i tag per il “versioning” e i messaggi di commit, che vedremo come realizzare. 

|

Cominciamo dal software (command line)
--------------------------------------

Per cominciare sarà necessario di installare qualche software qualora non fosse già installato. 
`Git for windows <https://github.com/git-for-windows/git/releases/download/v2.16.2.windows.1/Git-2.16.2-32-bit.exe>`_.

Nello specifico Git for Windows fornisce un’emulazione della BASH per l’utilizzo dell’applicazione da riga di comando, essa funzionerà in pratica come se si stesse lavorando in ambienti UNIX o UNIX like come Linux.

In fase di installazione: abilitare il manager delle credenziali di Github.

**Quale editor di testo utilizzerai?**

Sul terminale per fare piccole modifiche va bene Nano così come Vim entrambi già inclusi nella versione di git installata, mentre per lavorare sul testo fuori dal terminale conviene Notepad++ per Windows https://notepad-plus-plus.org/download.

Per il terminale è possibile utilizzare il cmd di Windows ma consiglio caldamente:
ConEmu https://www.fosshub.com/ConEmu.html/ConEmuSetup.161206.exe.

|

Creare il progetto
-----------------

Per creare il nostro progetto e implementare lo Starter Kit di Docs Italia bisognerà creare una nuova repository su GitHub:

.. figure:: /img/img9.png

Nel settings della repository bisognerà aggiungere Read the Docs come *services* nella sezione *Integrations & services*.

.. figure:: /img/img10.png

Infine sarà necessario importare la repository in Read the Docs come indicato nel paragrafo `Ora andiamo a lavorare su Read the Docs <http://come-creare-guida.readthedocs.io/it/latest/_docs/capitolo2.html>`_. 

Andiamo sul terminale e posizioniamoci in una cartella dove ci saranno i nostri repository e cloniamo lo starter kit.

:: 

   $ git clone https://github.com/italia/docs-italia-starter-kit
   
nella stessa directory cloniamo il repository del nostro progetto

::

   $ git clone https://github.com/pablopers/provadocs
   
Il link del repository lo prendete dal tasto a destra

.. figure:: /img/img11.png

Se dovesse comparire un messaggio di errore non preoccupatevi 

.. figure:: /img/img12.png

ci dice solo che abbiamo clonato un repository vuoto (ancora per poco).

Ora dobbiamo implementare lo Starter kit nel nostro progetto copiando il contenuto completo, files e cartelle, delle cartella **repo-documento** e **repo-configurazione** presenti nello starter kit (usare come meglio preferite il terminale o explorer di Windows).

Procedere alla modifica dei file e alla creazione del documento con i relativi file rst così come già indicato nei paragrafi:

- `"Nel progetto Github abbiamo" <http://come-creare-guida.readthedocs.io/it/latest/_docs/capitolo1.html#nel-progetto-github-abbiamo>`_,

- `"Nota sui file RST" <http://come-creare-guida.readthedocs.io/it/latest/_docs/capitolo1.html#nel-progetto-github-abbiamo>`_.


























------

.. raw:: html
   :file: disqus.html
