## Akoma Ntoso - Bulk Data - 14a legislatura - Atto Senato n. 255-379-623-640-658-660-B ##

* Scheda del Disegno di Legge - Atto Senato n. 255-379-623-640-658-660-B:
	* http url: http://www.senato.it/leg/14/BGT/Schede/Ddliter/22893.htm

* Riferimenti al sito OpenData del Senato http://dati.senato.it/:
	* Link OpenData: http://dati.senato.it/ddl/22893
	* Query SPARQL per i documenti relativi all'Atto Senato:

        PREFIX osr: <http://dati.senato.it/osr/>  
		SELECT DISTINCT ?testoPresentato ?testoApprovato  
		WHERE  
		{  
		    ?ddl a osr:Ddl.  
		    ?ddl osr:idFase 255-379-623-640-658-660-B .  
		    OPTIONAL { ?ddl osr:testoPresentato ?testoPresentato }  
		    OPTIONAL { ?ddl osr:testoApprovato ?testoApprovato }  
		}
		