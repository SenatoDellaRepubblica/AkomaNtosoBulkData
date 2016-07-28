## Akoma Ntoso - Bulk Data - 16a legislatura - Atto Senato n. 601-711-1171-1198-B ##

* Scheda del Disegno di Legge - Atto Senato n. 601-711-1171-1198-B:
	* http url: http://www.senato.it/leg/16/BGT/Schede/Ddliter/39027.htm

* Riferimenti al sito OpenData del Senato http://dati.senato.it/:
	* Link OpenData: http://dati.senato.it/ddl/39027
	* Query SPARQL per i documenti relativi all'Atto Senato:

        PREFIX osr: <http://dati.senato.it/osr/>  
		SELECT DISTINCT ?testoPresentato ?testoApprovato  
		WHERE  
		{  
		    ?ddl a osr:Ddl.  
		    ?ddl osr:idFase 601-711-1171-1198-B .  
		    OPTIONAL { ?ddl osr:testoPresentato ?testoPresentato }  
		    OPTIONAL { ?ddl osr:testoApprovato ?testoApprovato }  
		}
		