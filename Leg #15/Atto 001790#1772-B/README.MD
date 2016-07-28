## Akoma Ntoso - Bulk Data - 15a legislatura - Atto Senato n. 1772-B ##

* Scheda del Disegno di Legge - Atto Senato n. 1772-B:
	* http url: http://www.senato.it/leg/15/BGT/Schede/Ddliter/29011.htm

* Riferimenti al sito OpenData del Senato http://dati.senato.it/:
	* Link OpenData: http://dati.senato.it/ddl/29011
	* Query SPARQL per i documenti relativi all'Atto Senato:

        PREFIX osr: <http://dati.senato.it/osr/>  
		SELECT DISTINCT ?testoPresentato ?testoApprovato  
		WHERE  
		{  
		    ?ddl a osr:Ddl.  
		    ?ddl osr:idFase 1772-B .  
		    OPTIONAL { ?ddl osr:testoPresentato ?testoPresentato }  
		    OPTIONAL { ?ddl osr:testoApprovato ?testoApprovato }  
		}
		