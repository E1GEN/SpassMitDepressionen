```mermaid
flowchart LR

%% Formatierung

classDef Beschreibung fill:#eff4f5,color:#32464B,stroke:none,font-size:0.9em

classDef Knoten fill:#098eb0,stroke:none,color:white,font-size:1.1em

classDef Formular fill:#ffa,stroke:#996600,color:#996600,font-size:1.3em,padding:0.1em

classDef Ziel fill:#9d9,stroke:#060,color:#040,font-size:1.3em,padding:0.1em

%% Erstellen der Objekte
01(
    Psychotherapeutische
    Sprechstunde
):::Knoten

02(
    PTV11 Formular
):::Formular

03{
    Kann die
    Therapie hier
    weitergehen?
}:::Knoten

04(
    Therapieplatzsuche durch
    den Patientenservice oder auf eigene Faust
    116 117
):::Knoten

05(
    Probatorische Sitzungen
):::Knoten

06{
    Stimmt die
    Chemie?
}:::Knoten

07(
    Therapiebeginn
):::Ziel

%% Spalte 2: Hauptdiagramm

01 ==> 02

03 ==>|: NEIN :| 04
03 ==>|: JA :| 05

02 ==> 03

04 ==> 05

05 ==> 06

06 ==>|: NEIN :| 04
06 ==>|: JA :| 07




%% Erläuterungen
zu_01[
    Einstiegspunkt für jede Therapieplatzsuche.
    Alle ärztlichen und psychologischen
    Psychotherapeutinnen und -Therapeuten
    müssen Sprechstunden anbieten.
    Diese sind aber auch für die Patienten
    verpflichtend, um in eine Therapie
    einsteigen zu können. Gewöhnlich sind das
    bis zu 3 Termine à 50 Minuten.

    Hier wird erst einmal abgeklärt,
    ob der Verdacht auf eine psychische
    Erkrankung besteht und ob eventuell
    eine Akutbehandlung angebracht ist.
]:::Beschreibung-.-

zu_02[
    Eure Diagnose wird auf einem Formular
    mit der Bezeichnung PTV11 festgehalten.

    Auf diesem Formular wird
    eingetragen, ob eine behandlungs-
    bedürftige psychische Erkrankung vorliegt
    und ob es Begleiterscheinungen -
    sog. somatoforme Störungen - gibt.
    Zudem wird festgehalten, welcher Therapieansatz
    für den Start eurer Therapie empfohlen wird.
    
    Das PTV11 Formular enthält auch einen Code,
    mit dem ihr euch an den Patientenservice 116 117
    wenden könnt.

    Dieses Formular solltet ihr gut aufbewahren!
]:::Beschreibung-.-

zu_03[
    Es ist gut möglich, dass ihr die Therapie nicht
    gleich in der Praxis starten könnt, in der euch
    die Diagnose gestellt wurde.
    Das kann daran liegen, dass dort keine Expertise
    für euren empfohlenen Therapieansatz besteht.
    Es kann aber auch einfach an fehlenden
    Kapazitäten liegen.
 ]:::Beschreibung-.-

zu_04[
    Sofern ihr die Therapie nicht in der
    Praxis fortführen könnt, in der die
    Diagnose gestellt wurde, könnt ihr euch
    nun mit den Code auf eurem PTV11 Formular
    an den Patientenservice 116 117 wenden.
    Dieser erhält damit alle erforderlichen
    Informationen, um für euch einen passenden
    Therapieplatz suchen zu können.

    Ab hier heißt es erst einmal abwarten,
    bis ihr Rückmeldung erhaltet.
    Ihr müsst aber nicht tatenlos herumsitzen.
    Es ist absolut erlaubt, dass ihr auch
    selbst auf die Suche geht, sofern ihr
    euch das gerade zutraut. Gebt aber bitte
    Rückmeldung, falls ihr selbst fündig
    werdet, damit hier nicht unnötig
    Ressourcen belegt werden.

    Geht es euch sehr schlecht, könnt ihr
    in der Zwischenzeit mit eurer Hausärztin
    oder eurem Hausarzt bereden, ob ihr
    übergangsweise Medikamente einnehmen
    möchtet, damit ihr besser klar kommt,
    bis euch anderweitig geholfen werden kann.
]:::Beschreibung-.-

zu_05[05 Bei den probatorischen Sitzungen
    handelt es sich um Probesitzungen
    die je nach eurer Empfehlung als
    Einzel- oder Gruppensitzung stattfinden
    können. Hier können die Therapeutin bzw.
    der Therapeut eine präzisere Diagnose
    stellen, um den für euch passenden
    Behandlungsweg bestimmen zu können.
]:::Beschreibung-.-

zu_06[
    Die probatorischen Sitzungen geben sowohl
    euch die Gelegenheit, festzustellen, ob ihr
    euch mit eurem Gegenüber wohl fühlt.
    Falls nicht, habt ihr jederzeit das Recht,
    eure Suche weiterzuführen. Ihr braucht auch
    keine Scheu zu haben, dies den Therapeuten
    mitzuteilen. Diese wissen, dass eine
    gute Chemie wichtig ist.
]:::Beschreibung-.-

zu_07[
    Nach mindestens 2 probatorischen
    Sitzungen kann die Therapeutin oder
    der Therapeut bei der Krankenkasse
    die für euch zutreffende Therapieform
    beantragen. Neben einer Kurz- oder
    Langzeittherapie gibt es noch einige
    weitere Formen, die hier den Rahmen 
    sprengen würden. Das wird euch dann
    aber ausführlich erklärt.

Herzlichen Glückwunsch! Ihr habt jetzt
zumindest einen Therapieplatz.

Nun liegt es auch an euch!]:::Beschreibung
