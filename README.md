# Personalizovani PageRank za sistem preporuka

PageRank je algoritam za određivanje verovatnoća posećivanja čvorova grafa pri
slučajnim šetnjama. Nastao je kao algoritam za rangiranje internet stranica i
samim tim je pogodan u primeni kod sistema preporuka. Prikazana je njegova
upotreba za predviđanje korisničkih ocena filmova na *MovieLens 100K* [[1]](#1)
skupu podataka.

Primenjen je algoritam aproksimacije personalizovanog PageRank rangiranja
prikazan u [[2]](#2). Rezultati i vreme izvršavanja upoređeni su sa običnim
PageRank algoritmom implementiranim u okviru *NetworkX* paketa, kao i sa SVD
algoritmom implementiranim u okviru *Surprise* paketa.

## Literatura
<a id = "1">[1]</a>
F. Maxwell Harper and Joseph A. Konstan. 2015. The MovieLens Datasets:
History and Context. ACM Transactions on Interactive Intelligent
Systems (TiiS) 5, 4, Article 19 (December 2015), 19 pages.
DOI=http://dx.doi.org/10.1145/2827872

<a id = "2">[2]</a>
Fan Chung and Wenbo Zhao. 2010. A sharp PageRank algorithm with applications to
edge ranking and graph sparsification. In International Workshop on Algorithms
and Models for the Web-Graph. Springer, 2–14.
