# Utdanningsrammeverk
Tilknytning til utdanningsrammeverk er en sentral del av NS4180. I den grad det er hensiktsmessig bør det angis tilknytninger til relevante rammeverk som tilbys fra sentrale kilder innen utdanningssektoren. Dette gjøres fortrinnsvis ved bruk av egenskapen [educationalAlignment](./typer-og-egenskaper#utdanningsspesifikke-egenskaper) og typen [AlignmentObject](./typer-og-egenskaper#alignment-object) i NS4180. 

## Innholdsfortegnelse
1.	[Grep](#grep)  
2.	[Fagkart](#fagkart)
3.	[Eksempler](#eksempler)

<a name="grep"></a>
### 1. Grep
Grep er den nasjonale databasen for fag, læreplaner og opplæringstilbud i grunnopplæringen. Alle fastsatte læreplaner i Kunnskapsløftet legges inn i Grep. I tillegg finnes kodeverk og informasjon om fag i grunnskole og videregående opplæring (vgo), inkludert vurderingsordninger, samt fag- og vitnemålsmerknader til bruk i dokumentasjon av opplæringen.

Grep tilbyr i dag flere grensesnitt for deler av databasen - både som webservice/soap og REST. I dag kan data leveres som xml og json (json er default-formatet som vises på data.udir.no/kl06). Læreplaner leveres i tillegg også som html, odf, pdf, doc, docx og rtf.

Mer informasjon om Grep, finnes [her](http://data.udir.no/kl06/) og [her](http://grepwiki.udir.no/).

<a name="fagkart"></a>
### 2. Fagkart
Konseptet Fagkart ble utviklet av KS-prosjektet Aktivitetsdata for vurdering og tilpassing (AVT-prosjektet) og er tilgjengelig på nettstedet [fagkart.no](https://fagkart.no). Formålet med fagkartet er å etablere en felles referanse for detaljert metadatamerking og strukturering av aktivitetsdata. De minste områdene i fagkartet er svært detaljerte. Innhold kan enten merkes mot de mest detaljerte områdene i fagkartet, eller mot mer overordnede områder. Jo mer detaljert merkingen gjøres, jo mer presist vil merkingen kunne brukes i forhold til målene om å gi tilpasset opplæring og kvalitet i vurderings- og utviklingsarbeid. Alle områdene i fagkartet har en ID som det kan refereres til.
Inntil videre er det KS som eier og forvalter denne tjenesten.
Fagkartet er tilgjengelig både maskinlesbart via REST API og et grensesnitt for søk, oversikt og navigasjon i fagkartet. Hele fagkartet kan også lastes ned i en samlet fil.

<a name="eksempler"></a>
### 2. Eksempler
For eksempler på tilknytninger til utdanningsrammeverk ved bruk av NS4180, se [Eksempler](./eksempler).
