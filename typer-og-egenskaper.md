# Typer og egenskaper
Typer og egenskaper utgjør den normative delen av NS4180. Typer og egenskaper er i all hovedsak hentet fra [Schema.org](https://schema.org/). Utdanningsspesifikke og tilgjengelighetsspesifikke egenskaper er spesifisert under typen CreativeWork. Det er fullt mulig å berike metadata ytterligere ved å hente flere egenskaper fra Schema.org og andre vokabularer.

*Utdanningsspesifikke og tilgjengelighetsspesifikke typer og egenskaper er utviklet av henholdsvis Learning Resource Metadata Initiative ([LRMI](http://dublincore.org/specifications/lrmi/)) og Accessibility Metadata Project ([a11ymetadata](http://www.a11ymetadata.org/)).* 

## Innholdsfortegnelse
1.	[Generelle egenskaper](#generelle-egenskaper)  
	* 	1.1. [Person](#person) 
	* 	1.2. [Organization](#organization)
2. [Utdanningsspesifikke egenskaper](#utdanningsspesifikke-egenskaper)
	*	2.1. [Alignment Object](#alignment-object)
	* 	2.2. [Educational Audience](#educational-audience)
3.	[Tilgjengelighetsspesifikke egenskaper](#tilgjengelighetsspesifikke-egenskaper)
4. [Datatyper](#datatyper)

<a name="generelle-egenskaper"></a>
### 1. Generelle egenskaper
Egenskaper i tabellen er hentet fra typen [schema.org/CreativeWork](https://schema.org/CreativeWork). 

**Egenskap**|**Forventet type**|**Beskrivelse**|**Status**|
------------|------------------|---------------|----------|
identifier|Text eller URL eller PropertyValue|Representerer en hver form for identifikator (*eks. URI, URL, DOI, ISBN*)|påkrevd
name|Text|Tittelen på ressursen|anbefalt
description|Text|En beskrivelse av ressursen|anbefalt
about|Thing|Innholdets emne|anbefalt
dateCreated|Date eller DateTime|Dato for opprettelse av ressursen (*Datoformat som spesifisert i ISO 8601 benyttes*)|anbefalt
dateModified|Date eller DateTime|Dato for endring av ressursen (*Datoformat som spesifisert i NS-ISO 8601 benyttes*)|valgfritt
datePublished|Date|Dato for første publisering eller kringkasting av ressursen (*Datoformat som spesifisert i NS-ISO 8601 benyttes*)|valgfritt
expires|Date|Dato for når ressursen utløper og ikke lenger er nyttig eller tilgjengelig (*Datoformat som spesifisert i NS-ISO 8601 benyttes*)|valgfritt
publisher|Organization eller Person|Organisasjon eller person som har ansvar for utgivelsen av ressursen (*Se tabell [1.1](#person) og [1.2](#organization)*)|anbefalt
author|Person eller Organization|Person eller organisasjon som har ansvar for utarbeidelsen av ressursen (*Se tabell [1.1](#person) og [1.2](#organization)*)|valgfritt
inLanguage|Text eller Language|Ressursens primærspråk (*Kodeformat som spesfisert i NS-ISO 639 (del 1 eller del 2) benyttes*)|anbefalt
license|CreativeWork eller URL|Et lisensdokument som gjelder innholdet, som regel angitt som URL|anbefalt
thumbnailUrl|URL|Et miniatyrbilde relevant for ressursen|anbefalt
url|URL|URL for ressursen eller en landingsside for ressursen|valgfritt
hasPart|CreativeWork|Ressursen består av mer detaljerte ressurser|valgfritt
isPartOf|CreativeWork|Ressursen er en del av en mer generell ressurs|valgfritt
isBasedOn|URL|En ressurs som ble brukt i utviklingen av ressursen. Termen kan gjentas for flere ressurser|valgfritt

<a name="person"></a>
#### 1.1. Person
Egenskaper i tabellen er hentet fra typen [schema.org/Person](https://schema.org/Person).

**Egenskap**|**Forventet type**|**Beskrivelse**|**Status**|
------------|------------------|---------------|----------|
name|Text|Personens navn|valgfritt
givenName|Text|Personens fornavn|anbefalt
familyName|Text|Personens etternavn|anbefalt
affiliation|Organization|En organisasjon som personen er tilknyttet. For eksempel en skole, et universitet, en bedrift eller en annen sammenslutning (*Se tabell [1.2](#organization)*)|valgfritt

<a name="organization"></a>
#### 1.2. Organization
Egenskaper i tabellen er hentet fra typen [schema.org/Organization](https://schema.org/Organization).

**Egenskap**|**Forventet type**|**Beskrivelse**|**Status**|
------------|------------------|---------------|----------|
legalName|Text|Organisasjonens offisielle navn, registrert firmanavn|anbefalt
logo|URL eller ImageObject|En logo forbundet med organisasjonen|valgfritt
url|URL|URL til organisasjonen|valgfritt

<a name="utdanningsspesifikke-egenskaper"></a>
### 2. Utdanningsspesifikke egenskaper
Egenskaper i tabellen er hentet fra typen [schema.org/CreativeWork](https://schema.org/CreativeWork). 

**Egenskap**|**Forventet type**|**Beskrivelse**|**Status**|
------------|------------------|---------------|----------|
educationalAlignment|AlignmentObject|Tilknytning til et etablert rammeverk for utdanning (*se tabell [2.1](#alignment-object)*)|anbefalt
educationalUse|Text|Formålet med verket i forbindelse med utdanning (*Se [vokabular](./vokabularer.md#educational-use) for tilordning av verdier*)|valgfritt
timeRequired|Duration|Omtrentlig eller typisk tid det tar å arbeide med eller gjennomgå denne læringsressursen for typisk tiltenkt målgruppe (*Varighetsformat som spesifisert i NS-ISO 8601 benyttes*)|valgfritt
typicalAgeRange|Text|Typisk aldersgruppe for innholdets tiltenkte sluttbruker (*Eks.: «7-9», «18-»*)|valgfritt
interactivityType|Text|Vanligste læringsmodus som er støttet av læringsressursen (*Se [vokabular](./vokabularer.md#interactivity-type) for tilordning av verdier*)|valgfritt
learningResourceType|Text|Vanligste typeangivelse som karakteriserer læringsressursen(*Se [vokabular](./vokabularer.md#learning-resource-type) for tilordning av verdier*)|anbefalt
audience|EducationalAudience|En tiltenkt målgruppe, dvs. en gruppe for hvem ressursen ble opprettet (*se tabell [2.2](#educational-audience)*)|anbefalt

<a name="alignment-object"></a>
#### 2.1. Alignment Object
Egenskaper i tabellen er hentet fra typen [schema.org/AlignmentObject](https://schema.org/AlignmentObject).

**Egenskap**|**Forventet type**|**Beskrivelse**|**Status**|
------------|------------------|---------------|----------|
alignmentType|Text|Kategori for tilknytning mellom læringsressursen og rammeverknoden (*Se [vokabular](./vokabularer.md#alignment-type) for tilordning av verdi*)|anbefalt
educationalFramework|Text|Rammeverket som den beskrevne ressursen er tilknyttet|anbefalt
targetDescription|Text|Beskrivelse av en node i et etablert utdanningsrammeverk|anbefalt
targetName|Text|Navn på en node i et etablert utdanningsrammeverk|anbefalt
targetUrl|URL|URL for en node i et etablert utdanningsrammeverk|anbefalt

<a name="educational-audience"></a>
#### 2.2. Educational Audience 
Egenskaper i tabellen er hentet fra typen [schema.org/EducationalAudience](https://schema.org/EducationalAudience).

**Egenskap**|**Forventet type**|**Beskrivelse**|**Status**|
------------|------------------|---------------|----------|
educationalRole|Text|Rolle som beskriver målgruppen for innholdet (*Se [vokabular](./vokabularer.md#educational-role) for tilordning av verdier*)|valgfritt

<a name="tilgjengelighetsspesifikke-egenskaper"></a>
### 3. Tilgjengelighetsspesifikke egenskaper
Egenskaper i tabellen er hentet fra typen [schema.org/CreativeWork](https://schema.org/CreativeWork). 

**Egenskap**|**Forventet type**|**Beskrivelse**|**Status**|
------------|------------------|---------------|----------|
accessibilityAPI|Text|Angir at ressursen er kompatibel med referert tilgangs-API (*Se [vokabular](./vokabularer.md#accessibility-api) for tilordning av verdier*)|valgfritt
accessibilityControl|Text|Identifiserer inndatametoder som er tilstrekkelige for full kontroll med beskrevet ressurs (*Se [vokabular](./vokabularer.md#accessibility-control) for tilordning av verdier*)|valgfritt
accessibilityFeature|Text|Innholdsegenskaper ved ressursen, for eksempel tilgjengelige medier, alternativer og støttede tillegg for tilgjengelighet (*Se [vokabular](./vokabularer.md#accessibility-feature) for tilordning av verdier*)|valgfritt
accessibilityHazard|Text|Egenskap ved beskrevet ressurs at den er fysiologisk skadelig for enkelte brukere (*Se [vokabular](./vokabularer.md#accessibility-hazard) for tilordning av verdier*)|valgfritt
accessMode|Text|Det menneskelige sensoriske perseptuelle systemet eller kognitiv fakultet gjennom hvilken en person kan behandle eller oppleve informasjon (*Se [vokabular](./vokabularer.md#access-mode) for tilordning av verdier*)|valgfritt
accessModeSufficient|Text|En liste over enkelte eller kombinerte tilgangsmoduser som er tilstrekkelige for å forstå alt intellektuelt innhold i en ressurs (*Se [vokabular](./vokabularer.md#access-mode-sufficient) for tilordning av verdier*)|valgfritt
accessibilitySummary|Text|En menneskelig lesbar oppsummering av spesifikke tilgjengelighetsfunksjoner eller mangler, som er i samsvar med de andre tilgjengelighetsmetadataene, men som uttrykker spissfindigheter som "korte beskrivelser er tilstede, men lange beskrivelser vil være nødvendige for ikke-visuelle brukere" eller "korte beskrivelser er til stede og ingen lange beskrivelser trengs"|valgfritt

<a name="datatyper"></a>
### 4. Datatyper
Datayper som spesifisert i *forventet type* i tabellene er hentet fra [schema.org/DataType](https://schema.org/DataType). 