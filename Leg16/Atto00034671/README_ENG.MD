## 16a Legislature - Bill n. 1929 ##

* Web page for the Bill:
	* Url: http://www.senato.it/leg/16/BGT/Schede/Ddliter/34671.htm

* OpenData site http://dati.senato.it/:
	* Link OpenData: http://dati.senato.it/ddl/34671
	* Query SPARQL for the bill's texts:

        Query by bill's ID:
        
        ```
        PREFIX osr: <http://dati.senato.it/osr/>  
		SELECT DISTINCT ?testoPresentato ?testoApprovato  
		WHERE  
		{  
		    ?ddl a osr:Ddl.  
		    ?ddl osr:idFase 34671 .  
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
		    ?ddl osr:numFase 1929 .  
		    OPTIONAL { ?ddl osr:testoPresentato ?testoPresentato }  
		    OPTIONAL { ?ddl osr:testoApprovato ?testoApprovato }  
		}		
		```
* GitHub page for the bill:
    * Url: https://github.com/SenatoDellaRepubblica/AkomaNtosoBulkData/tree/master/Leg16/Atto00034671		