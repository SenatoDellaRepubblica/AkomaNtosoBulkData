# Akoma Ntoso - Bulk Data - Italian Senate #

The project contains all the legislative documents of the Italian Senate in the Akoma Ntoso standard.

## Data description ##

Data are structured following the same logical organization of the Italian Senate web site (http://www.senato.it/). For every Legislature every bill has its own web page named "Scheda DDL" where it is possible to view the parliamentary steps with the related documents (presented and approved bills, reports, amendments, etc.)  

The first level of the bulk data is composed of the Legislatures. Any of them contains folders of bills in the Italian Senate. These folders contain the bills' text organized by the type of bill: proposed bill, bill debate, approved bill.

The following section contains a detailed schema of the folders structure described before.

### Folders and file structure ###

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

* **ddlpres**:    it contains the text of the proposed bill
* **ddlcomm**:    it contains the text of the debate in the Committee for the proposed bill
* **ddlmess**:    it contains the text of the approved bill from the Italian Senate
* **emend**:      it contains the amendments voted on the Assembly  
* **emendc**:     it contains the amendments voted on the Committees 
* **NUM_LEG**:    the Legislature number in the Italian Senate  
* **ID_FASE**:    Unique ID for the bill
* **ID_TESTO**:   Unique ID for the bill's text
* **README.MD**:  the main readme or the bill's readme for the folder "AttoID_FASE"

## Author ##

Italian Senate - IT Office

## License ##

CC BY 3.0

## Updates ##

Last update: 12:00:01 27/12/2023