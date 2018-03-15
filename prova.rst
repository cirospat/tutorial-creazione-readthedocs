+-----------------------+-----------------------+-----------------------+
| **Metadato**          | **Proprietà**         | **Descrizione**       |
|                       | **DCAT_AP_IT**        |                       |
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
|                       |                       | http://bit.ly/2tWLEJd |
|                       |                       |                       |
|                       |                       |                       |
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
|                       |                       | il seguente           |
|                       |                       | http://bit.ly/2tKxGK0 |
|                       |                       |                       |
|                       |                       |                       |
|                       |                       |                       |
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

------

+--------------------------------+-----------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Metadato                       | Proprietà DCAT-AP_IT  | Descrizione                                                                                                                                                                     |
+================================+=======================+=================================================================================================================================================================================+
| Titolo*                        | dct:title (M)         | Questa proprietà contiene un nome assegnato al Dataset. Questa proprietà può essere ripetuta per esprimere il titolo in diverse lingue                                          |
+--------------------------------+-----------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Descrizione*                   | dct:description (M)   | Questa proprietà contiene una sintesi come testo libero delle caratteristiche del Dataset. Questa proprietà può essere ripetuta per esprimere la descrizione in diverse lingue. |
+--------------------------------+-----------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| punto di contatto
(Contatto)*  | dcat:contactPoint (R) | Questa proprietà contiene informazioni di contatto che possono essere usate per inviare osservazioni e commenti sul Dataset.                                                    |
+--------------------------------+-----------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

