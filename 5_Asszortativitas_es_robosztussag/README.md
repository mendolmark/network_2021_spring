### 5. házi

Kötelező olvasmányok:
- [NetworkScience Book Ch 7: Degree Correlations](http://networksciencebook.com/chapter/7)
- [NetworkScience Book Ch 8: Network Robustness](http://networksciencebook.com/chapter/8)

Válasszatok egyet az alábbi két olvasmány közül:
- [Financial Networks and Contagion](http://www.bengolub.net/papers/financial_networks.pdf): Jacksonról fog szólni a kurzi, cikkekről meg a háziról dumálunk végig. Hosszú cikk, fókuszáljatok a lényegre! Sok a pénzügyes banküzemtanos képletes rész, az nem kell olyan részletesen ahogy le van írva. Viszont a network modellek kellenek nagyon, és érteni kell az alapmodellt is a csődre. A pénzügyesektől ezt szeretném kérni!
- [Networks of military alliances, wars, and international trade](https://www.pnas.org/content/112/50/15277): Ez az IR-os cikk, itt elég HC játékelmélet van, ez viszont kell, mert BA-s játékelmélet és matektudással megérthető. Hajrá! Ha nem értitek a képleteket elsőre nem gond, az órán belemegyünk a bizonyításokba is egy kicsit.

**Feladat: My First Network Model**

A POKEC hálózatra az órán megmutattam, hogy hogyan becsültem meg az életkort. A Házi feladat a Gender megbecslése lesz. 

- Minimum követelmény: Az órán vett kötelező cikk leíró ábráinak reprodukciója. Minimum 5 ábrát szeretnék látni, legyen köztükj heatmap is.
Elvárt teljesítési szint: Model fit, nem kell kitörölni a gendert, elég egy lineáris regresszió. Tudsz jobb modellt, mint a szomszédok átlaga?
- Non plus ultra szint: Töröld ki néhány csúcs genderét, és építs egy modellt ami megbecsli őket. Meg tudod verni a szomszédok átlagát? Fókusz kérdés: Hogyan változik a modell pontossága triplet - szintű featurek bevonásával? (vs diád-szintű featurek)

Az elemzéseteket támasszátok alá leíró statisztikákkal és ábrákkal. Nem egy lineáris regressziót kérek csak, hanem egy elemzést, arról, hogy miképpen működik a Gender ebben a hálózatban az életkorral összefüggésben. Az ábrák legyenek szépek!

A notebookot mindenképpen le kell adni. 2 opciótok van: vagy leadtok egy szépen letisztázott, Markdownos szöveggel teletűzdelt jupyter notebookot, vagy kimásoljátok az ábrákat Wordbe és úgy írtok hozzá szöveget.

Hajrá, ez most egy neház, komplex feladat, javaslom hogy párosodjatok!

[Erről a linkről](https://snap.stanford.edu/data/soc-Pokec.html) tudjátok leszedni az adatot.