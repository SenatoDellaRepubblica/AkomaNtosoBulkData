## Akoma Ntoso - Bulk Data - 14a legislatura - Atto Senato n. 3600/BIS ##

* Scheda del Disegno di Legge - Atto Senato n. 3600/BIS:
	* http url: http://www.senato.it/leg/14/BGT/Schede/Ddliter/23764.htm

* Riferimenti al sito OpenData del Senato http://dati.senato.it/:
	* Link OpenData: http://dati.senato.it/ddl/23764
	* Query SPARQL per i documenti relativi all'Atto Senato:

        PREFIX osr: <http://dati.senato.it/osr/>  
		SELECT DISTINCT ?testoPresentato ?testoApprovato  
		WHERE  
		{  
		    ?ddl a osr:Ddl.  
		    ?ddl osr:idFase 3600/BIS .  
		    OPTIONAL { ?ddl osr:testoPresentato ?testoPresentato }  
		    OPTIONAL { ?ddl osr:testoApprovato ?testoApprovato }  
		}
		