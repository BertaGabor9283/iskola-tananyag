STATISZTIKA I
Leíró statisztikai
mutatók

---

loszlások jellege

A gyakorisági eloszlások jellegzetességei
■ Helyzet: a közepesnek mondható

ismérvértékek (középértékek) vízszintes
tengelyen elfoglalt helye → helyzetmutatók

■ Szóródás: az ismérvértékek egymástól

vagy valamely kitüntetett értéktől való
eltérései → szóródási mérőszámok

■ Alak: a gyakorisági eloszlás görbéjének

kinézete egy vele azonos helyzetű és
szóródású normális eloszlás gyakorisági
görbéjéhez képest → ferdeség, csúcsosság
mérőszámai
2
Módusz

Balázsné Mócsai
Andrea
Eloszlások
jellege

Medián

Módusz

Terjedelem

Átlagok

Medián

Átlagok

Aszimmetria

Szórás

STATISZTIKA
I
Terjedelem

Szórás

Csúcsosság

Aszimmetria

Csúcsosság

---

loszlások jellege

5.2. HELYZETMUTATÓK
■ A mennyiségi ismérvet egyetlen számmal jellemzik
□ mértékegység: Y ismérv mértékegysége

pl. minimum, alsó kvartilis, stb.
■ A középértékek speciális helyzetmutatók
■ A középérték legyen …
□ közepes helyzetű,
□ tipikus,
□ egyértelműen és könnyen meghatározható,
□ könnyen értelmezhető
3
Módusz

Balázsné Mócsai
Andrea
Eloszlások
jellege

Medián

Módusz

Terjedelem

Átlagok

Medián

Átlagok

Aszimmetria

Szórás

STATISZTIKA
I
Terjedelem

Szórás

Csúcsosság

Aszimmetria

Csúcsosság

---

loszlások jellege

A középértékek osztályozása
■ Helyzeti középértékek
□ módusz
□ medián
■ Számított középértékek (átlagok)

□ számtani átlag
□ mértani átlag
□ harmonikus átlag

□ négyzetes átlag

4
Módusz

Balázsné Mócsai
Andrea
Eloszlások
jellege

Medián

Módusz

Terjedelem

Átlagok

Medián

Átlagok

Aszimmetria

Szórás

STATISZTIKA
I
Terjedelem

Szórás

Csúcsosság

Aszimmetria

Csúcsosság

---

loszlások jellege

– Mi a módusz
kedvenc mondata?

5.2.1. MÓDUSZ

– ???
– Ezt már más is
mondta ☺

diszkrét ismérvnél a leggyakrabban
előforduló (tipikus) ismérvérték
■ folytonos ismérvnél a gyakorisági
görbe maximumához tartozó érték

osztályközös gyakorisági sorból közelíthető
□ nyers módusz: a móduszt (mint legtöbb egységet) tartalmazó
osztályköz osztályközepe: Ymo
□ korrigált érték egyenlő osztályközhossz esetén:
■

~

da
Mo = Ymo,0 +
 hmo  da = fmo − fmo−1 ; df = fmo − fmo+1
da + df

□

nem egyenlő osztályközhossz esetén becslés az átszámított (fi/hi)
gyakoriságok alapján
Módusz

Balázsné Mócsai
Andrea
Eloszlások
jellege

Medián

Módusz

Terjedelem

Átlagok

Medián

Átlagok

Aszimmetria

Szórás

STATISZTIKA
I
Terjedelem

Szórás

Csúcsosság

Aszimmetria

Csúcsosság

5

---

loszlások jellege

Az élveszületések súly szerinti megoszlása (2025)
Súly (g)

Gyakoriság

0

499

37

500

999

334

1000

1499

534

1500

1999

1 280

2000

2499

4 036

2500

2999

13 667

3000

3499

29 499

3500

3999

21 392

4000

4499

5 739

4500

4999

754

5000

99

Összesen

30 000

25 000

20 000

15 000

10 000

5 000

77 371
0

3000 3331 3500

nyers módusz: 3250
korrigált:
~

29499 − 13667
Mo = 3000 + 500 
 3331
(29499 − 13667) + (29499 − 21392)
Forrás: https://www.ksh.hu
Módusz

Balázsné Mócsai
Andrea
Eloszlások
jellege

Medián

Módusz

Terjedelem

Átlagok

Medián

Átlagok

Aszimmetria

Szórás

STATISZTIKA
I
Terjedelem

Szórás

Csúcsosság

Aszimmetria

Csúcsosság

6

---

loszlások jellege

