## Akoma Ntoso - Bulk Data - 17a legislatura - Atto Senato n. 1120-SEXIES ##

* Scheda del Disegno di Legge - Atto Senato n. 1120-SEXIES:
	* http url: http://www.senato.it/leg/17/BGT/Schede/Ddliter/42468.htm

* Riferimenti al sito OpenData del Senato http://dati.senato.it/:
	* Link OpenData: http://dati.senato.it/ddl/42468
	* Query SPARQL per i documenti relativi all'Atto Senato:

        PREFIX osr: <http://dati.senato.it/osr/>  
		SELECT DISTINCT ?testoPresentato ?testoApprovato  
		WHERE  
		{  
		    ?ddl a osr:Ddl.  
		    ?ddl osr:idFase 1120-SEXIES .  
		    OPTIONAL { ?ddl osr:testoPresentato ?testoPresentato }  
		    OPTIONAL { ?ddl osr:testoApprovato ?testoApprovato }  
		}
		