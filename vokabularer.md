# Vokabularer
Flere egenskaper i NS4180 er tilknyttet etablerte internasjonale vokabularer. Det vil si at når egenskapene tilordnes verdier bør verdiene hentes fra disse vokabularene.

Vokabularene er ikke uttømmende, de definerer p.t. toppnivåbegreper som er ment å fungere i en internasjonal kontekst.

Nasjonale tilpasninger av vokabularene vil foregå her. Tilpasninger spenner fra norske oversettelser av eksisterende termer og definisjoner til spesifisering av nye termer og definisjoner. 

## Innholdsfortegnelse
1.	[Utdanningsspesifikke vokabularer](#utdanningsvokab)  
	* 	1.1. [Alignment Type](#alignment-type) 
	* 	1.2. [Educational Role](#educational-role)
	*  	1.3. [Educational Use](#educational-use)
	*  	1.4. [Interactivity Type](#interactivity-type)
	*  	1.5. [Learning Resource Type](#learning-resource-type)
2. [Tilgjengelighetsspesifikke vokabularer](#tilgjengelighetsvokab)
	*	2.1. [Accessibility Feature](#accessibility-feature)
	* 	2.2. [Accessibility Hazard](#accessibility-hazard)
	* 	2.3. [Accessibility API](#accessibility-api)
	*	2.4. [Accessibility Control](#accessibility-control)
	* 	2.5. [Access Mode](#access-mode)
	*  	2.6. [Access Mode Sufficient](#access-mode-sufficient)

<a name="utdanningsvokab"></a>
### 1. Utdanningsspesifikke vokabularer
Utdanningsspesifikke vokabularer er hentet fra Learning Resource Metadata Initiative ([LRMI](http://dublincore.org/specifications/lrmi/)). Utfyllende beskrivelser av vokabularene, finnes [her](http://dublincore.org/specifications/lrmi/concept_schemes/).

<a name="alignment-type"></a>
#### 1.1. Alignment Type ([alignmentType](./typer-og-egenskaper.md#alignment-object))
###### Beskrivelse
Definerer relasjonstyper mellom en læringsressurs og en node i et utdanningsrammeverk / <i>Defines the types of relationships between a learning resource and a node in an educational framework</i>.

###### Multiplisitet
1 (én)

**Kode**|**Term**|**Definisjon**|**Term (norsk)**|**Definisjon (norsk)**|
--------|--------|--------------|----------------|----------------------|
assesses|assesses|The learning resource being described may be used to assess the competency being referenced.|vurderer|Den beskrevne læringsressursen kan brukes til å vurdere referert kompetanse.
complexityLevel|complexity level|The point in the framework being referenced defines a level or range that measures the difficulty or challenge presented by the learning resource being described.|vanskelighetsgrad|Det refererte punktet i rammeverket angir et nivå eller område som mål for vanskelighets- eller utfordringsgrad for læringsressursen som beskrives.
educationalLevel|educational level|The point in the framework being referenced defines a level or stage within an education system for which the resource being described is intended or useful.|utdanningsnivå|Det refererte punktet i rammeverket angir et nivå eller stadium i utdanningssystemet der den beskrevne ressursen er tiltenkt eller anvendelig.
educationalSubject|educational subject|The point in the framework being referenced defines the subject context of the learning resource being described.|undervisningsfag|Det refererte punktet i rammeverket angir den faglige konteksten for den beskrevne læringsressursen.
prerequisite|prerequisite|The competency being referenced is a learning prerequisite to the effective outcome of the learning resource being described.|forutsetning|Den refererte kompetansen er en læringsmessig forutsetning for effektiv anvendelse av den beskrevne lærings¬ressursen.
readingLevel|reading level|The point in the framework being referenced defines a level or range of reading ability expected for a person using the learning resource being described.|lesenivå|Det refererte punktet i rammeverket angir et nivå eller område av evne til lesing som forventes av en person som skal benytte den beskrevne læringsressursen.
teaches|teaches|The learning resource being described may be used to teach the competency being referenced.|underviser|Den beskrevne læringsressursen kan benyttes til å undervise i den refererte kompetansen.

<a name="educational-role"></a>
#### 1.2. Educational Role ([educationalRole](./typer-og-egenskaper.md#educational-audience))
###### Beskrivelse
Definerer primære eller tilsiktede roller hos målgruppen (mottaker) til ressursen som beskrives / <i>Defines the primary or intended roles of the audience (beneficiary) of the resource being described</i>.

###### Multiplisitet
N (mange)

**Kode**|**Term**|**Definisjon**|**Term (norsk)**|**Definisjon (norsk)**|
--------|--------|--------------|----------------|----------------------|
administrator|administrator|A trainer or educator with administrative authority and responsibility.|administrator|En trener eller instruktør på regionalt eller skolenivå med administrativt ansvar.
generalPublic|general public|The public at large.|allmennheten|Allmennheten.
mentor|mentor|Someone who advises, trains, supports, and/or guides.|mentor|En som driver rådgivning, opplæring, støtte eller veiledning.
parent|parent|A father, mother, or legal guardian.|foresatt|En far, mor eller verge.
peerTutor|peer tutor|The peer learner serving as tutor of another learner.|fagfelle|En elev eller student som underviser medelev eller medstudent.
professional|professional|Someone already practicing a profession; an industry partner, or professional development trainer.|yrkesaktiv|En som allerede praktiserer et yrke; en industripartner eller videreutdanningsinstruktør.
student|student|The learner or trainee.|elev/student|Den lærende eller lærlingen.
teacher|teacher|A person who has been trained to implement educational methods and practices.|lærer|En person som er opplært til å implementere pedagogiske metoder og praksiser.

<a name="educational-use"></a>
#### 1.3. Educational Use ([educationalUse](./typer-og-egenskaper.md#utdanningsspesifikke-egenskaper))
###### Beskrivelse
Opplisting av pedagogisk bruksområder for en læringsressurs / <i>Enumerates the educational uses of a learning resource</i>.

###### Multiplisitet
N (mange)


**Kode**|**Term**|**Definisjon**|**Term (norsk)**|**Definisjon (norsk)**|
--------|--------|--------------|----------------|----------------------|
assessment|assessment|Primary purpose of the resource is to evaluate learning, before, during, or after instruction occurs.|vurdering|Hovedformålet med ressursen er å vurdere læring, før, under eller etter undervisningen.
instruction|instruction|Primary purpose of the resource is to support the instructional process, student learning, or to provide information about the curriculum.|undervisning|Hovedformålet med ressursen er å støtte undervisningsprosessen, elevens læring eller å gi informasjon om undervisningsplanen.
professionalSupport|professional support|Primary purpose of the resource is to provide instruction for a teacher or other education professional including professional development.|profesjonell støtte|Hovedformålet med ressursen er å gi instruksjon til en lærer eller en annen instruktør inkludert utvikling.

<a name="interactivity-type"></a>
#### 1.4. Interactivity Type ([interactivityType](./typer-og-egenskaper.md#utdanningsspesifikke-egenskaper))
###### Beskrivelse
Definerer den overordnede interaktive modusen til læringsressursen som beskrives / <i>Defines the predominate interact mode of the learning resource being described</i>.

###### Multiplisitet
N (mange)

**Kode**|**Term**|**Definisjon**|**Term (norsk)**|**Definisjon (norsk)**|
--------|--------|--------------|----------------|----------------------|
active|active|Learning that engages and challenges the learner's thinking using real-life and/or imaginary situations taking advantage of the opportunities for learning presented by investigating, exploring, events, and life experiences.|aktiv|
expositive|expositive|Use of a subject-matter expert to explain a concept or give clear and concise information in a purposeful way to the passive learner.|forklarende|
mixed|mixed|Instructional interactions comprised of a mix of active learning and expositive approaches.|blandet|

<a name="learning-resource-type"></a>
#### 1.5. Learning Resource Type ([learningResourceType](./typer-og-egenskaper.md#utdanningsspesifikke-egenskaper))
###### Beskrivelse
Definerer den dominerende sjangeren eller typen som karakteriserer en læringsressurs / <i>Defines  the predominant genre, type or kind characterizing a learning resource</i>.

**Vokabularet er under revisjon av LRMI Task Group.**

###### Multiplisitet
N (mange)

**Kode**|**Term**|**Definisjon**|**Term (norsk)**|**Definisjon (norsk)**|
--------|--------|--------------|----------------|----------------------|
alternateAssessment|alternate assessment|An assessment that is used to evaluate the performance of students who are unable to participate in general assessments even with accommodations.||
assessmentItem|assessment item|A specific prompt, that defines a question or protocol for a measurable activity that triggers a response from a person used to determine whether the person has mastered a learning objective.||
course|course|A series of units and lessons used to teach the skills and knowledge required by its curriculum.||
demonstration-simulation|demonstration/simulation|An imitation or modeling of a real-world process.||
educatorCurriculumGuide|educator curriculum guide|A document that defines what concepts should be taught and/or how a concept should be taught effectively.||
formativeAssessment|formative assessment|A process used by teachers and students during instruction that provides feedback to adjust ongoing teaching and learning to improve students' achievement of intended instructional outcomes.||
images-visuals|images/visuals|Visual media, including but not limited to pictures, graphics, diagrams, figures, illustrations, charts, and maps.||
interim-summativeAssessment|interim/summative assessment|An assessment instrument used to evaluate student learning at the end of an instructional unit by comparing it against some standard or benchmark.||
learningActivity|learning activity|Activities engaged in by the learner for the purpose of acquiring certain skills, concepts, or knowledge, whether guided by an instructor or not. A Lesson may define one or more learning activities.||
lesson|lesson|A detailed description of the course of instruction for a short period of time that is used by a teacher to guide class instruction. A unit contains one or more lessons.||
primarySource|primary source|An artifact, document, recording, or other source of information that was created at the time under study and provides first-hand testimony or direct evidence concerning a topic under investigation.||
rubricScoringGuide|rubric scoring guide|A document or guide that is used to delineate consistent criteria for grading.||
selfAssessment|self assessment|An assessment in which the user gathers information about and reflects on his or her own knowledge, skills, learning, or attitudes.||
text|text|The body of a printed work, to include reading passages.||
textbook|textbook|A book used as a standard source of information on a particular subject.||
unit|unit|A long-range plan of instruction on a particular concept; it contains multiple lessons that are related.||

<a name="tilgjengelighetsvokab"></a>
### 2. Tilgjengelighetsspesifikke vokabularer
Tilgjengelighetsspesifikke vokabularer er hentet fra Accessibility Metadata Project ([a11ymetadata](http://www.a11ymetadata.org/)). Utfyllende beskrivelser av vokabularene, finnes [her](https://www.w3.org/wiki/WebSchemas/Accessibility).

<a name="accessibility-feature"></a>
#### 2.1. Accessibility Feature ([accessibilityFeature](./typer-og-egenskaper.md#tilgjengelighetsspesifikke-egenskaper))
###### Beskrivelse
Innholdsegenskaper til ressursen, for eksempel tilgjengelig multimedia, støttede forbedringer for tilgjengelighet og alternativer / <i>Content features of the resource, such as accessible media, supported enhancements for accessibility and alternatives</i>.

###### Multiplisitet
N (mange)

**Kode**|**Term**|**Definisjon**|
--------|--------|--------------|
alternativeText|alternativ tekst|-
annotations|-|-
audioDescription|-|-
bookmarks|-|-
braille|-|-
captions|-|-
ChemML|-|-
describedMath|-|-
displayTransformability|-|-
highContrastAudio|-|-
highContrastDisplay|-|-
index|-|-
largePrint|-|-
latex|-|-
longDescription|-|-
MathML|-|-
none|-|-
printPageNumbers|-|-
readingOrder|-|-
rubyAnnotations|-|-
signLanguage|-|-
structuralNavigation|-|-
synchronizedAudioText|-|-
tableOfContents|-|-
taggedPDF|-|-
tactileGraphic|-|-
tactileObject|-|-
timingControl|-|-
transcript|-|-
ttsMarkup|-|-
unlocked|-|-

<a name="accessibility-hazard"></a>
#### 2.2. Accessibility Hazard ([accessibilityHazard](./typer-og-egenskaper.md#tilgjengelighetsspesifikke-egenskaper))
###### Beskrivelse
En karakteristisk ved den beskrevne ressursen som er fysiologisk farlig for noen brukere / <i>A characteristic of the described resource that is physiologically dangerous to some users</i>.

###### Multiplisitet
N (mange)

**Kode**|**Term**|**Definisjon**|
--------|--------|--------------|
flashing|-|-
noFlashingHazard|-|-
motionSimulation|-|-
noMotionSimulationHazard|-|-
sound|-|-
noSoundHazard|-|-
unknown|-|-
none|-|-

<a name="accessibility-api"></a>
#### 2.3. Accessibility API ([accessibilityAPI](./typer-og-egenskaper.md#tilgjengelighetsspesifikke-egenskaper))
###### Beskrivelse
Indikerer at ressursen er kompatibel med den angitte tilgjengelighets-APIen / <i>Indicates that the resource is compatible with the referenced accessibility API</i>.

###### Multiplisitet
N (mange)

**Kode**|**Term**|**Definisjon**|
--------|--------|--------------|
AndroidAccessibility|-|-
ARIA|-|-
ATK|-|-
AT-SPI|-|-
BlackberryAccessibility|-|-
Accessible2|-|-
iOSAccessibility|-|-
JavaAccessibility|-|-
MacOSXAccessibility|-|-
MSAA|-|-
UIAutomation|-|-

<a name="accessibility-control"></a>
#### 2.4. Accessibility Control ([accessibilityControl](./typer-og-egenskaper.md#tilgjengelighetsspesifikke-egenskaper))
###### Beskrivelse
Identifiserer en eller flere inndatametoder som gir tilgang til all funksjonalitet i applikasjonen / <i>Identifies one or more input methods that allow access to all of the application functionality.</i>

###### Multiplisitet
N (mange)

**Kode**|**Term**|**Definisjon**|
--------|--------|--------------|
fullKeyboardControl|-|-
fullMouseControl|-|-
fullSwitchControl|-|-
fullTouchControl|-|-
fullVideoControl|-|-
fullVoiceControl|-|-

<a name="access-mode"></a>
#### 2.5. Access Mode ([accessMode](./typer-og-egenskaper.md#tilgjengelighetsspesifikke-egenskaper))
###### Beskrivelse
Det menneskelige sensoriske perceptuelle systemet eller kognitiv fakultet gjennom hvilken en person kan behandle eller oppleve informasjon / <i>The human sensory perceptual system or cognitive faculty through which a person may process or perceive information</i>.

###### Multiplisitet
N (mange)

**Kode**|**Term**|**Definisjon**|
--------|--------|--------------|
auditory|-|-
chartOnVisual|-|-
chemOnVisual|-|-
colorDependent|-|-
diagramOnVisual|-|-
mathOnVisual|-|-
musicOnVisual|-|-
tactile|-|-
textOnVisual|-|-
textual|-|-
visual|-|-

<a name="access-mode-sufficient"></a>
#### 2.6. Access Mode Sufficient ([accessModeSufficient](./typer-og-egenskaper.md#tilgjengelighetsspesifikke-egenskaper))
###### Beskrivelse
En liste over enkelt eller kombinert tilgangsmoduser som er tilstrekkelige for å forstå alt intellektuelt innhold i en ressurs / <i>A list of single or combined accessModes that are sufficient to understand all the intellectual content of a resource</i>.

###### Multiplisitet
N (mange)

**Kode**|**Term**|**Definisjon**|
--------|--------|--------------|
auditory|-|-
tactile|-|-
textual|-|-
visual|-|-
