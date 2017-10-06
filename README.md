# TextMining
Szorgalmi Szövegbányánk Megszületése avagy Jézus elhozzá nékünk Kriszmeszre a vizsgamentesség csodáját!

 ### Névelemfelismerés – szorgalmi házi feladat
 
A névelem-felismerést (named entity recognition) segítségével kinyerhetők egy
adott korpuszon belül előforduló névelemek, s ezen belül a tulajdonnevek
(személynevek, helyek, szervezetek és egyéb tulajdonnevek). A feladat angol
nyelvű szövegben 7 típusú entitásnak a felismerése, melyek a következők:
* event = esemény
* geo földrajzi entitás
* gpe = geopolitikai entitás
* obj = objektum, műtárgy
* org rvezet
* per = személy

A felismerendő entitások állhatnak 1 vagy akár több szóból is.
Minden esetben az entitás első szavát külön detektálni kell, ennek
jelzésére a B betű használandó (beginning): így B-event, B-geo, stb. címkékkel
kell a megfelelő szavakat ellátni. Ha az entitások több szóból áll,
akkor az összes többi I-vel jelölendő (inside), azaz I-event, I-geo, stb. címkék;
így összesen az egyéb (O) címkével együtt 15 osztálycímke adódik.

Példa:
Indian border security forces are accusing their Pakistani counterparts of lobbing at least four rockets into northern Punjab state.

Indian: B-gpe,   Pakistani: B-gpe,  Punjab: B-geo,  a többi pedig O címkéjű.
