## 18a Legislatura - Atto Senato n. 1541 ##

([README_ENG.MD](README_ENG.MD) for the English version)

* Scheda del Disegno di Legge sul sito del Senato:
	* Url: http://www.senato.it/leg/18/BGT/Schede/Ddliter/52357.htm

* Riferimenti al sito OpenData Senato http://dati.senato.it/:
	* Link OpenData: http://dati.senato.it/ddl/52357
	* Query SPARQL per i documenti relativi all'Atto Senato:

        Query per ID della Fase:
        
        ```
        PREFIX osr: <http://dati.senato.it/osr/>  
		SELECT DISTINCT ?testoPresentato ?testoApprovato  
		WHERE  
		{  
		    ?ddl a osr:Ddl.  
		    ?ddl osr:idFase 52357 .  
		    OPTIONAL { ?ddl osr:testoPresentato ?testoPresentato }  
		    OPTIONAL { ?ddl osr:testoApprovato ?testoApprovato }  
		}
		```
				
		Query per numero della Fase:
		
		```
        PREFIX osr: <http://dati.senato.it/osr/>  
		SELECT DISTINCT ?testoPresentato ?testoApprovato  
		WHERE  
		{  
		    ?ddl a osr:Ddl.  
		    ?ddl osr:numFase 1541 .  
		    OPTIONAL { ?ddl osr:testoPresentato ?testoPresentato }  
		    OPTIONAL { ?ddl osr:testoApprovato ?testoApprovato }  
		}		
		```
* Contenuto dell'Atto nei Bulk Data su GitHub:
    * Url: https://github.com/SenatoDellaRepubblica/AkomaNtosoBulkData/tree/master/Leg18/Atto00052357		