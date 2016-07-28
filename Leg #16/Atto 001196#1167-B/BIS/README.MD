## Akoma Ntoso - Bulk Data - 16a legislatura - Atto Senato n. 1167-B/BIS ##

* Scheda del Disegno di Legge - Atto Senato n. 1167-B/BIS:
	* http url: http://www.senato.it/leg/16/BGT/Schede/Ddliter/35328.htm

* Riferimenti al sito OpenData del Senato http://dati.senato.it/:
	* Link OpenData: http://dati.senato.it/ddl/35328
	* Query SPARQL per i documenti relativi all'Atto Senato:

        PREFIX osr: <http://dati.senato.it/osr/>  
		SELECT DISTINCT ?testoPresentato ?testoApprovato  
		WHERE  
		{  
		    ?ddl a osr:Ddl.  
		    ?ddl osr:idFase 1167-B/BIS .  
		    OPTIONAL { ?ddl osr:testoPresentato ?testoPresentato }  
		    OPTIONAL { ?ddl osr:testoApprovato ?testoApprovato }  
		}
		