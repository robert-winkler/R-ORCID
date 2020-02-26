# R-ORCID
Bibliographic analysis with R and ORCID

This R markdown script runs in Rstudio (<https://rstudio.com>) and generates from an ORCID (https://orcid.org/inbox?lang=en) identifier of an author ('0000-0001-6732-1958'):

1. A wordcloud based on the most frequent title words:

![Wordcloud of ORCID profile](https://github.com/robert-winkler/R-ORCID/blob/master/Winkler%2C%20Robert%200000-0001-6732-1958.png)

2. A citation summary, based on Crossref (<https://www.crossref.org>) data:

author           | **publications** | **sum_citations** | **H_factor**
 :-------------- | ---------------: | ----------------: | -------------:
Winkler, Robert  |	            82	|              1439 |	           21	


3. A listing of coauthors:

orcid_ident         | orcid_coauthor_names            | coauthor_freq
:-------------------| :-------------------------------| :-------------
0000-0002-0367-337X |	Hertweck, Christian	            | 12		
0000-0001-8228-7663 |	Moreno-Pedraza, Abigail	        | 8		
0000-0002-4908-8934	| Martínez-Jarquín, Sandra      	| 7		
0000-0001-8041-8586	| Gamboa Becerra, Roberto	        | 5		
0000-0002-3463-957X	| García-Lara, Silverio	          | 5		
0000-0002-7471-9152	| Montero-Vargas, Josaphat Miguel |	5		
0000-0002-9493-6402	| Kniemeyer, Olaf	                | 5		
0000-0001-7738-7184	| Ordaz-Ortiz, Jose Juan          |	4		
0000-0002-6738-9554	| López-Castillo, Laura Margarita |	4		
0000-0002-2097-0464	| De Vizcaya-Ruiz, Andrea         |	3	

The wordcloud is exported to a png graphics, the tables into CSV tables.
