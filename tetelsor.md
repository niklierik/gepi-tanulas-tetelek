01

- Gépi tanulás fogalma, tanulóalgoritmus, tanulási feladatok típusai (felügyelt, felügyelet nélküli, időbeli folyamatok, megerősítéses tanulás), példák

- Osztályozás lépései (előfeldolgozás, jellemzőkinyerés, osztályozás), gépi tanulás életciklusa

- Függvények felügyelt tanulása (a tanulóalgoritmus inputja, outputja, a tanulandó függvény bemenetének és kimenetének típusai, reprezentációk és konverziók), példák

- A jellemzőtér és a döntési felület, geometriai és döntéselméleti szemlélet, a tanulandó függvény reprezentálása

- A hipotézistér szerepe a gépi tanulásban, konzisztens hipotézis fogalma, Occam borotvája

02

- A gépi tanulás alapfogalmai (jellemzőkinyerés, curse of dimensionality), redundáns és irreleváns jellemzők, jellemző-kiválasztás és jellemzőtér-transzformációk

- A tanult modell kiértékelése

- No free lunch, általánosítás és túltanulás, bias és variancia, a komplexitás gyakorlati beállítása

03

- A Bayes döntési szabály, diszkriminánsfüggvények és döntési felületek

- Bayes-döntés diszkrét és folytonos jellemzők mellett (leszámlálás), Gauss-eloszlások néhány speciális esetében a döntési felület alakja

- A statisztikai alakfelismerési módszer hibalehetőségei (Bayes hiba, modellezési hiba, paraméterbecslési hiba), a hibák kezelése

- A Naiv Bayes osztályozó (motiváció, megoldás, előnyök és hátrányok)

04

- Gauss-görbe illesztése Maximum Likelihood módszerrel (áttekintés), egydimenziós eset

- Gauss-görbe illesztése Maximum Likelihood módszerrel sokdimenziós esetben, gyakorlati megoldások (nem invertálható eset, diagonális kovariancia-mátrix)

- Bayes paraméterbecslés általános megközelítésben

- Gauss-görbe illesztése Bayes paraméterbecsléssel

05

- Gaussi keverékmodell (motiváció, előfeldolgozás)

- K-means klaszterezés, soft clustering és használata a GMM tanítása során

- Az EM algoritmus Gaussi keverékmodell tanítására

- Finite Mixture model, az EM algoritmus tulajdonságai, technikai megjegyzések

06

- Logikai formulák tanulása, redukálásuk, döntési fa reprezentáció, ID3 algoritmus

- Attribútum választása döntési fa építése során, Shannon-entrópia, információnyereség

- Döntési fák vágása (motiváció, megvalósítás, típusai)

- ID3 kiterjesztései (több osztály, valószínűségi becslés, folytonos attribútumok, hiányzó jellemzők)

- Döntési fák építése Gini index használatával, regressziós fák, többváltozós döntési fák

07

- Lineáris módszerek (motiváció, jelölés), kétosztályos eset, normalizálási lépés, a perceptron algoritmus (+batch)

- Lineáris osztályozó tanítása gradient descent eljárással, SGD

- Lineáris osztályozó tanítása MSE hibafüggvény minimalizálásával (analitikus + SGD eset)

- Logisztikus regresszió, lineáris gép

08

- SVM motivációja, alapfogalmak (szupport-vektorok, margó), jelölés, lineárisan elválasztható eset

- SVM: lineárisan nem elválasztható eset

- Nemlineáris SVM, osztályozás a kernel-térben (ötlet, hogyan módosul a tanítás és a kiértékelés)

09

- A perceptron modell, aktivációs függvény, MLP standard architektúra (multi-layer feed-forward fully-connected), kapcsolat a statisztikai alakfelismeréssel

- "Sekély" neuráls háló tanítása (Gradient descent, backpropagation)

- A backpropagation eljárás változatai (sztochasztikus: online és batch, GPU használata), standard technikák (véletlen súlyinicializálás, tanítóadatok megkeverése, adatok normalizálása, learning rate beállítása)

10

- Hagyományos és mély neurális hálók, a mély hálók tanításának problémái (eltűnő gradiens), megoldások (új aktivációs függvények, DBN előtanítás, rétegről-rétegre felépítés)

- Konvolúciós neurális hálók (motiváció, megvalósítás), konvolúció és pooling (kiértékelés és tanítás)

- Időbeli sorozatok modellezése egyszerűbb neurális hálókkal (szomszédos inputok figyelembe vétele, TDNN, RNN)

- Időbeli sorozatok modellezése Long-Short Term Memory neuronokkal

11

- Együttes tanulás alapötlete, gyenge osztályozók fogalma, különbözőségeik módjai (döntési fákkal is), kimenet-aggregálási módszerek

- Bagging, Random Forest

- Boosting

12

- Lineáris transzformációs adat-előfeldolgozás, PCA és LDA áttekintése

- Főkomponens-analízis (PCA)

- Lineáris diszkriminánselemzés (LDA)

13

- Autoenkóder neurális hálók (koncepció, autoenkóder hálók használata felügyelt tanításra), autoenkóderek típusai

- Önfelügyelt tanítás (koncepció, példák automatikusan generált címkékre, előtanítás és finomhangolás)
