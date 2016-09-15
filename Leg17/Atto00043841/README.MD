## 17a Legislatura - Atto Senato n. 1272 ##

* Scheda del Disegno di Legge sul sito del Senato:
	* Url: http://www.senato.it/leg/17/BGT/Schede/Ddliter/43841.htm

* Riferimenti al sito OpenData del Senato http://dati.senato.it/:
	* Link OpenData: http://dati.senato.it/ddl/43841
	* Query SPARQL per i documenti relativi all'Atto Senato:

        ```
        PREFIX osr: <http://dati.senato.it/osr/>  
		SELECT DISTINCT ?testoPresentato ?testoApprovato  
		WHERE  
		{  
		    ?ddl a osr:Ddl.  
		    ?ddl osr:idFase 43841 .  
		    OPTIONAL { ?ddl osr:testoPresentato ?testoPresentato }  
		    OPTIONAL { ?ddl osr:testoApprovato ?testoApprovato }  
		}
		
        PREFIX osr: <http://dati.senato.it/osr/>  
		SELECT DISTINCT ?testoPresentato ?testoApprovato  
		WHERE  
		{  
		    ?ddl a osr:Ddl.  
		    ?ddl osr:numFase 1272 .  
		    OPTIONAL { ?ddl osr:testoPresentato ?testoPresentato }  
		    OPTIONAL { ?ddl osr:testoApprovato ?testoApprovato }  
		}		
		```
* Contenuto dell'Atto nei Bulk Data su GitHub:
    * Url: https://github.com/SenatoDellaRepubblica/AkomaNtosoBulkData/tree/master/Leg17/Atto00043841		