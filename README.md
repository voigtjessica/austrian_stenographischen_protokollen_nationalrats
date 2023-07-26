# austrian_stenographischen_protokollen_nationalrats
Collecting and slicing Speeched from the Austrian Parlamento for future DNA analisys 

This is the repository that fetches the austrian speeches for the DNA database. 
<br> Originally, we wanted to promote the analisys of two groups of speeches: "data and AI" and "forestry and climate". However, after a first look into the data and KI groups of speeches, we decided to focus our attention on the holz theme, since it would be to difficult to filter what actually was beeing told about data and AI.

<br><br>
The files ```00_AI_search_terms.ipynb```, ```01_scraping.ipynb``` , ```02_scraping_speeches.ipynb``` and ```03_fetch_text_at.ipynb``` are the steps in gathering the speeches from the austrian API, that for many reasons I wanted to do it in separate scripts. The final product is all the speeches saved at ```all_speeches``` directory (that in this repository is empty, since I could not upload so many files) The fourth script ```04_filtering_speeches.ipynb``` filters the speeches according to *holz* and *daten_ki* terms and save them a the directories ```ai_bd``` (empty, due to amount of files) and ```holz_db``` (with all filtered files). The files in the ```holz_db``` folder are the ones in the DNA database (*dna*)
