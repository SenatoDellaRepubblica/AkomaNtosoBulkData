## Akoma Ntoso - Bulk Data - 16a legislatura - Atto Senato n. 1367 ##

* Scheda del Disegno di Legge - Atto Senato n. 1367:
	* http url: http://www.senato.it/leg/16/BGT/Schede/Ddliter/33184.htm

* Riferimenti al sito OpenData del Senato http://dati.senato.it/:
	* Link OpenData: http://dati.senato.it/ddl/33184
	* Query SPARQL per i documenti relativi all'Atto Senato:

        PREFIX osr: <http://dati.senato.it/osr/>  
		SELECT DISTINCT ?testoPresentato ?testoApprovato  
		WHERE  
		{  
		    ?ddl a osr:Ddl.  
		    ?ddl osr:idFase 1367 .  
		    OPTIONAL { ?ddl osr:testoPresentato ?testoPresentato }  
		    OPTIONAL { ?ddl osr:testoApprovato ?testoApprovato }  
		}
		