A módusz tulajdonságai
nem érzékeny a szélső (outlier) értékekre (robusztus)
■ valamennyi mérési skála esetén alkalmazható
■ a helyettesítéskor elkövetett hibák számát minimalizálja
■ nem mindig létezik, mert nem mindig lehet egyértelműen meghatározni
□ Excelben MÓDUSZ.TÖBB függvény → tömb értékű
■ kevés adat esetén nem használható
□ az elemszámhoz képest sokféle értéket felvevő diszkrét ismérvnél egy
konkrét érték bekövetkezésének esélye kicsi → a sokaságot
folytonosnak tekintjük, a móduszt az osztályközös gyakorisági sorból
becsüljük
a magyar városok népességszáma (január 1):
2024-ben egy pár → módusz = 3799 ?
2025-ben két pár → módusz = 3921, 11654 ?
■

7

Módusz

Balázsné Mócsai
Andrea
Eloszlások
jellege

Medián

Módusz

Terjedelem

Átlagok

Medián

Átlagok

Aszimmetria

Szórás

STATISZTIKA
I
Terjedelem

Szórás

Csúcsosság

Aszimmetria

Csúcsosság

---

loszlások jellege

A magyar városok lakosságszáma Budapest nélkül (2025. január 1.)
Lakosságszám

fi

hi

fi (egységre)

fi (ezerre)

940

5000

106

4060

0,02611

26,11

5001

10000

106

5000

0,02120

21,20

10001

20000

77

10000

0,00770

7,70

20001

40000

35

20000

0,00175

1,75

40001

70000

13

30000

0,00043

0,43

70001

110000

4

40000

0,00010

0,10

110001

150000

4

40000

0,00010

0,10

150001
202130
Összesen

2

52130

0,00004

0,04

347

két azonos gyakoriság (106), de az osztályközhossz eltér
→ azonos hosszra vetítve (pl. fi-t az osztályközhosszal osztva)
módusz egy főre eső osztályközhosszal:
~
0,02611 − 0
Mo = 940 + 4060 
 4358 fő
(0,02611 − 0) + (0,0261 − 0,02120)
~
26,11
1000 főre vetítve: Mo = 940 + 4060 
 4358 fő
26,11 + (26,11 − 21,2)
Forrás: https://www.ksh.hu
Módusz

Balázsné Mócsai
Andrea
Eloszlások
jellege

Medián

Módusz

Terjedelem

Átlagok

Medián

Átlagok

Aszimmetria

Szórás

STATISZTIKA
I
Terjedelem

Szórás

Csúcsosság

Aszimmetria

Csúcsosság

8

---

loszlások jellege

5.2.2. MEDIÁN
■

A rangsorba állított értékeket két egyforma
gyakoriságú részre bontja
□ gyakorisági görbénél a görbe alatti terület
felezőjénél lévő érték

■

Meghatározása:

N+1
□ egyedi adatokra: a rangsor
-edik eleme
2

N
 −1
− fme
~
□ osztályközös gyakorisági sorból: Me = Yme,0 + 2
 hme
fme

9
Módusz

Balázsné Mócsai
Andrea
Eloszlások
jellege

Medián

Módusz

Terjedelem

Átlagok

Medián

Átlagok

Aszimmetria

Szórás

STATISZTIKA
I
Terjedelem

Szórás

Csúcsosság

Aszimmetria

Csúcsosság

---

loszlások jellege

… folytatás (élveszületések száma súly szerint) …
Súly

Gyakoriság

Kum.gyak.

499

37

37

500

999

334

371

1000

1499

534

905

1500

1999

1280

2185

2000

2499

4036

6221

2500

2999

13667

19888

3000

3499

29499

49387

3500

3999

21392

70779

4000

4499

5739

76518

4500

4999

754

77272

99

77371

5000
Összesen

77371

a (becsült) medián sorszáma: 77371/2 = 38686
~

38686 − 19888
Me = 3000 + 500 
 3319
49387 − 19888
10
Módusz

Balázsné Mócsai
Andrea
Eloszlások
jellege

Medián

Módusz

Terjedelem

Átlagok

Medián

Átlagok

Aszimmetria

Szórás

STATISZTIKA
I
Terjedelem

Szórás

Csúcsosság

Aszimmetria

Csúcsosság

---

loszlások jellege

A medián tulajdonságai
mindig egyértelműen meghatározható
◼ nem érzékeny a szélső (outlier) értékekre (robusztus)
◼ sorrendi, intervallum és arány skálán használható
◼ sok azonos adat esetén nem jó mutató
◼ ha minden ismérvértéket a mediánnal helyettesítenénk, akkor
összességében a legkisebb hibát követnénk el, ha a hiba az (abszolút)
eltérést jelenti
◼

N

 Y − A = min, ha A = Me
i

i =1

Magyarország városai népességszámának mediánja (2025. január 1.)
□ Budapest nélkül 7663 fő
□ Budapesttel együtt 7682 fő
11
Módusz

