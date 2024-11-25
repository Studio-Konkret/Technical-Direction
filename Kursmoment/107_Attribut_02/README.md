
Vi fortsätter med attribut och lär oss om [datatypen](https://github.com/Studio-Konkret/Technical-Direction/wiki/Attribut#datatyper)  [vektorer](https://github.com/Studio-Konkret/Technical-Direction/wiki/Datatyper#vector---vektor)

Vi kommer primärt att arbeta med vektorer för att styra orienteringen för instanser. 

## Uppgifter


### Miniuppgift

<img src="https://github.com/user-attachments/assets/fe9404cb-05e5-45fb-99fd-5cdde3372cda4" align="right" width="250">

#### A

-Animera en sfär och skapa ett attribut på den. 

- För över attributet med en attribute transfer till en grid.

- Blura och justera attributet.

- Använd attributet för att extruda eller displace geometrin.

  
&nbsp;

&nbsp;

___

<img src="https://github.com/user-attachments/assets/1749496c-73e8-4184-8913-869294a383c2" align="right" width="250">

#### B (svår)

Gör en meshad point-light skugga med [Ray SOP](https://www.sidefx.com/docs/houdini/nodes/sop/ray.html).

Generera ett vektor-attribut som beskriver riktningen från varje punkt, till en given position i worldspace (representerar point lightens position). Använd denna rikting för att raya geometrin på en grid.

> Hint: `ljusets position - P = riktningen till ljuset från geometrin`
>
> Använd Attribute Adjust Vector för att räkna ut formeln.

___

<img src="https://github.com/user-attachments/assets/8f465e4d-6313-4040-b30e-1db531551bd6" align="right" width="250">

### Hemuppgift

Hängande kablar.

Använd Ray SOP för att skapa linjer från en vägg till en annan. Generera ett vektor attribut med varierande rikting för att göra linjerna mer intressanta vid rayen.

> Tips:
> Generera först en vektor riktad rakt mot den andra väggen. Sedan använd Attribute Randomize och addera till den existerande vektorn. "Global Scale" styr mängden randomisering.

&nbsp;

## Underlag:
- [**Wiki - Attribut**](https://github.com/Studio-Konkret/Technical-Direction/wiki/Attribut)
- [**Wiki - Datatyper**](https://github.com/Studio-Konkret/Technical-Direction/wiki/Datatyper)
- [**SideFX - Attributes**](https://www.sidefx.com/docs/houdini/model/attributes.html#attributes)
