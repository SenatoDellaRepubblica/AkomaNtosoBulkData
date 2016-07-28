## Akoma Ntoso - Bulk Data - 16a legislatura - Atto Senato n. 1791-B ##

* Scheda del Disegno di Legge - Atto Senato n. 1791-B:
	* http url: http://www.senato.it/leg/16/BGT/Schede/Ddliter/34730.htm

* Riferimenti al sito OpenData del Senato http://dati.senato.it/:
	* Link OpenData: http://dati.senato.it/ddl/34730
	* Query SPARQL per i documenti relativi all'Atto Senato:

        PREFIX osr: <http://dati.senato.it/osr/>  
		SELECT DISTINCT ?testoPresentato ?testoApprovato  
		WHERE  
		{  
		    ?ddl a osr:Ddl.  
		    ?ddl osr:idFase 1791-B .  
		    OPTIONAL { ?ddl osr:testoPresentato ?testoPresentato }  
		    OPTIONAL { ?ddl osr:testoApprovato ?testoApprovato }  
		}
		