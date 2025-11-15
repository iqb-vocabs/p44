# Metadatenprofile für Assessment Content Package

ID of profile-store: `acp`

Creator: IQB - Institut zur Qualitätsentwicklung im Bildungswesen

3 Profile definiert:

## Profil "Assessment Content Package Index"

ID of profile: `https://raw.githubusercontent.com/iqb-vocabs/p44/master/index.json`

| Name/Label | Typ | Parameter | ID Profil-Eintrag |
| :--- | :---: | :--- | :---: |
| Art der Erhebung | [Vokabular](https://w3id.org/iqb/v85/dt/) | url: 'https://w3id.org/iqb/v85/dt/', Mehrfachauswahl, Dialogbox, Nummerierung unterdrückt | e1 |
| Schulform | [Vokabular](https://w3id.org/kim/schularten/) | url: 'https://w3id.org/kim/schularten/', Einmalauswahl, Dialogbox, Nummerierung unterdrückt | kim_type_school |
| Untersuchungsdesign | [Vokabular](https://w3id.org/iqb/v85/ed/) | url: 'https://w3id.org/iqb/v85/ed/', Einmalauswahl, Dialogbox, Nummerierung unterdrückt | e4 |
| Erhebungsverfahren | [Vokabular](https://w3id.org/iqb/v85/v2/) | url: 'https://w3id.org/iqb/v85/v2/', Mehrfachauswahl, Dialogbox, Nummerierung unterdrückt | e5 |
| Erhebungseinheit | [Vokabular](https://w3id.org/iqb/v85/ee/) | url: 'https://w3id.org/iqb/v85/ee/', Mehrfachauswahl, Dialogbox | e6 |

## Profil "Assessement Content Package Part"

ID of profile: `https://raw.githubusercontent.com/iqb-vocabs/p44/master/assessmentPart.json`

| Name/Label | Typ | Parameter | ID Profil-Eintrag |
| :--- | :---: | :--- | :---: |
| Klassenstufe | [Vokabular](http://w3id.org/openeduhub/vocabs/educationalLevel/) | url: 'http://w3id.org/openeduhub/vocabs/educationalLevel/', Mehrfachauswahl, Dialogbox, Nummerierung unterdrückt | f0 |
| Für SPF geeignet | Ja/Nein | Text für WAHR: ja, Text für FALSCH: nein | f23 |
| Art der Erhebung | [Vokabular](https://w3id.org/iqb/v85/dt/) | url: 'https://w3id.org/iqb/v85/dt/', Mehrfachauswahl, Dialogbox, Nummerierung unterdrückt | f1 |
| Untersuchungsdesign | [Vokabular](https://w3id.org/iqb/v85/ed/) | url: 'https://w3id.org/iqb/v85/ed/', Einmalauswahl, Dialogbox, Nummerierung unterdrückt | f4 |
| Erhebungseinheit | [Vokabular](https://w3id.org/iqb/v85/ee/) | url: 'https://w3id.org/iqb/v85/ee/', Mehrfachauswahl, Dialogbox | f6 |

## Profil "Assessment Content Package Instrument"

ID of profile: `https://raw.githubusercontent.com/iqb-vocabs/p44/master/instrument.json`

### Allgemein

| Name/Label | Typ | Parameter | ID Profil-Eintrag |
| :--- | :---: | :--- | :---: |
| Klassenstufe | [Vokabular](http://w3id.org/openeduhub/vocabs/educationalLevel/) | url: 'http://w3id.org/openeduhub/vocabs/educationalLevel/', Mehrfachauswahl, Dialogbox, Nummerierung unterdrückt | f0 |
| Für SPF geeignet | Ja/Nein | Text für WAHR: ja, Text für FALSCH: nein | f23 |
| Erhebungseinheit | [Vokabular](https://w3id.org/iqb/v85/ee/) | url: 'https://w3id.org/iqb/v85/ee/', Mehrfachauswahl, Dialogbox | f6 |

### Konstrukte

| Name/Label | Typ | Parameter | ID Profil-Eintrag |
| :--- | :---: | :--- | :---: |
| Leistungsdaten | [Vokabular](https://w3id.org/iqb/v87/ca/) | url: 'https://w3id.org/iqb/v87/ca/', Mehrfachauswahl, Dialogbox, Nummerierung unterdrückt | w101 |
| Fragebogen | [Vokabular](https://w3id.org/iqb/v87/cq/) | url: 'https://w3id.org/iqb/v87/cq/', Mehrfachauswahl, Dialogbox, Nummerierung unterdrückt | w102 |

### Durchführung

| Name/Label | Typ | Parameter | ID Profil-Eintrag |
| :--- | :---: | :--- | :---: |
| Zeit für Durchführung Minuten gesamt | Zahl | Kommastellen: 0, Mindestwert: 0, Maximalwert: kein | iqb_time_booklet |
| Art der Erhebung | [Vokabular](https://w3id.org/iqb/v85/dt/) | url: 'https://w3id.org/iqb/v85/dt/', Mehrfachauswahl, Dialogbox, Nummerierung unterdrückt | f1 |
| Kopfhörereinsatz | [Vokabular](https://w3id.org/iqb/v24/kh/) | url: 'https://w3id.org/iqb/v24/kh/', Einmalauswahl, Dialogbox, Nummerierung unterdrückt | iqb_phones |
| Taschenrechnereinsatz | Ja/Nein | Text für WAHR: ja, Text für FALSCH: nein | iqb_calculator |
| Untersuchungsdesign | [Vokabular](https://w3id.org/iqb/v85/ed/) | url: 'https://w3id.org/iqb/v85/ed/', Einmalauswahl, Dialogbox, Nummerierung unterdrückt | f4 |