Balázsné Mócsai
Andrea
Eloszlások
jellege

Medián

Módusz

Terjedelem

Átlagok

Medián

Átlagok

Aszimmetria

Szórás

STATISZTIKA
I
Terjedelem

Szórás

Csúcsosság

Aszimmetria

Csúcsosság

---

loszlások jellege

5.2.3. SZÁMÍTOTT KÖZÉPÉRTÉKEK
N

Y

Y
Y + Y + ... + Y

=
=
■ Számtani átlag: Y =
1

2

N

i =1

N

■

i

N

i

N

A számtani átlag számítása gyakorisági sorból:
~
fi Yi  fi Yi
fi

Y=
=
=  Yi =  gi Yi
N
N
 fi
Yi: i-edik érték vagy osztályközép (→ becsült átlag)
□ fi: gyakoriságok (összegük: N), gi: relatív gyakoriságok (összegük: 1)
□ elnevezés: súlyozott átlag
□

12
Módusz

Balázsné Mócsai
Andrea
Eloszlások
jellege

Medián

Módusz

Terjedelem

Átlagok

Medián

Átlagok

Aszimmetria

Szórás

STATISZTIKA
I
Terjedelem

Szórás

Csúcsosság

Aszimmetria

Csúcsosság

---

loszlások jellege

… folytatás (élveszületések száma súly szerint) …

~

Y=

37  250 + 334  750 + ... + 99  5250
 3288
77371

Excel megvalósítás: SZUM függvény tömbműveletekkel
régebbi Office verziókban a tömb műveleteket csak a SZORZATÖSSZEG tudta

□
Módusz

Balázsné Mócsai
Andrea
Eloszlások
jellege

Medián

Módusz

Terjedelem

Átlagok

Medián

Átlagok

Aszimmetria

Szórás

STATISZTIKA
I
Terjedelem

Szórás

Csúcsosság

Aszimmetria

Csúcsosság

13

---

loszlások jellege

– Miben hasonlít egymásra a nyesett átlag
és a politikus?

A számtani átlag tulajdonságai
■

– ???

NY =  Yi  (Yi − Y) = 0 → ha minden értéket az átlaggal
helyettesítünk, akkor az így elkövetett hibák előjeles összege 0

– Mindkettő gondosan
eltünteti a szélsőségeket ☺

■  (Yi − A) = min, ha A = Y → az átlag minimalizálja az elkövetett hibát, ha azt
2

négyzetösszegként értelmezzük

■

■
■
■

lineárisan transzformált ismérvértékek átlaga az átlag lineárisan transzformált
értéke: Li = a + bYi  L = a + bY
csak mennyiségi ismérvekre számolható
számításánál minden értéket figyelembe veszünk
érzékeny a kiugró értékekre (→ nyesett átlag)
Magyarország városai népességszámának átlaga (2025. január 1.)
□ Budapest nélkül 14432 fő
□ Budapesttel együtt 19233 fő
14
Módusz

Balázsné Mócsai
Andrea
Eloszlások
jellege

Medián

Módusz

Terjedelem

Átlagok

Medián

Átlagok

Aszimmetria

Szórás

STATISZTIKA
I
Terjedelem

Szórás

Csúcsosság

Aszimmetria

Csúcsosság

---

loszlások jellege

KÖZÉPÉRTÉKEK ÖSSZEHASONLÍTÁSA
HÁTRÁNYOK

ELŐNYÖK

■

■

■

Módusz
□ nem függ a kiugró értékektől
□ minden mérési szint esetén jó
□ a helyettesítéskor elkövetett hibák
számát minimalizálja
Medián
□ egyértelműen meghatározható
□ nem függ a kiugró értékektől
□ sorrendi skálán is használható
□ az abszolút eltérésösszeg min.
Számtani átlag
□ egyértelműen meghatározható
□ minden adatot felhasznál
□ az eltérésnégyzet-összeg min.
□ indukcióra jól használható

■

Módusz
□ nem vesz figyelembe minden adatot
□ nem mindig határozható meg
egyértelműen

■

Medián
□ sok egyforma értéknél rossz
□ nem vesz figyelembe minden adatot
□ névleges skálán nem számítható

■

Számtani átlag
□ csak mennyiségi ismérvekre számítható
□ minden adatot felhasznál
□ érzékeny a kilógó értékekre
15

Módusz

Balázsné Mócsai
Andrea
Eloszlások
jellege

Medián

Módusz

Terjedelem

Átlagok

Medián

Átlagok

Aszimmetria

Szórás

STATISZTIKA
I
Terjedelem

Szórás

Csúcsosság

Aszimmetria

Csúcsosság

---

loszlások jellege

