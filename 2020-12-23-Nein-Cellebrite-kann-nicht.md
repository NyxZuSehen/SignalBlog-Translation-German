# Nein, Cellebrite kann nicht die Signal Verschlüsselung knacken

[Original von moxie0 am 23.12.2020](https://signal.org/blog/cellebrite-and-clickbait/) • [übersetzt von nyx (14.02.2021)](https://twitter.com/nyx_zu_sehen)

Gestern veröffentlichte die BBC eine Geschichte mit der faktisch falschen Schlagzeile: "Signal: Cellebrite erklärt die Verschlüsselung der App geknackt zu haben"  Dies ist falsch. Nicht nur, dass Cellebrite die Signal-Verschlüsselung nicht knacken kann, Cellebrite hat auch nie behauptet, es zu können.

Da wir nicht die Möglichkeit hatten, uns zu dieser Geschichte Stellung zu nehmen, tun wir nun dies, um die Dinge für alle zu klären, die die Überschrift gesehen haben könnten.

#### Unsere Welt

Letzte Woche hat Cellebrite einen (für sie) ziemlich peinlichen technischen Artikel in ihrem Blog veröffentlicht, in dem sie die "fortgeschrittenen Techniken" dokumentieren, die sie verwenden, um Signal auf einem Android-Gerät zu analysieren, auf das sie physischen Zugriff hatten und welches bereits entsperrt war. 

Das ist eine Situation, in der jemand ein entsperrtes Telefon in den Händen hält und einfach die App öffnen könnte, um die Nachrichten zu lesen. In ihrem Beitrag ging es darum, dasselbe automatisch zu tun (was ebenso einfach ist), aber sie schrieben einen ganzen Artikel über die "Herausforderungen", die sie überwunden haben, und kamen zu dem Schluss, dass "... es umfangreiche Forschung an vielen verschiedenen Fronten erforderte, um neue Fähigkeiten von Grund auf zu schaffen."

Das ließ uns wundern. Wenn dies "Forschung" erforderte, dann erweckt das nicht gerade Ehrfurcht vor den vorhandenen Fähigkeiten.

Es ist schwer zu verstehen, wie so ein Posting an die Öffentlichkeit gelangt ist oder warum irgendjemand dachte, dass die Offenlegung solch begrenzter Fähigkeiten in seinem Interesse sei. Basierend auf den anfänglichen Rückmeldungen muss Cellebrite erkannt haben, dass Amateurarbeit keinen guten Eindruck macht, und der Beitrag wurde schnell wieder entfernt. Dann muss ihnen klar geworden sein, dass ein 404-Fehler nicht besser ist, und sie haben ihn wieder durch eine grobe Zusammenfassung ersetzt.

Es ist auch schwer zu sagen, wie eine solch peinliche Wendung der Ereignisse zu etwas anderem als einem Desaster für Cellebrite wurde, aber mehrere Nachrichtenagenturen, einschließlich der BBC, veröffentlichten Artikel über den "Erfolg" von Cellebrite, obwohl es bereits online verfügbare, klärende Informationen gab.

#### Was wirklich geschah

1. **Solange du dein Gerät bei dir hast, sollte Cellebrite keine deiner Sorgen sein.** Es ist wichtig zu verstehen, dass jede Geschichte über "Cellebrite Physical Analyzer"  [Name der Software: Anmerkung der Übersetzer*In] damit beginnt, dass jemand anderes als du dein Gerät mit entsperrtem Bildschirm wortwörtlich in den Händen hält. Was Cellebrite nicht versucht ist: das Abfangen von Nachrichten, Audios, VIdeos oder Signal Calls, oder anders gesagt das Knacken der Verschlüsselung von Signal.
2. **Cellebrite ist keine Zauberei.** Stellen dir vor, dass jemand dein Gerät mit entsperrtem Bildschirm in den Händen hält. Wenn die Person in diesem Moment eine Aufzeichnung dessen erstellen möchte, was sich auf Ihrem Gerät befindet, könnte sie einfach jede App auf Ihrem Gerät öffnen und Screenshots von dem machen, was sich dort befindet. Das ist es, was "Cellebrite Physical Analyser" tut. Es automatisiert den Prozess der Erstellung dieser Aufzeichnung. Da es jedoch automatisiert ist, muss es wissen, wie jede App aufgebaut ist. Daher ist es eigentlich weniger zuverlässig, als das Anfertigen von Screenshots. Es ist keine Magie, es ist eine mittelmäßige kommerzielle Software.
3. **Cellebrite hat nicht "versehentlich" Geheimnisse verraten.** Der Artikel von der BBC, so wie andere Artikel, basieren auf einer falschen Interpretation des Cellebrite Blogartikel über das Hinzufügen einer von Signalunterstützung. Cellebrite veröffentlichte einen ausführlichen Blogartikel, welche sie recht schnell wieder löschten und durch einen weniger ausführlichen ersetzten. Das lag nicht daran, dass sie eine grundlegend neue Technik, die sie entwickelt haben, enthüllt haben (Nur als Erinnerung: Es ist eine Situation, in der die Person lediglich die App öffnen müsste, um sich die Nachrichten anzusehen). Der Grund warum der Artikel gelöscht wurde war eher das Gegenteil: Es hat sie schlecht aussehen lassen. Die eigentlich Artikel Überschrift hätte lauten müssen: "Cellebrite enthüllt das ihre technischen Fähigkeiten genauso veraltet sind wie ihre Rolle in der Welt"

#### Was du tun kannst

Wenn du dir Sorgen machst, dass eine andere Person dein Gerät entsperrt in die Hände bekommt oder Sperre umgeht, dann kann dir Signal dennoch weiterhelfen. Funktionen wie "Verschwindende Nachrichten" und "Einmalige Mediennachrichten" ermöglichen es dir, die Menge an Daten die gewonnen werden kann zu verringern (abhängig von Einstellungen) und deine Chats aufgeräumt zu halten.

Es ist bedauerlich, dass sich solche irreführenden und ungenauen Geschichten wie diese so schnell verbreiten, vor allem, weil so viele Menschen diese Schlagzeile sehen werden und so wenige die Korrektur sehen werden. Wenn du Menschen siehst, die durch diese Art der unverantwortlichen Berichterstattung verwirrt sind, helfe ihnen, indem du den Blogartikel mit ihnen teilen.

#### **Ergänzung der Übersetzer\*In (14.02.2021):**

Das meiste aus diesem Blogartikel trifft auch auf die Meldung ["Court documents show FBI may have tool to access private Signal messages on locked iPhones" von foxbusiness.com](https://www.foxbusiness.com/technology/fbi-tool-access-private-signal-messages-locked-iphones) zu. Das einzige neue ist, dass es wohl gelungen die Nachrichten trotz der Bildschirmsperre auszulesen. "Verschwindende Nachrichten" und "Einmalige Mediennachrichten" können dem aber immer noch entgegenwirken. 