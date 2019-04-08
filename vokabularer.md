<a name="vokabularer"></a>
# Vokabularer
Flere egenskaper i NS4180 er tilknyttet etablerte internasjonale vokabularer. Det vil si at når egenskapene tilordnes verdier bør verdiene hentes fra disse vokabularene.

Vokabularene er ikke uttømmende, de definerer p.t. toppnivåbegreper som er ment å fungere i en internasjonal kontekst.

Nasjonale tilpasninger av vokabularene vil foregå her. Tilpasninger spenner fra norske oversettelser av eksisterende termer og definisjoner til spesifisering av nye termer og definisjoner. 

## Innholdsfortegnelse
1.	[Utdanningsspesifikke vokabularer](#utdanningsvokab)  
	* 	1.1. [Alignment Type](#alignment-type) 
	* 	1.2. [Educational Audience Role](#educational-audience-role)
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
Utdanningsspesifikke vokabularer er hentet fra Learning Resource Metadata Initiative (<a href="http://lrmi.dublincore.net/">LRMI</a>).

For utfyllende informasjon om vokabularene, se <a href="http://lrmi.dublincore.net/specifications/concept_schemes/">http://lrmi.dublincore.net/specifications/concept_schemes/</a>

 

<a name="alignment-type"></a>
#### 1.1. Alignment Type (<a href="#">alignmentType</a>)
###### Beskrivelse
Definerer relasjonstyper mellom en læringsressurs og en node i et utdanningsrammeverk / <i>Defines the types of relationships between a learning resource and a node in an educational framework</i>.

###### Multiplisitet
N (mange)

<table>
<tr><th>Kode</th><th>Term</th><th>Definisjon</th><th>Term (no)</th><th>Definisjon (no)</th></tr>
<tr><td>assesses</td><td>assesses</td><td>The learning resource being described may be used to assess the competency being referenced.</td><td>vurderer</td><td>Den beskrevne læringsressursen kan brukes til å vurdere referert kompetanse.</td></tr>
<tr><td>complexityLevel</td><td>complexity level</td><td>The point in the framework being referenced defines a level or range that measures the difficulty or challenge presented by the learning resource being described.</td><td>vanskelighetsgrad</td><td>Det refererte punktet i rammeverket angir et nivå eller område som mål for vanskelighets- eller utfordringsgrad for læringsressursen som beskrives.</td></tr>
<tr><td>educationalLevel</td><td>educational level</td><td>The point in the framework being referenced defines a level or stage within an education system for which the resource being described is intended or useful.</td><td>utdanningsnivå</td><td>Det refererte punktet i rammeverket angir et nivå eller stadium i utdanningssystemet der den beskrevne ressursen er tiltenkt eller anvendelig.</td></tr>
<tr><td>educationalSubject</td><td>educational subject</td><td>The point in the framework being referenced defines the subject context of the learning resource being described.</td><td>undervisningsfag</td><td>Det refererte punktet i rammeverket angir den faglige konteksten for den beskrevne læringsressursen.</td></tr>
<tr><td>prerequisite</td><td>prerequisite</td><td>The competency being referenced is a learning prerequisite to the effective outcome of the learning resource being described.</td><td>forutsetning</td><td>Den refererte kompetansen er en læringsmessig forutsetning for effektiv anvendelse av den beskrevne lærings¬ressursen.</td></tr>
<tr><td>readingLevel</td><td>reading level</td><td>The point in the framework being referenced defines a level or range of reading ability expected for a person using the learning resource being described.</td><td>lesenivå</td><td>Det refererte punktet i rammeverket angir et nivå eller område av evne til lesing som forventes av en person som skal benytte den beskrevne læringsressursen.</td></tr>
<tr><td>teaches</td><td>teaches</td><td>The learning resource being described may be used to teach the competency being referenced.</td><td>underviser</td><td>Den beskrevne læringsressursen kan benyttes til å undervise i den refererte kompetansen.</td></tr>
</table>

<a name="educational-audience-role"></a>
#### 1.2. Educational Audience Role (<a href="#">educationalRole</a>)
###### Beskrivelse
Definerer primære eller tilsiktede roller hos målgruppen (mottaker) til ressursen som beskrives / <i>Defines the primary or intended roles of the audience (beneficiary) of the resource being described</i>.

###### Multiplisitet
N (mange)

<table>
<tr><th>Kode</th><th>Term</th><th>Definisjon</th><th>Term</th><th>Definisjon</th></tr>
<tr><td>administrator</td><td>administrator</td><td>A trainer or educator with administrative authority and responsibility.</td><td>administrator</td><td>En trener eller instruktør på regionalt eller skolenivå med administrativt ansvar.</td></tr>
<tr><td>generalPublic</td><td>general public</td><td>The public at large.</td><td>allmennheten</td><td>Allmennheten.</td></tr>
<tr><td>mentor</td><td>mentor</td><td>Someone who advises, trains, supports, and/or guides.</td><td>mentor</td><td>En som driver rådgivning, opplæring, støtte eller veiledning.</td></tr>
<tr><td>parent</td><td>parent</td><td>A father, mother, or legal guardian.</td><td>foresatt</td><td>En far, mor eller verge.</td></tr>
<tr><td>peerTutor</td><td>peer tutor</td><td>The peer learner serving as tutor of another learner.</td><td>fagfelle</td><td>En elev eller student som underviser medelev eller medstudent.</td></tr>
<tr><td>professional</td><td>professional</td><td>Someone already practicing a profession; an industry partner, or professional development trainer.</td><td>yrkesaktiv</td><td>En som allerede praktiserer et yrke; en industripartner eller videreutdanningsinstruktør.</td></tr>
<tr><td>student</td><td>student</td><td>The learner or trainee.</td><td>elev/student</td><td>Den lærende eller lærlingen.</td></tr>
<tr><td>teacher</td><td>teacher</td><td>A person who has been trained to implement educational methods and practices.</td><td>lærer</td><td>En person som er opplært til å implementere pedagogiske metoder og praksiser.</td></tr>
</table>

<a name="educational-use"></a>
#### 1.3. Educational Use (<a href="#">educationalUse</a>)
###### Beskrivelse
Opplisting av pedagogisk bruksområder for en læringsressurs / <i>Enumerates the educational uses of a learning resource</i>.

###### Multiplisitet
N (mange)

<table>
<tr><th>Kode</th><th>Term</th><th>Definisjon</th><th>Term</th><th>Definisjon</th></tr>
<tr><td>assessment</td><td>assessment</td><td>Primary purpose of the resource is to evaluate learning, before, during, or after instruction occurs.</td><td>vurdering</td><td>Hovedformålet med ressursen er å vurdere læring, før, under eller etter undervisningen.</td></tr>
<tr><td>instruction</td><td>instruction</td><td>Primary purpose of the resource is to support the instructional process, student learning, or to provide information about the curriculum.</td><td>undervisning</td><td>Hovedformålet med ressursen er å støtte undervisningsprosessen, elevens læring eller å gi informasjon om undervisningsplanen.</td></tr>
<tr><td>professionalSupport</td><td>professional support</td><td>Primary purpose of the resource is to provide instruction for a teacher or other education professional including professional development.</td><td>profesjonell støtte</td><td>Hovedformålet med ressursen er å gi instruksjon til en lærer eller en annen instruktør inkludert utvikling.</td></tr>
</table>

<a name="interactivity-type"></a>
#### 1.4. Interactivity Type (<a href="#">interactivityType</a>)
###### Beskrivelse
Definerer den overordnede interaktive modusen til læringsressursen som beskrives / <i>Defines the predominate interact mode of the learning resource being described</i>.

###### Multiplisitet
N (mange)

<table>
<tr><th>Kode</th><th>Term</th><th>Definisjon</th><th>Term</th><th>Definisjon</th></tr>
<tr><td>active</td><td>active</td><td>Learning that engages and challenges the learner's thinking using real-life and/or imaginary situations taking advantage of the opportunities for learning presented by investigating, exploring, events, and life experiences.</td><td>aktiv</td><td></td></tr>
<tr><td>expositive</td><td>expositive</td><td>Use of a subject-matter expert to explain a concept or give clear and concise information in a purposeful way to the passive learner.</td><td>forklarende</td><td></td></tr>
<tr><td>mixed</td><td>mixed</td><td>Instructional interactions comprised of a mix of active learning and expositive approaches.</td><td>blandet</td><td></td></tr>
</table>

<a name="learning-resource-type"></a>
#### 1.5. Learning Resource Type (<a href="#">learningResourceType</a>)

Vokabularet er under revisjon.

<a name="tilgjengelighetsvokab"></a>
### 2. Tilgjengelighetsspesifikke vokabularer
Tilgjengelighetsspesifikke vokabularer er hentet fra Accessibility Metadata Project (<a href="http://www.a11ymetadata.org/">a11ymetadata</a>).

For utfyllende informasjon om vokabularene, se <a href="https://www.w3.org/wiki/WebSchemas/Accessibility">https://www.w3.org/wiki/WebSchemas/Accessibility</a>

<a name="accessibility-feature"></a>
#### 2.1. Accessibility Feature (<a href="#">accessibilityFeature</a>)
###### Beskrivelse
Innholdsegenskaper til ressursen, for eksempel tilgjengelig multimedia, støttede forbedringer for tilgjengelighet og alternativer / <i>Content features of the resource, such as accessible media, supported enhancements for accessibility and alternatives</i>.

###### Multiplisitet
N (mange)

<table>
<tr><th>Kode</th><th>Term</th><th>Definisjon</th></tr>
<tr><td>alternativeText</td><td>alternativ tekst</td><td>-</td></tr>
<tr><td>annotations</td><td>-</td><td>-</td></tr>
<tr><td>audioDescription</td><td>-</td><td>-</td></tr>
<tr><td>bookmarks</td><td>-</td><td>-</td></tr>
<tr><td>braille</td><td>-</td><td>-</td></tr>
<tr><td>captions</td><td>-</td><td>-</td></tr>
<tr><td>ChemML</td><td>-</td><td>-</td></tr>
<tr><td>describedMath</td><td>-</td><td>-</td></tr>
<tr><td>displayTransformability</td><td>-</td><td>-</td></tr>
<tr><td>highContrastAudio</td><td>-</td><td>-</td></tr>
<tr><td>highContrastDisplay</td><td>-</td><td>-</td></tr>
<tr><td>index</td><td>-</td><td>-</td></tr>
<tr><td>largePrint</td><td>-</td><td>-</td></tr>
<tr><td>latex</td><td>-</td><td>-</td></tr>
<tr><td>longDescription</td><td>-</td><td>-</td></tr>
<tr><td>MathML</td><td>-</td><td>-</td></tr>
<tr><td>none</td><td>-</td><td>-</td></tr>
<tr><td>printPageNumbers</td><td>-</td><td>-</td></tr>
<tr><td>readingOrder</td><td>-</td><td>-</td></tr>
<tr><td>rubyAnnotations</td><td>-</td><td>-</td></tr>
<tr><td>signLanguage</td><td>-</td><td>-</td></tr>
<tr><td>structuralNavigation</td><td>-</td><td>-</td></tr>
<tr><td>synchronizedAudioText</td><td>-</td><td>-</td></tr>
<tr><td>tableOfContents</td><td>-</td><td>-</td></tr>
<tr><td>taggedPDF</td><td>-</td><td>-</td></tr>
<tr><td>tactileGraphic</td><td>-</td><td>-</td></tr>
<tr><td>tactileObject</td><td>-</td><td>-</td></tr>
<tr><td>timingControl</td><td>-</td><td>-</td></tr>
<tr><td>transcript</td><td>-</td><td>-</td></tr>
<tr><td>ttsMarkup</td><td>-</td><td>-</td></tr>
<tr><td>unlocked</td><td>-</td><td>-</td></tr>
</table>

<a name="accessibility-hazard"></a>
#### 2.2. Accessibility Hazard (<a href="#">accessibilityHazard</a>)
###### Beskrivelse
En karakteristisk ved den beskrevne ressursen som er fysiologisk farlig for noen brukere / <i>A characteristic of the described resource that is physiologically dangerous to some users</i>.

###### Multiplisitet
N (mange)

<table>
<tr><th>Kode</th><th>Term</th><th>Definisjon</th></tr>
<tr><td>flashing</td><td>-</td><td>-</td></tr>
<tr><td>noFlashingHazard</td><td>-</td><td>-</td></tr>
<tr><td>motionSimulation</td><td>-</td><td>-</td></tr>
<tr><td>noMotionSimulationHazard</td><td>-</td><td>-</td></tr>
<tr><td>sound</td><td>-</td><td>-</td></tr>
<tr><td>noSoundHazard</td><td>-</td><td>-</td></tr>
<tr><td>unknown</td><td>-</td><td>-</td></tr>
<tr><td>none</td><td>-</td><td>-</td></tr>
</table>

<a name="accessibility-api"></a>
#### 2.3. Accessibility API (<a href="#">accessibilityAPI</a>)
###### Beskrivelse
Indikerer at ressursen er kompatibel med den angitte tilgjengelighets-APIen / <i>Indicates that the resource is compatible with the referenced accessibility API</i>.

###### Multiplisitet
N (mange)

<table>
<tr><th>Kode</th><th>Term</th><th>Definisjon</th></tr>
<tr><td>AndroidAccessibility</td><td>-</td><td>-</td></tr>
<tr><td>ARIA</td><td>-</td><td>-</td></tr>
<tr><td>ATK</td><td>-</td><td>-</td></tr>
<tr><td>AT-SPI</td><td>-</td><td>-</td></tr>
<tr><td>BlackberryAccessibility</td><td>-</td><td>-</td></tr>
<tr><td>Accessible2</td><td>-</td><td>-</td></tr>
<tr><td>iOSAccessibility</td><td>-</td><td>-</td></tr>
<tr><td>JavaAccessibility</td><td>-</td><td>-</td></tr>
<tr><td>MacOSXAccessibility</td><td>-</td><td>-</td></tr>
<tr><td>MSAA</td><td>-</td><td>-</td></tr>
<tr><td>UIAutomation</td><td>-</td><td>-</td></tr>
</table>

<a name="accessibility-control"></a>
#### 2.4. Accessibility Control (<a href="#">accessibilityControl</a>)
###### Beskrivelse
Identifiserer en eller flere inndatametoder som gir tilgang til all funksjonalitet i applikasjonen / <i>Identifies one or more input methods that allow access to all of the application functionality.</i>

###### Multiplisitet
N (mange)

<table>
<tr><th>Kode</th><th>Term</th><th>Definisjon</th></tr>
<tr><td>fullKeyboardControl</td><td>-</td><td>-</td></tr>
<tr><td>fullMouseControl</td><td>-</td><td>-</td></tr>
<tr><td>fullSwitchControl</td><td>-</td><td>-</td></tr>
<tr><td>fullTouchControl</td><td>-</td><td>-</td></tr>
<tr><td>fullVideoControl</td><td>-</td><td>-</td></tr>
<tr><td>fullVoiceControl</td><td>-</td><td>-</td></tr>
</table>

<a name="access-mode"></a>
#### 2.5. Access Mode (<a href="#">accessMode</a>)
###### Beskrivelse
Det menneskelige sensoriske perceptuelle systemet eller kognitiv fakultet gjennom hvilken en person kan behandle eller oppleve informasjon / <i>The human sensory perceptual system or cognitive faculty through which a person may process or perceive information</i>.

###### Multiplisitet
N (mange)

<table>
<tr><th>Kode</th><th>Term</th><th>Definisjon</th></tr>
<tr><td>auditory</td><td>-</td><td>-</td></tr>
<tr><td>chartOnVisual</td><td>-</td><td>-</td></tr>
<tr><td>chemOnVisual</td><td>-</td><td>-</td></tr>
<tr><td>colorDependent</td><td>-</td><td>-</td></tr>
<tr><td>diagramOnVisual</td><td>-</td><td>-</td></tr>
<tr><td>mathOnVisual</td><td>-</td><td>-</td></tr>
<tr><td>musicOnVisual</td><td>-</td><td>-</td></tr>
<tr><td>tactile</td><td>-</td><td>-</td></tr>
<tr><td>textOnVisual</td><td>-</td><td>-</td></tr>
<tr><td>textual</td><td>-</td><td>-</td></tr>
<tr><td>visual</td><td>-</td><td>-</td></tr>
</table>

<a name="access-mode-sufficient"></a>
#### 2.6. Access Mode Sufficient (<a href="#">accessModeSufficient</a>)
###### Beskrivelse
En liste over enkelt eller kombinert tilgangsmoduser som er tilstrekkelige for å forstå alt intellektuelt innhold i en ressurs / <i>A list of single or combined accessModes that are sufficient to understand all the intellectual content of a resource</i>.

###### Multiplisitet
N (mange)

<table>
<tr><th>Kode</th><th>Term</th><th>Definisjon</th></tr>
<tr><td>auditory</td><td>-</td><td>-</td></tr>
<tr><td>tactile</td><td>-</td><td>-</td></tr>
<tr><td>textual</td><td>-</td><td>-</td></tr>
<tr><td>visual</td><td>-</td><td>-</td></tr>
</table>