Számított középértékek (átlagok)
Elnevezés

Jelölés

Képlet

Súlyozott

számtani
(aritmetikai) átlag

Ȳ

Y
N

fY = fY = g Y

f
N


ÁTLAG

mértani
(geometriai) átlag

Ȳg

N

 Yi

 fi  Y fi = N  Y fi

MÉRT.KÖZÉP

Ȳh

N
1
Y
i

f = N
f
f
Y Y

HARM.KÖZÉP

harmonikus átlag

négyzetes
(kvadratikus) átlag

i

i

i

i

i

i

i

Y

Ȳq

i

Excel függvény

i

i

i
i

i

i

2
f
Y
i i

2

i

f

N

i

=

i

2
f
Y
i i

N
16

Módusz

Balázsné Mócsai
Andrea
Eloszlások
jellege

Medián

Módusz

Terjedelem

Átlagok

Medián

Átlagok

Aszimmetria

Szórás

STATISZTIKA
I
Terjedelem

Szórás

Csúcsosság

Aszimmetria

Csúcsosság

---

loszlások jellege

Átlagok alkalmazási területei
■

Számtani átlag: adatredukció, előrejelzés

■

Mértani átlag: növekedési ütem jellemzése
□

■

például láncviszonyszámok átlagolása

Harmonikus átlag: részviszonyszám elemzés
S

□ például átlag értékösszeg alapján: Yh =

■

i

Négyzetes átlag: hibaszámítás
□

■

f

például szórás (később)

=

S
Si
Y
i

Relációs viszony az átlagok között: Ymin  Ȳh  Ȳg  Ȳ  Ȳq  Ymax

17
Módusz

Balázsné Mócsai
Andrea
Eloszlások
jellege

Medián

Módusz

Terjedelem

Átlagok

Medián

Átlagok

Aszimmetria

Szórás

STATISZTIKA
I
Terjedelem

Szórás

Csúcsosság

Aszimmetria

Csúcsosság

---

loszlások jellege

– Miért nem szeret
a szórás az átlag
közelében lenni?

5.3. SZÓRÓDÁSI MUTATÓK
■ Szóródás: a megfigyelt Y értékek különbözősége
■ Mérési lehetőségek:
□

terjedelem-mutatók

egymástól való eltérések
◆

□

– Mert neki mindig
kell egy kis távolság ☺

szélső értékek eltérése
◆

□

– ???

pl. átlagos abszolút különbség

egy kitüntetett értéktől (átlag) való eltérések
◆

pl. átlagos abszolút eltérés, szórás

18
Módusz

Balázsné Mócsai
Andrea
Eloszlások
jellege

Medián

Módusz

Terjedelem

Átlagok

Medián

Átlagok

Aszimmetria

Szórás

STATISZTIKA
I
Terjedelem

Szórás

Csúcsosság

Aszimmetria

Csúcsosság

---

loszlások jellege

5.3.1. Terjedelem-mutatók
■

(Teljes) terjedelem: R = Ymax – Ymin
□
□

■

előnye: egyszerű
hátránya: csak a két szélsőséges értéktől függ

Interkvartilis terjedelem:

R0,5 = IQR = Q3 – Q1
□ a középső 50% terjedelme
□ hasonlóan lehet a középső 80%-ot figyelembe
venni a két szélső decilis eltéréseként
(interdecilis terjedelem, R0,8 = IDR)
■

Becslés osztályközös gyakorisági sorból:
□
□

R esetében gondot okoz, ha a legelső és legutolsó osztályköz nyitott →
kiegészítő információ kell
Interkvartilis terjedelem becslése az alsó és felső kvartilis becslésén át
Módusz

Balázsné Mócsai
Andrea
Eloszlások
jellege

Medián

Módusz

Terjedelem

Átlagok

Medián

Átlagok

Aszimmetria

Szórás

STATISZTIKA
I
Terjedelem

Szórás

Csúcsosság

Aszimmetria

Csúcsosság

19

---

loszlások jellege

5.3.2. Az abszolút eltérések mutatói
■

Átlagos abszolút különbség
□

□
□

■

minden lehetséges módon párba állított Y értékek abszolút eltéréseinek átlaga:
Yi − Yj

G= i j
N  (N − 1)
ha minden ismérvérték egyforma, akkor G=0
bonyolult számítási mód

Átlagos abszolút eltérés

Y −Y

□ az átlagtól vett abszolút eltérések átlaga: δ =
i

N

□
□
□

ha minden ismérvérték egyforma, akkor δ=0
ritkán használják, mert az abszolút érték nehezen kezelhető matematikailag
Excelben: ÁTL.ELTÉRÉS
20
Módusz

Balázsné Mócsai
Andrea
Eloszlások
jellege

