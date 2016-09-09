## Akoma Ntoso - Bulk Data - 15a legislatura - Atto Senato n.  ##

* Scheda del Disegno di Legge - Atto Senato n. :
	* Url: http://www.senato.it/leg/15/BGT/Schede/Ddliter/25946.htm

* Riferimenti al sito OpenData del Senato http://dati.senato.it/:
	* Link OpenData: http://dati.senato.it/ddl/25946
	* Query SPARQL per i documenti relativi all'Atto Senato:

        ```
        PREFIX osr: <http://dati.senato.it/osr/>  
		SELECT DISTINCT ?testoPresentato ?testoApprovato  
		WHERE  
		{  
		    ?ddl a osr:Ddl.  
		    ?ddl osr:idFase 25946 .  
		    OPTIONAL { ?ddl osr:testoPresentato ?testoPresentato }  
		    OPTIONAL { ?ddl osr:testoApprovato ?testoApprovato }  
		}
		```
* Riferimenti al sito GitHub del Senato:
    * Url: https://github.com/SenatoDellaRepubblica/AkomaNtosoBulkData/Leg15/Atto00025946		