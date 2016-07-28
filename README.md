# Akoma Ntoso - Bulk Data - Senato della Repubblica#

Il progetto contiene tutti i documenti legislativi del Senato della Repubblica in standard Akoma Ntoso.

## Descrizione dei dati ##

I dati sono strutturati seguendo la medesima organizzazione logica nel sito web del Senato (http://www.senato.it/). In ogni legislatura, ogni Atto Senato ha una propria pagina di navigazione chiamata "Scheda DdL"", da dove è possibile visualizzare le letture parlamentari ed i testi disponibili (presentato, relazioni, messaggio, emendamenti, etc. ). 

Nei "bulk data" il primo livello sono le legislature e per ognuna di esse le cartelle relative agli Atti Senato con i relativi testi organizzati per tipologia.

Nella seguente sezione vi è uno schema dettagliato della struttura appena descritta.

### Struttura delle cartelle e dei file ###

README.MD

* **Leg #NUM_LEG**
    * **Atto ORDINALE#NUM_ATTO**
        * README-num_fase.MD    
        *   **ddlpres**
            * NUM_TEXT
                * id_testo-ft.akn
        *   **ddlcomm**
            * NUM_TEXT
                * id_testo-ft.akn
        *   **ddlmess**
            * NUM_TEXT
                * id_testo.akn
        *   **emend**
            * id_testo-em.akn
        *   **emendc**
            * id_testo-em.akn
    

### Legenda ###

**ddlpres**:   testo dell'atto così come presentato dal proponente  
**ddlcomm**:    testo della relazione della Commissione relativa all'atto Senato  
**ddlmess**:    testo del messaggio inviato alla Presidenza della Repubblica  
**emend**:      emendamenti in Assemblea  
**emendc**:     emendamenti in Commissione  
**num_atto**:   numero dell'Atto Senato  
**id_testo**:    ID univoco nella Base Dati del Senato del testo  
**README.MD**:  Questo readme  
**README-num_atto.MD**:   per ogni Atto Senato, un file che contiene i riferimenti alla Scheda del Disegno di Legge sul sito del Senato e i riferimenti nell'Open Data Senato.

## Autore ##

Senato della Repubblica

## Licenza ##

[TBD]