Medián

Módusz

Terjedelem

Átlagok

Medián

Átlagok

Aszimmetria

Szórás

STATISZTIKA
I
Terjedelem

Szórás

Csúcsosság

Aszimmetria

Csúcsosság

---

loszlások jellege

5.3.3. SZÓRÁS
A szóródás legfontosabb mérőszáma
■ A (számtani) átlagtól vett eltérések négyzetes átlaga: σ =
■

(Y − Y)

2

i

N
olyan átlagos hiba, amit azzal követnénk el, ha az adatokat az átlaggal
2
helyettesítenénk
fi ( Yi − Y )

súlyozott esetben (gyakorisági sor): σ =

□
□

f

i

■

A szórásnégyzet érték elnevezése: variancia
jelölés: Var(Y)

□

■

Excel: SZÓR.S ill. VAR.S függvény (súlyozatlan)
régebbi verziók: SZÓRÁSP ill. VARP függvény

□

21
Módusz

Balázsné Mócsai
Andrea
Eloszlások
jellege

Medián

Módusz

Terjedelem

Átlagok

Medián

Átlagok

Aszimmetria

Szórás

STATISZTIKA
I
Terjedelem

Szórás

Csúcsosság

Aszimmetria

Csúcsosság

---

loszlások jellege

Eltérések az átlagtól
-1

+1

Y

-2

+5

-3

Yi − Y
=0
átlagtól vett átlagos eltérés: 
N
Yi − Y 1 + 1 + 2 + 3 + 5
=
= 2,4
átlagtól vett átlagos abszolút eltérés: δ = 
N
5

átlagtól vett átlagos négyzetes eltérés (variancia) → szórás:

( Y − Y ) = (−1) + 1 + (−2) + (−3) + 5 = 8 → σ = 8  2,83
2

σ2 = 

2

i

2

N

2

2

2

5

22
Módusz

Balázsné Mócsai
Andrea
Eloszlások
jellege

Medián

Módusz

Terjedelem

Átlagok

Medián

Átlagok

Aszimmetria

Szórás

STATISZTIKA
I
Terjedelem

Szórás

Csúcsosság

Aszimmetria

Csúcsosság

---

loszlások jellege

A szórás tulajdonságai, relatív szórás
a szórás értéke akkor és csakis akkor nulla, ha az összes ismérvérték
egyenlő
■ értékét a szélsőséges értékek befolyásolják (nem robusztus)
■ lineárisan transzformált értékek szórása: Li = a + b  Yi  σL = b  σ Y
■

Y  Y 

■ alternatív számítási lehetőség: σ = Y − Y =
−

2

2
q

σ
■ Relatív szórás: V =
Y

i

2

N

2

i

 N 

mértékegység nélküli szám (gyakran % formátum)
különböző sokaságok vagy ismérvek szóródásának összehasonlítására

□

□

Magyarország városai népességének szóródási mutatói (2025)
Budapest nélkül: IQR = 10176; IDR = 25729; σ = 22619 fő; V = 1,57
Budapesttel:
IQR = 10199; IDR = 25834; σ = 92242 fő; V = 4,80

□
□
Módusz

Balázsné Mócsai
Andrea
Eloszlások
jellege

Medián

Módusz

Terjedelem

Átlagok

Medián

Átlagok

Aszimmetria

Szórás

STATISZTIKA
I
Terjedelem

Szórás

Csúcsosság

Aszimmetria

Csúcsosság

23

---

loszlások jellege

TESZT: A04 – Szóródási- és alakmutatók
3. kérdés
Tegyük fel, hogy a kistelepülések pótlólagos kiadásaik fedezésére valamennyi egység
a) 10 %-os
b) 500 ezer Ft
évközi kiegészítést kap a költségvetésből.
Hogyan változik a kistelepülések költségvetésből kapott összegének a szórása?
a. Egyik esetben sem változik.
b. Az a) esetben 10%-kal nő, a b) esetben nem változik.
c. Az a) esetben nem változik, a b) esetben 500 ezer Ft-tal nő.
d. Az a) esetben 10%-kal nő, a b) esetben 500 ezer Ft-tal nő.

24
Módusz

Balázsné Mócsai
Andrea
Eloszlások
jellege

Medián

Módusz

Terjedelem

Átlagok

Medián

Átlagok

Aszimmetria

Szórás

STATISZTIKA
I
Terjedelem

Szórás

Csúcsosság

Aszimmetria

Csúcsosság

---

loszlások jellege

TESZT: A04 – Szóródási- és alakmutatók
8. kérdés
Tegyük fel, hogy a kereskedelemben dolgozó eladók 1980. évi és 2012. évi keresetének a
szóródását akarjuk összehasonlítani. Mely mérőszám(ok) alkalmazható(k) e célra?
a. A terjedelem.
b. A relatív szórás.
c. Az interkvartilis terjedelem.
d. A szórás.

