# Auctoritates-FR16-17

La base de données Auctoritates-FR16-17 contient des données relationnelles des grammaires françaises des XVIe et XVIIe siècles.
Ces données ont été collectées dans le <i>Grand Corpus des grammaires et des remarques et des traités sur la langue française (XIVe-XVIIe s.)</i> dirigé par W. Ayres-Bennett, B. Colombat et J.-M. Fournier (2011) et édité par Garnier Numérique

## Architecture de la base Auctoritates/FR16-17
La base de données est divisée dans les BDD suivantes :

<b>mention_gram16</b> -	Autorité sur la langue sans citation dans les grammaires du XVIe siècle<br/>
<b>mention_gram17</b> - 	Autorité sur la langue sans citation dans les grammaires du XVIIe siècle<br/>
<b>citation_gram16</b> -	Autorité sur la langue source de citation explicite ou d’opinion dans les grammaires du XVIe siècle<br/>
<b>citation_gram17</b> -	Autorité sur la langue source de citation explicite ou d’opinion dans les grammaires du XVIe siècle<br/>
<b>mention_citation_gram16-17</b> -	Données des quatre BDD précédentes fusionnées<br/>

## Composition des bases
Les dossiers contiennet les fichiers des données relationnelles, ainsi que d'autres documents relatifs à l'élaboration de graphe de réseaux : 
* Les fichiers nodes.csv contiennent les sommets ou nœuds des relations dans le graphe.
* Les fichiers du type edges.csv encodent les liens, c’est-à-dire, les informations sur les relations que l’on peut établir entre les nœuds. 
* Les fichiers .gephi qui encapsulent une partie du projet (base de données et réglages). Elles sont destinées à être traitées dans le logiciel Gephi.
* Les fichiers images (jpg) : captures d'écran des réglagees, détails des graphes, entre autres.
