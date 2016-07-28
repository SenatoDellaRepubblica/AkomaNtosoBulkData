## Akoma Ntoso - Bulk Data - 17a legislatura - Atto Senato n. 1342 ##

* Scheda del Disegno di Legge - Atto Senato n. 1342:
	* http url: http://www.senato.it/leg/17/BGT/Schede/Ddliter/44042.htm

* Riferimenti al sito OpenData del Senato http://dati.senato.it/:
	* Link OpenData: http://dati.senato.it/ddl/44042
	* Query SPARQL per i documenti relativi all'Atto Senato:

        PREFIX osr: <http://dati.senato.it/osr/>  
		SELECT DISTINCT ?testoPresentato ?testoApprovato  
		WHERE  
		{  
		    ?ddl a osr:Ddl.  
		    ?ddl osr:idFase 1342 .  
		    OPTIONAL { ?ddl osr:testoPresentato ?testoPresentato }  
		    OPTIONAL { ?ddl osr:testoApprovato ?testoApprovato }  
		}
		