25
Módusz

Balázsné Mócsai
Andrea
Eloszlások
jellege

Medián

Módusz

Terjedelem

Átlagok

Medián

Átlagok

Aszimmetria

Szórás

STATISZTIKA
I
Terjedelem

Szórás

Csúcsosság

Aszimmetria

Csúcsosság

---

loszlások jellege

5.3. AZ ELOSZLÁSOK ALAKJA
■ Módusz szempontjából:

egymóduszú
□ többmóduszú
□

■ Egymóduszú eloszlások alakjának eltérése a normális

eloszlástól
□

aszimmetria
balra elnyúló
◆ szimmetrikus
◆ jobbra elnyúló
◆

□

csúcsosság
hegyesebb
◆ lapultabb
◆

26
Módusz

Balázsné Mócsai
Andrea
Eloszlások
jellege

Medián

Módusz

Terjedelem

Átlagok

Medián

Átlagok

Aszimmetria

Szórás

STATISZTIKA
I
Terjedelem

Szórás

Csúcsosság

Aszimmetria

Csúcsosság

---

loszlások jellege

Felvételi pontszámok alakulása (2011/2012, 8. osztály)

Forrás: https://www.oh.gov.hu
Módusz

Balázsné Mócsai
Andrea
Eloszlások
jellege

Medián

Módusz

Terjedelem

Átlagok

Medián

Átlagok

Aszimmetria

Szórás

STATISZTIKA
I
Terjedelem

Szórás

Csúcsosság

Aszimmetria

Csúcsosság

27

---

loszlások jellege

Felvételi pontszámok alakulása (2017/2018, 8. osztály)

28
Módusz

Balázsné Mócsai
Andrea
Eloszlások
jellege

Medián

Módusz

Terjedelem

Átlagok

Medián

Átlagok

Aszimmetria

Szórás

STATISZTIKA
I
Terjedelem

Szórás

Csúcsosság

Aszimmetria

Csúcsosság

---

loszlások jellege

Matematika érettségi pontszámok (2022/2023. május - közép)
3000

2500

2000

1500

1000

500

0

0

2

4

6

8 10 12 14 16 18 20 22 24 26 28 30 32 34 36 38 40 42 44 46 48 50 52 54 56 58 60 62 64 66 68 70 72 74 76 78 80 82 84 86 88 90 92 94 96 98 100

kb. 70,8 ezer érettségiző

saját oktató javít
jegyhatárok: 20/40/60/80

átlag: 53 pont
Forrás: https://oktatas.hu

Módusz

Balázsné Mócsai
Andrea
Eloszlások
jellege

Medián

Módusz

Terjedelem

Átlagok

Medián

Átlagok

Aszimmetria

Szórás

STATISZTIKA
I
Terjedelem

Szórás

Csúcsosság

Aszimmetria

Csúcsosság

29

---

loszlások jellege

Matematika érettségi pontszámok, (2022-2023, május - emelt)
500

450

400

350

300

250

200

150

100

50

0

0

5

10

15

20

25

30

35

40

45

50

55

60

65

70

75

80

85

központi javítás
ponthatárok: 30/50/70/90

90

95

100

105

110

115

120

125

130

135

140

145

150

kb. 5 ezer érettségiző
átlag: 94 pont (150-ből)
30

Módusz

Balázsné Mócsai
Andrea
Eloszlások
jellege

Medián

Módusz

Terjedelem

Átlagok

Medián

Átlagok

Aszimmetria

Szórás

STATISZTIKA
I
Terjedelem

Szórás

Csúcsosság

Aszimmetria

Csúcsosság

---

loszlások jellege

5.3.1. ASZIMMETRIA - Jobbra elnyúló eloszlások
Társadalmi-gazdasági jelenségeknél gyakori eloszlásfajta (baloldali
korlát)
■ módusz < medián < átlag
■

□

mérsékelt aszimmetriánál
jellemzően a medián harmadol,
közelebb esik az átlaghoz

módusz
medián

