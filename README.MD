# Akoma Ntoso - Bulk Data - Senato della Repubblica #

Il progetto contiene tutti i documenti legislativi del Senato della Repubblica in standard Akoma Ntoso.
([README_ENG.MD](README_ENG.MD) for the English version)

## Descrizione dei dati ##

I dati sono strutturati seguendo la medesima organizzazione logica nel sito web del Senato (http://www.senato.it/). In ogni legislatura, ogni Atto Senato ha una propria pagina di navigazione chiamata "Scheda DdL"", da dove è possibile visualizzare le letture parlamentari ed i testi disponibili (presentato, relazioni, messaggio, emendamenti, etc. ). 

Nei "bulk data" il primo livello è costituito dalle legislature; ognuna di esse contiene poi le cartelle relative agli Atti Senato con i relativi testi organizzati per tipologia.

Nella seguente sezione vi è uno schema dettagliato della struttura appena descritta.

### Struttura delle cartelle e dei file ###

* **README.MD**
* **LegNUM_LEG**
    * **AttoID_FASE**
        * **README.MD**    
        *   **ddlpres**
            * ID_TESTO-ft.akn.xml
        *   **ddlcomm**
            * ID_TESTO-ft.akn.xml
        *   **ddlmess**
            * ID_TESTO-ft.akn.xml
        *   **emend**
            * ID_TESTO-em.akn.xml
        *   **emendc**
            * ID_TESTO-em.akn.xml
    

### Legenda ###

* **ddlpres**:    cartella che contiene il testo dell'atto così come presentato dal proponente  
* **ddlcomm**:    cartella che contiene il testo della relazione della Commissione relativa all'atto Senato  
* **ddlmess**:    cartella che contiene il testo del messaggio trasmesso alla successiva istituzione coinvolta nell'iter  
* **emend**:      cartella che contiene gli emendamenti in Assemblea  
* **emendc**:     cartella che contiene gli emendamenti in Commissione  
* **NUM_LEG**:    Numero della legislatura Senato  
* **ID_FASE**:    ID univoco della fase dell'Atto nell'iter Senato  
* **ID_TESTO**:   ID univoco del testo nella BGT Senato
* **README.MD**:  Readme principale o per atto (contiene i riferimenti alla Scheda del Disegno di Legge sul sito del Senato e i riferimenti nell'Open Data Senato)

## Autore ##

Senato della Repubblica - Servizio dell'Informatica

## Licenza ##

CC BY 3.0

## Aggiornamento ##

Ultimo aggiornamento: 09:45:01 20/03/2024