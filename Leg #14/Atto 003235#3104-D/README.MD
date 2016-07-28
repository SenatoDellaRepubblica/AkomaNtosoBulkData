## Akoma Ntoso - Bulk Data - 14a legislatura - Atto Senato n. 3104-D ##

* Scheda del Disegno di Legge - Atto Senato n. 3104-D:
	* http url: http://www.senato.it/leg/14/BGT/Schede/Ddliter/22190.htm

* Riferimenti al sito OpenData del Senato http://dati.senato.it/:
	* Link OpenData: http://dati.senato.it/ddl/22190
	* Query SPARQL per i documenti relativi all'Atto Senato:

        PREFIX osr: <http://dati.senato.it/osr/>  
		SELECT DISTINCT ?testoPresentato ?testoApprovato  
		WHERE  
		{  
		    ?ddl a osr:Ddl.  
		    ?ddl osr:idFase 3104-D .  
		    OPTIONAL { ?ddl osr:testoPresentato ?testoPresentato }  
		    OPTIONAL { ?ddl osr:testoApprovato ?testoApprovato }  
		}
		