Az első kvantilis (pl. Q1)
távolsága a mediántól kisebb, mint
az utolsó kvantilis (Q3) távolsága a
mediántól
3
Yi − Y )
(

■
0
N
■

átlag

Q1 Me

Q3

31
Módusz

Balázsné Mócsai
Andrea
Eloszlások
jellege

Medián

Módusz

Terjedelem

Átlagok

Medián

Átlagok

Aszimmetria

Szórás

STATISZTIKA
I
Terjedelem

Szórás

Csúcsosság

Aszimmetria

Csúcsosság

---

loszlások jellege

Szimmetrikus/aszimmetrikus eloszlások
Balra elnyúló

Szimmetrikus

Jobbra elnyúló

Y  Me  Mo

Y = Me = Mo

Mo  Me  Y

Me − Yp  Y1−p − Me

Me − Yp = Y1−p − Me

Me − Yp  Y1−p − Me

Y − Y)
(

M Y =
=0

Y − Y)
(

M Y =
0

(p<0,5)

Y − Y)
(

M Y =
0
3

3

( )

i

3

N

3

( )

i

3

N

3

( )

i

N

32
Módusz

Balázsné Mócsai
Andrea
Eloszlások
jellege

Medián

Módusz

Terjedelem

Átlagok

Medián

Átlagok

Aszimmetria

Szórás

STATISZTIKA
I
Terjedelem

Szórás

Csúcsosság

Aszimmetria

Csúcsosság

---

loszlások jellege

– Hallom, tegnap ferde
estét tartottatok.

Aszimmetria-mutatók

– Igen, bár a társaság
eleinte teljesen normális
volt.

 pozitív → jobbra elnyúló eloszlás

→ szimmetrikus eloszlás
■ Érték szerint:  nulla
– És mi történt?
negatív → balra elnyúló eloszlás
– Néhányan elhúztak a

kocsmába ☺
3 Y − Me
■ Pearson-féle aszimmetria-mutató: P =
σ
□ mérsékelt aszimmetria esetén jó (a harmadoláson alapul), ekkor -1 és 1 közötti érték
(Q3 − Me) − (Me − Q1 )
■ Kvantilisen (pl. kvartilis) alapuló (Bowley-féle ferdeségi): F0,25 =
(Q3 − Me) + (Me − Q1 )
□ decilisekből is képezhető (F0,1)
□ önmagában is értelmezhető, mert -1  F  1
3
 Yi − Y
M3 Y
N
=
■ α3 =
σ3
σ3
□ nincsenek alsó/felső határai  inkább csak összehasonlításra alkalmas
□ érzékenyen reagál az eloszlás alakjának kismértékű változásaira is
□ Excel: FERDESÉG.P függvény (2013+ verzió)
33

(

(

( )

Módusz

Balázsné Mócsai
Andrea
Eloszlások
jellege

Medián

Módusz

)

Terjedelem

Átlagok

Medián

)

Átlagok

Aszimmetria

Szórás

STATISZTIKA
I
Terjedelem

Szórás

Csúcsosság

Aszimmetria

Csúcsosság

---

loszlások jellege

– Miért nem szeretik a
statisztikusok a mopszot?

5.3.2. CSÚCSOSSÁG

■
■

■

– Mert lapos az arca, alig
van farka, és még csak
Csúcsosság: a görbe relatív emelkedése a módusz közelében nem is normális. ☺

□

alapvetően szimmetrikus eloszlás esetén értelmes

□

alapgondolat: csúcsos eloszlás esetén a szélső
kvartilisek aránya a szélső decilisekhez képest
kisebb, mint lapult eloszlás esetén

Q3 − Q1
Kvantiliseken alapuló (Kelly-féle csúcsossági) mutató: K =
2(D9 − D1 )
csúcsosabb
eloszlás
normális
eloszlás

Kiemelt értékek:

normális eloszlásnál K = 0,263
ugyanolyan szórású normálisnál
lapultabb
eloszlás
csúcsosabb eloszlás esetén K < 0,263,
lapultabb eloszlásnál K > 0,263
a középső értékek egy pontba tömörülnek (Q3 – Q1 = 0) → K = 0 (→ K > 0)
az adatok csak a két szélen vannak (Q3 – Q1 = D9 – D1) → K = 0,5 (→ K  0,5)
egyenletes eloszlás (Q3 – Q1 = 0,5·R; D9 – D1 = 0,8·R) → K = 0,3125

□
□

□
□
□
Módusz

Balázsné Mócsai
Andrea
Eloszlások
jellege

Medián

Módusz

Terjedelem

Átlagok

Medián

Átlagok

Aszimmetria

Szórás

STATISZTIKA
I
Terjedelem

Szórás

Csúcsosság

Aszimmetria

Csúcsosság

34

---

loszlások jellege

A csúcsosság általános mutatója
■

Csúcsossági mutató: α4 =
 pozitív

□ értéke:  nulla
negatív


( ) −3 =

M4 Y
σ

(Y − Y)

4

i

N
σ4

4

→ csúcsos
→ normális eloszlás
→ lapult

−3

nincsen alsó/felső határa  csak összehasonlításra jó
a csúcsosságbeli kis eltéréseket erősen felnagyítja
az Excel ennek egy korrigált értékét számolja, de összehasonlításra ez is
alkalmas (CSÚCSOSSÁG függvény)

□
□
□

Magyarország városainak népességszáma alakmutatói (2025):
Budapest nélkül: F0,25 = 0,35; P = 0,90; α3 = 4,61; K = 0,20; α4 = 26,3
Budapesttel:
F0,25 = 0,35; P = 0,38; α3 = 17,0; K = 0,20; α4 = 307

□
□
Módusz

Balázsné Mócsai
Andrea
Eloszlások
jellege

Medián

Módusz

Terjedelem

Átlagok

Medián

Átlagok

Aszimmetria

Szórás

STATISZTIKA
I
Terjedelem

Szórás

Csúcsosság

Aszimmetria

Csúcsosság

35

---

loszlások jellege

TESZT: A04 – Szóródási- és alakmutatók
10. kérdés
Egy statisztikai felvétel során az egyik társadalmi réteg egy főre jutó nettó jövedelmére 60000
Ft-ot kaptak. Az egy főre jutó nettó jövedelem módusza 52000 Ft, a medián 58000 Ft. Melyik
megállapítás helyes a jövedelem eloszlására?
a. A jövedelemeloszlás jobbra ferde.
b. A jövedelemeloszlás balra elnyúló.
c. A jövedelemeloszlás jobbra elnyúló.
d. A jövedelem eloszlása szimmetrikus.
□

átlag = 60000

□

medián = 58000

□

módusz = 52000

□

Pearson-féle mutató:
3  (60000 − 58000)
P=
0
σ
36
Módusz

Balázsné Mócsai
Andrea
Eloszlások
jellege

Medián

Módusz

Terjedelem

Átlagok

Medián

Átlagok

Aszimmetria

Szórás

STATISZTIKA
I
Terjedelem

Szórás

Csúcsosság

Aszimmetria

Csúcsosság

---

loszlások jellege

TESZT: Mennyiségi sorok, mutatók
12. kérdés
Egy mennyiségi ismérvnél az alsó kvartilis kétszer olyan messze van a mediántól, mint a felső
kvartilis. Mit mondhatunk ez alapján?
a. Az aszimmetria F mutatója -0,33.
b. Az eloszlás a normális eloszlásnál csúcsosabb.
c. Az eloszlás jobbra elnyúló.
d. Az aszimmetria F mutatója 0.

2x

(Q3 − Me) − (Me − Q1) x − 2x
1
□ F0,25 =
=
=−
(Q3 − Me) + (Me − Q1) x + 2x
3

x

37
Módusz

Balázsné Mócsai
Andrea
Eloszlások
jellege

Medián

Módusz

Terjedelem

Átlagok

Medián

Átlagok

Aszimmetria

Szórás

STATISZTIKA
I
Terjedelem

Szórás

Csúcsosság

Aszimmetria

Csúcsosság

---

loszlások jellege

TESZT: Mennyiségi sorok, mutatók
14. kérdés
Valamely eloszlás alakját vizsgálva a következő mutatókat kaptuk:
α3 = 1,256 ; α4 = 0,872
A fenti eloszlás a nulla várható értékű, egy szórású normális eloszlásnál...
a. lapultabb, balra elnyúló eloszlás.
b. csúcsosabb, balra elnyúló eloszlás.
c. lapultabb, jobbra elnyúló eloszlás.
d. csúcsosabb, jobbra elnyúló eloszlás.
□

α3 > 0 → jobbra elnyúló

□

α4 > 0 → csúcsosabb

38
Módusz

Balázsné Mócsai
Andrea
Eloszlások
jellege

Medián

Módusz

Terjedelem

Átlagok

Medián

Átlagok

Aszimmetria

Szórás

STATISZTIKA
I
Terjedelem

Szórás

Csúcsosság

Aszimmetria

Csúcsosság

---

loszlások jellege

Az eloszlás ábrázolása dobozábrán
■

Helyzet
□
□
□

■

medián
alsó kvartilis, felső kvartilis
az Excel dobozábráján az átlag is

50 000

Szóródás
□
□
□

■

60 000

40 000

terjedelem
interkvartilis terjedelem
alsó- és felső kerítés

30 000

Alak

20 000

doboz helyzete
□ medián és átlag helyzete
10 000
□ (kerítéseken kívüli) kilógó értékek
□ doboz szélessége a tartományon belül (csúcsosság)
0
például a magyar városok területének doboz ábrája
□

Módusz

Balázsné Mócsai
Andrea
Eloszlások
jellege

Medián

Módusz

Terjedelem

Átlagok

Medián

Átlagok

Aszimmetria

Szórás

STATISZTIKA
I
Terjedelem

Szórás

39
Csúcsosság

Aszimmetria

Csúcsosság
