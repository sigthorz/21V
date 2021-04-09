# Töflur og form

## Verkefni 4.1 - Töflur  

[Meðfylgjandi upplýsingar](https://github.com/vefhonnun/21V/tree/main/S%C3%BDnid%C3%A6mi/V-4) á að setja í HTML töflu og þær eiga að vera skilmerkilega settar upp. Í stílsíðu er hægt að nota gerviklasa (Pseudo class - nth-child) til að fá litskiptingu í bakgrunn töflunnar. 

Taflan á að birtast í öllum skjástærðum án þess að riðla skipulagi síðunnar. Það á ekki að þurfa að hliðra til skjánum. Myndirnar hér að neðan eru af töflu í vefsíðu. Í stílsíðunni eru eitt viðmið (_breakpoints_) 48em.

Mynd 1. Viðmið 48em + (760px ~ og stærri skjáir)

![Mynd 1](mynd-1.jpg)

Mynd 2. Viðmið 0 – 48 em (0 – 760px)

![Mynd 2](mynd-2.jpg)

## Verkefni 4.2 - Form 

Setjið skráningarform inn á vefsíðu, formið á að vera sýnilegt í öllum helstu skjástærðum. 

Mynd 3. Form með helstu innsláttarreitum sem notaðir eru í HTML

![Mynd 3](mynd-3.jpg)

#### FORM VALIDATION – HTML5

Þegar smellt er á hnappinn (input submit) í skráningarforminu þá á vafrinn að athuga (validate) hvort einver texti hafi verið settur í alla innsláttarreitina. Ef reitirnir uppfylla ekki þau skilyrði þá á ekki að vera hægt að senda upplýsingar frá vefsíðunni, ef allt er í lagi þá sendum við innsláttinn út í bláinn. 
```
  <input type=“x“ name=“x“ value=“X“ required placeholder=“fyllið út þennan reit“>
```
Eftirfarnandi skilyrði (_required_) þarf að uppfylla áður form er sent af stað með pósti frá vefsíðu

* Ekki er hægt að skilja nafnareit auðan 		
* Símanúmer verður að vera tölur (numbers)
* Tölvupóstfang verður að vera með @	      	
* Notið „input date“
* Notið „select option, checkbox og radio“. 	
* Notið aðra leturgerð og stærð í „textarea“

### Námsmat tafla 6%

* 3% Notaðu thead, tbody og tfooter tögin í töflukóðanum. 
* 3% Taflan er svegjanleg (_responsive_) og skiptist þannig að hún er öll sýnileg
á litlum skjáum.

### Námsmat form 8%

* 4% &lt;input -text, -email, -radio, -checkbox, date, select> og &lt;textarea> er í forminu 
* 4% Ekki á að vera hægt að senda (submit) form fyrr en ákveðin skilyrði (required)  eru uppfyllt.

[Fylgigögn](https://github.com/vefhonnun/21V/tree/main/S%C3%BDnid%C3%A6mi/V-4)

### Verkefnaskil

Öllum vinnugögnum á að skila í áfangageymsluna þína.

Einkunn verður birt í Innu.

_Gangi þér vel_

