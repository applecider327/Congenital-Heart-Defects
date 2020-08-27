# NLP-Cogenital-Heart-Defects

NLP (Natural Language Processing) project of developing a system to automatically identify which type of cogenital heart disease is being described in a relevant text (such as in a medical case report). 

The general idea: a text is divided into two parts, title and body. For each component the system looks for key features and utilises those information collectively to come up with a final call. The title part holds greater significance than the rest, however, and as such it may override any other parts of the text. 
For instance, a text piece with the title "Case Report: Fallot's Tetralogy" already offers enough information for the system to output "Tetralogy of Fallot".

There are two types of key features the system looks for - keywords and key descriptions. The former refers to all accepted names of cogenital heart defects and the latter their respective descriptions that uniquely identify each of them. For instance, for the term "Coarctation of the Aorta" the key text patterns to look out for would be something like "cogenital defect where the aorta is narrow" or its similar variations. 

As of now the system is ready for individual classification not yet for massive scale of text sets. Upgrades to be coming soon. 

Every part has been written in the Python programming language. All the data can be found here: https://www.nlm.nih.gov/databases/download/mesh.html / https://pubmed.ncbi.nlm.nih.gov




