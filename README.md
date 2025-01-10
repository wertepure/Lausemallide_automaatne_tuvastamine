# Lausemallide automaatne tuvastamine
Siin repositooriumis asub materjal, mida kasutati Kertu Sauli magistritöös "Eesti keele lausemallide automaatne tuvastamine liigutamisverbide näitel" ning Kertu Sauli, Kadri Muischneki ja Jelena Kallase artiklis "„Keeleteadlane raputab lausemalle korpusest loendisse“ – lausemallide automaatse tuvastamise esimesed sammud". 

## Failid

**alusandmed**: Tasakaalus korpusest saadud alusmaterjal
* *tasakaalus_korpus_laused_verbiti*: laused Tasakaalus korpusest verbi kaupa. Iga 28 liigutamisverbi laused on eri failides.
* *koik_laused.conll*: 28 liigutamisverbi Tasakaalus korpuse laused ühes failis. Lause verb pidi läbima morfoloogiliste ja süntaktiliste piirangute filtri.
* *verbi_sagedus_graafik.png*: graafik 28 liigutamisverbi esinemissagedusest Tasakaalus korpuses
* *verbide_esinemissagedus.csv*: tabel 28 liigutamisverbi esinemissagedusest Tasakaalus korpuses

**NB!** Lausemallide koostamiseks kasutati EKI vanemtarkvaraarendaja Katrin Tsepelina koostatud andmebaasi. Andmebaas koostati Tasakaalus korpuse andmete põhjal. Suuruse tõttu ei asu need failid siin repositooriumis, vaid Google Drive'is, millele saab ligi [siit lingilt](https://drive.google.com/drive/folders/1Sj5P_C601AaAYkQuq00L6NHEB_epvdfB?usp=sharing).
Andmebaasifail on nimega 'tasak_obl_verb_subj_obj_nocase_24_03.db'.
Andmebaasi koostamise toorandmetena kasutatud korpusefail on nimega 'tasak.conll'.
Andmebaasi loomiseks kasutatud kood asub [siin](https://github.com/rabauti/prg1978/tree/main).

**kood**: uurimuses kasutatud koodifailid
* *Lausemallide automaatne tuvastamine.ipynb*: Kood lausemallide tuvastamiseks. Kasutab andmeid andmebaasist ['tasak_obl_verb_subj_obj_nocase_24_03.db'](https://drive.google.com/drive/folders/1Sj5P_C601AaAYkQuq00L6NHEB_epvdfB?usp=sharing).
* *Näitelausete otsimine.ipynb*: Otsib lausemalli põhjal conllu failidest näitelauseid
* *korpuselaused_verbiti_filtreeritud*: Kasutaja sisestab verbi. Kood otsib conllu failist selle verbiga lauseid. Välja filtreeritakse laused, kus verb ei vasta uuringus määratud morfoloogilistele ja süntaktilistele piirangutele.

**testmaterjal**: lausemallide käsitsi koostamisega seotud materjal
* *testmaterjali laused verbiti*: 28 liigutamisverbi laused [UD eesti EDT korpusest](https://universaldependencies.org/treebanks/et_edt/index.html). Nende põhjal koostati käsitsi mallid.
* *testandmestik_käsitsi_mallid.xlsx*: käsitsi koostatud lausemallid. Mallid on kahel kuju: semantiliselt ja grammatiliselt.
* *testmaterjali_lausete_märgendamine.pdf*: tööfail, kus 28 liigutamisverbi jaoks on vaadatud lausenäiteid. Iga verbi jaoks on pandud kirja: argumendid, adjunktid, nende grammatilised märgendid, nende kasutusnäide.

**tulemused**: automaatselt tuvastatud lausemallid ja nende kvaliteet
* *automaatse_tuvastamise_kvaliteet.xlsx*: automaatselt tuvastatud seotud laiendite ja lausemallide kvaliteedi analüüs. Koosneb nii arvulisest infost kui ka vale tuvastuse põhjustest. 
* *liigutamisverbide_mallid_sorteeritud.xlsx*: kõik automaatselt tuvastatud lausemallid. 

**NB!** Tulemuste põhjaliku analüüsiga saab tutvuda magistritöös ["Eesti keele lausemallide automaatne tuvastamine liigutamisverbide näitel"](https://dspace.ut.ee/items/3d8811f8-a0d8-400c-a37d-c2e31ef5c951).
