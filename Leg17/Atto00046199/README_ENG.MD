## 17a Legislature - Bill n. 2132 ##

* Web page for the Bill:
	* Url: http://www.senato.it/leg/17/BGT/Schede/Ddliter/46199.htm

* OpenData site http://dati.senato.it/:
	* Link OpenData: http://dati.senato.it/ddl/46199
	* Query SPARQL for the bill's texts:

        Query by bill's ID:
        
        ```
        PREFIX osr: <http://dati.senato.it/osr/>  
		SELECT DISTINCT ?testoPresentato ?testoApprovato  
		WHERE  
		{  
		    ?ddl a osr:Ddl.  
		    ?ddl osr:idFase 46199 .  
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
		    ?ddl osr:numFase 2132 .  
		    OPTIONAL { ?ddl osr:testoPresentato ?testoPresentato }  
		    OPTIONAL { ?ddl osr:testoApprovato ?testoApprovato }  
		}		
		```
* GitHub page for the bill:
    * Url: https://github.com/SenatoDellaRepubblica/AkomaNtosoBulkData/tree/master/Leg17/Atto00046199		