## 17a Legislature - Bill n. 1498 ##

* Web page for the Bill:
	* Url: http://www.senato.it/leg/17/BGT/Schede/Ddliter/44474.htm

* OpenData site http://dati.senato.it/:
	* Link OpenData: http://dati.senato.it/ddl/44474
	* Query SPARQL for the bill's texts:

        Query by bill's ID:
        
        ```
        PREFIX osr: <http://dati.senato.it/osr/>  
		SELECT DISTINCT ?testoPresentato ?testoApprovato  
		WHERE  
		{  
		    ?ddl a osr:Ddl.  
		    ?ddl osr:idFase 44474 .  
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
		    ?ddl osr:numFase 1498 .  
		    OPTIONAL { ?ddl osr:testoPresentato ?testoPresentato }  
		    OPTIONAL { ?ddl osr:testoApprovato ?testoApprovato }  
		}		
		```
* GitHub page for the bill:
    * Url: https://github.com/SenatoDellaRepubblica/AkomaNtosoBulkData/tree/master/Leg17/Atto00044474		