## Akoma Ntoso - Bulk Data - 17a legislatura - Atto Senato n. 1504-BIS ##

* Scheda del Disegno di Legge - Atto Senato n. 1504-BIS:
	* http url: http://www.senato.it/leg/17/BGT/Schede/Ddliter/45388.htm

* Riferimenti al sito OpenData del Senato http://dati.senato.it/:
	* Link OpenData: http://dati.senato.it/ddl/45388
	* Query SPARQL per i documenti relativi all'Atto Senato:

        PREFIX osr: <http://dati.senato.it/osr/>  
		SELECT DISTINCT ?testoPresentato ?testoApprovato  
		WHERE  
		{  
		    ?ddl a osr:Ddl.  
		    ?ddl osr:idFase 1504-BIS .  
		    OPTIONAL { ?ddl osr:testoPresentato ?testoPresentato }  
		    OPTIONAL { ?ddl osr:testoApprovato ?testoApprovato }  
		}
		