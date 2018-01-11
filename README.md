# GLO-7006-Paper-NLP

A little article written for a course about Human Machine Interaction (HMI) making a review of all the techniques and models that could be put together in order to create a chatbot. 

Please note that all the pictures are not published here under the license of the current repository. See the article for more details on their origin.


## Agents conversationnels vocaux à base de réseaux de neurones artificiels profonds: un survol

### Guillaume Chevalier
Université Laval

Baccalauréat en génie logiciel 

guillaume.chevalier.2@ulaval.ca

### Samuel Cabral Cruz
Université Laval

Baccalauréat en génie logiciel

samuel.cabral-cruz.1@ulaval.ca

### Abstract
Les approches par réseaux de neurones ont récemment surpassées les approches par algorithmes
classiques pour la majorité des problèmes du traitement de la langue naturelle lorsqu’assez
de données sont disponibles. C’est principalement ce qui explique pourquoi nous voyons de
plus en plus de solutions commerciales implémentant des agents conversationnels, tels que Siri
(Apple) 1 , Alexa (Amazon) 2 et Google Assistant(Google) 3 . Alors, comment créer son propre
agent conversationnel à partir de publications récentes et de technologies de pointe ? Ainsi, nous
regroupons et expliquons tous les sous-systèmes nécessaires à la construction d’un tel agent
qui sera en mesure de recueillir une commande vocale pour ensuite renvoyer une réponse pro-
venant d’une recherche dans une base de données de connaissances en texte naturel, telle que
Wikipédia. Un aspect intéressant de la solution proposée est que la majorité des méthodes em-
ployées se basent sur les réseaux de neurones artificiels, regroupant ainsi une base de connais-
sances commune à chacune des étapes du traitement facilitant par le fait même l’intégration et
le maintien d’une telle architecture. Dans des travaux ultérieurs, une telle architecture pourrait
éventuellement être intégrée en un seul gros réseau de neurones profonds bout à bout plutôt qu’en
plusieurs réseaux distincts juxtaposés les uns aux autres.

