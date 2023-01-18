## 19a Legislature - Bill n. 117 ##

* Web page for the Bill:
	* Url: http://www.senato.it/leg/19/BGT/Schede/Ddliter/55294.htm

* OpenData site http://dati.senato.it/:
	* Link OpenData: http://dati.senato.it/ddl/55294
	* Query SPARQL for the bill's texts:

        Query by bill's ID:
        
        ```
        PREFIX osr: <http://dati.senato.it/osr/>  
		SELECT DISTINCT ?testoPresentato ?testoApprovato  
		WHERE  
		{  
		    ?ddl a osr:Ddl.  
		    ?ddl osr:idFase 55294 .  
		    OPTIONAL { ?ddl osr:testoPresentato ?testoPresentato }  
		    OPTIONAL { ?ddl osr:testoApprovato ?testoApprovato }  
		}
		```
				
		Query by bill's number:
		
		```
        PREFIX osr: <http://dati.senato.it/osr/>  
		SELECT DISTINCT ?testoPresentato ?testoApprovato  
		WHERE  
		{  
		    ?ddl a osr:Ddl.  
		    ?ddl osr:numFase 117 .  
		    OPTIONAL { ?ddl osr:testoPresentato ?testoPresentato }  
		    OPTIONAL { ?ddl osr:testoApprovato ?testoApprovato }  
		}		
		```
* GitHub page for the bill:
    * Url: https://github.com/SenatoDellaRepubblica/AkomaNtosoBulkData/tree/master/Leg19/Atto00055294		