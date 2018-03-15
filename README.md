# VEFÞ2 Lokaverkefni Vor 2018
### Hópverkefni, hópastærð: 2 nemendur.

[Skráning hópa hér í viðfangsefni -_New Issue_ ](https://github.com/vefhonnun/VEF2-Lokaverkefni-H17/issues/) 
## Verklýsing
Útgáfufyrirtækið **Z** sem er nýstofnað ætlar að hasla sér völl í tónlistabransanum og stefnir á að halda útgáfutónleika til að kynna starfsemi sína. Fyrirtækið er búið að gera samstarfssamninga við efnilega tónlistarmenn og stefnir á að koma þeim á vinsældalista landsins og síðar að halda út í djúpu laugina og sigra heiminn...

Fyritækið er ekki enn búið að marka sér nein einkenni og heiti útgáfufyritækisins **Z** er enn á vinnslustigi. Ykkar hlutverk er að skipuleggja og hanna eftrifarandi þætti:
* Firmamerki - með nýju heiti
* Útgáfufyrirtækið sérhæfir sig í útgáfu á (_tónlistarstefnu sem þið ákveðið_)
* Vef fyrir útgáfutónleikana
  * Á vefnum á að vera hægt að sjá dagskrá
  * Hverjir koma fram
  * Skráning á útgáfutónleikana
  * Upplýsingar um flytjendur
    * Hver flytjandi er með lagalista 
    * video eða .mp3 skrá með 1 lagi sem hægt að spila með hverjum flytjanda
  * Tímasetning útgáfutónleikana þarf að koma skýrt fram og gerum ráð fyrir að viðburðurinn sé haldin á sumarmánuðum.
  * Viðburðurinn má vera hvar sem er á íslandi, setjið staðsetningarkort á vefsíðuna
  * Upplýsingar um fyrirtækið
    * Hverjir eru Z
    * Hvað gerir Z
    * Hvar er Z
  * **Efnisval er að öðru leyti frjálst**, reynið að forðast _“dummy”_ texta (Lorem Ipsum ETC …). 
 
 #### Vefurinn á að endurspegla þá verkkunnáttu sem þið hafið öðlast í áfanganum ásamt fyrri áfanga, VEFÞ1.  

> **Nemendur eiga að nota Git samþáttun í hvert skipti sem unnið er í hópverkefninu.**<br>
> Afurð er metin útfrá vinnuframlagi í Git og verkstjórnun í GitHub.

> **Ég mæli með því að nota GitHub "Project" bæði í hugmynda- og skipulagsvinnuna.** <br>
> **Wiki** er tilvalið til að halda dagbók og skrá inn framvindu verkefnisins ásamt heimildaskrá.

### Útgáfustýring:  Verkstjórn og greinargerð um vinnuferlið.

* Gerið grein fyrir eftirtöldum atriðum í _README.md_ 
  * Um hvað er vefurinn?   
  * Hver er markhópurinn og markmið með gerð vefsins
  * Setjið tengla sem vísa á hópsíðu og afurð
* Efnisöflun og hugmyndavinna í [_"Project"_](https://github.com/vefhonnun/VEF2-Lokaverkefni-H17/projects/1)
  * Skráið allar hugmyndir  
  * Skoðið hvað aðrir hafa gert, safnið saman fyrirmyndum ss tenglum á áhugaverðar vefsíður
  * Það má nota texta og myndir af öðrum vefsíðum 
  * Gerið grein fyrir hvaðan efnið er tilkomið í heimildaskrá. Notið _WIKI_ skrá til þess
* Skipulagsvinna í [_"Project"_](https://github.com/vefhonnun/VEF2-Lokaverkefni-H17/projects/1)
  * Skráið **hvað** á að gera í verkefnaáætlun. Gerið tímaáætlun og skráið **hver** á að framkvæma tiltekna verkþætti.
* Dagbók, notið [_Wiki_](https://github.com/vefhonnun/VEF2-Lokaverkefni-H17/wiki) 
  * Kynning á hóp
  * Skráið vinnuferlið, hvernig það gengur frá byrjun til enda
  * Viðhald, í lok verkefnisins á að útskýra hvað má gera betur og hver geta verið næstu skref með vefinn (ókláruð virkni, endurbætur o.s.frv.)

### Afurð:  Tæknilegar lausnir
* [Setjið vefsíðu á GitHub geymsluna](/leiðbeiningar/vefsida_Github.pdf)
* [Sjá vefdæmi](https://vefhonnun.github.io/VEF2-Lokaverkefni-H17/)
* Veljið merki fyrir hópinn ( _SVG_ mynd)
* Viðmið (_breakpoints_) fyrir mismunandi skjástærðir, _„mobile up“_ -> 30em, 37.5em, 48em, 60em, 80em
* Myndir í vefsíðum aðlagast mismunandi skjástærðum (notið &lt;picture&gt; tagið)
* Letur og litanotkun er í samræmi við efni/þema vefsins
* SCSS stílsíður –> ein CSS stílsíða tengd vefsíðu (_compressed_)
* Kvikun (_animation, transitions, transform_)
* Almenn lýsing á viðburði og sundurliðuð dagskrá í töflu
* Notandi getur skráð sig á útgáfutónleikana (_form_)
  * **Athugið að það er ekki farið fram á samskipti vefsíðu og miðlara,** einungis er verið að setja upp formið og stíla það
* Upplýsingar sem skráðar eru í form eru villuprófaðar (_HTML5 validation - required_)
* Prófanir
  *  Er kóðinn í lagi? Er vefurinn villulaus?  [W3 Markup validation](https://validator.w3.org/)
### Námsmat 

* **8% Útgáfustýring - Undirbúningsvinna**
  *  Greinargerð (í _Readme.md_)
  *  Verkáætlun (_Project - milestones_)
  *  Efnisöflun og skipulag (_Project_)  
  *  Dagbók (_Wiki_)
  *  Heimildaskrá (_Wiki_)

*  **2% Kynning á hóp (vefsíða á GitHub - _docs_)**

* **10%   Afurð - Tæknilegar lausnir**
  * Útlit (_layout_) vel útfært með viðmiðum (_breakpoints_) 
  * Myndir í samræmi við skjástærð (_&lt;picture&gt;_)
  * SVG mynd sem firmamerki (_logo_)
  * Samræmi í letur og litanotkun 
  * Kvikun (_animation, transitions, transform_) 
  * Samskiptaform með _HTML5 validation_
  * SCSS/CSS stílsíður

## Verkefnaskil
  * **Öllum vinnugögnum  er skilað í GitHub geymslu (_repository_)**
    1. Greinargerð um verkefnið
    2. Hugmyndavinnu (skissur ofl). Skipulag (_layout_)
    3. Vefurinn með öllum kóða ss. SCSS/CSS, js og php kóða
    4. Textavinnsla og myndir
    5. Dagbók og Heimildaskrá 
    6. Kynning á hóp í Github vefsíðu
    7. Afurð/vef er skilað á http://tsuts.tskoli.is/2t/þín-KT/lokaverkefni

> Tenglum (link) á vef og geymslu er skilað í INNU. Nemendur skila verkefninu hver fyrir sig vegna þess að einkunn er metin útfrá vinnuframlagi í Git og verkstjórnun í GitHub. <br>
> **Athugið að hópverkefnið er lykilmatsþáttur.**

* _Gangi ykkur vel_

