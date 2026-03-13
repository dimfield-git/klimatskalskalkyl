# Klimatskalskalkyl

Ett webbaserat verktyg för att analysera **energibesparing och ekonomi
vid åtgärder på byggnadens klimatskal** i flerbostadshus.

Verktyget gör det möjligt att beräkna effekter av åtgärder som:

-   fönsterbyte
-   tilläggsisolering av fasad
-   förbättring av vindsbjälklag
-   förbättrad lufttäthet

Resultatet presenteras som **energibesparing, ekonomisk besparing,
CO₂‑reduktion och återbetalningstid**.

Applikationen körs helt i webbläsaren och kräver **ingen installation
eller server**.

------------------------------------------------------------------------

## Öppna verktyget

När GitHub Pages är aktiverat finns verktyget här:

https://dimfield-git.github.io/klimatskalskalkyl/

Direktlänk till kalkylen:

https://dimfield-git.github.io/klimatskalskalkyl/klimatskalskalkyl_v1.html

------------------------------------------------------------------------

## Vad verktyget gör

Klimatskalskalkylen beräknar hur värmeförluster förändras när olika
delar av klimatskalet förbättras.

Beräkningen baseras på:

-   U‑värden före och efter åtgärd
-   area för respektive byggnadsdel
-   klimatdata (gradtimmar)
-   energipris
-   uppvärmningssystem (fjärrvärme, el eller värmepump)

Utifrån detta beräknas:

-   årlig energibesparing (kWh)
-   ekonomisk besparing (kr/år)
-   CO₂‑besparing
-   återbetalningstid
-   investeringskostnad

Resultaten visas både numeriskt och i diagram.

------------------------------------------------------------------------

## Beräkningslägen

### Fönsterbyte

Snabb analys av energibesparing vid byte från äldre fönster till moderna
energifönster.

Inmatning sker per **fönstergrupp**:

-   antal fönster
-   area per fönster
-   befintligt U‑värde
-   nytt U‑värde
-   investeringskostnad

Detta är användbart för:

-   analys inför större fönsterprojekt
-   tekniska energiutredningar
-   underlag inför styrelsebeslut

------------------------------------------------------------------------

### Hela klimatskalet

I detta läge analyseras hela klimatskalet:

-   fönster
-   fasad
-   vindsbjälklag
-   lufttäthet

Varje del kan aktiveras eller avaktiveras separat.

Det gör det möjligt att analysera:

-   enskilda åtgärder
-   kombinationer av åtgärder
-   total energibesparing i ett renoveringsprojekt

------------------------------------------------------------------------

## Klimatdata och verifiering

Verktyget använder:

-   gradtimmar
-   DVUT
-   innetemperatur

Det går även att ange ett **verifieringsvärde för värmeförbrukning** för
att jämföra modellens resultat med verklig energianvändning.

------------------------------------------------------------------------

## Ekonomiska parametrar

Följande parametrar kan justeras:

-   energipris
-   kalkylränta
-   energiprisets utveckling
-   systemverkningsgrad / COP
-   livslängd för åtgärder

Det gör verktyget användbart både för tekniska analyser och ekonomiska
beslutsunderlag.

------------------------------------------------------------------------

## Export och rapport

Resultaten kan exporteras för användning i:

-   styrelsematerial
-   tekniska rapporter
-   energistrategier
-   energideklarationer

Verktyget innehåller även ett **rapportläge** som presenterar resultaten
i ett format anpassat för dokumentation.

------------------------------------------------------------------------

## Typiska användningsområden

Verktyget är främst avsett för:

-   energikonsulter
-   fastighetsförvaltare
-   energiingenjörer
-   styrelser i bostadsrättsföreningar

Det lämpar sig särskilt för:

-   analys inför fasad‑ eller fönsterprojekt
-   energibesparingsutredningar
-   beslutsunderlag till styrelsemöten
-   jämförelse mellan olika renoveringsalternativ

------------------------------------------------------------------------

## Tekniskt

Applikationen är en **statisk HTML‑sida** som körs lokalt i webbläsaren.

Den använder:

-   Chart.js för diagram
-   JavaScript för beräkningar
-   inga externa databaser eller backend

All data stannar lokalt i användarens webbläsare.

------------------------------------------------------------------------

## Licens

GPL‑3.0
