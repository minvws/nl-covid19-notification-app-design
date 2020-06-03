# User Stories / Jobs to be Done

Die GGD (Niederlaendische Gesundheitsbehörde) hat die Anforderungen and die Corona-Warn App [Schedule of Requirements (PvE)](https://www.rijksoverheid.nl/onderwerpen/coronavirus-app/documenten/publicaties/2020/05/19/programma-van-eisen) veröffentlicht. Darüber hinaus haben wir eine eigene lange Liste von Anforderungen aus der Sicht der Personen erstellt, die die Anwendung letztendlich verwenden werden. Darin geben wir an, was sie möchten und was die App kann.

| Durchfluss / Abschnitt | Kontext | Motivation erwartetes Ergebnis Version | Referenzanforderung PVE |
| -------------------------------------------------- -------- | -------------------------------------------------- ------------------------------- | -------------------------------------------------- -------------------------------------------------- -------------------------------------------------- --------------------- | -------------------------------------------------- -------------------------------------------------- -------------------------------------------------- ---------------------------- | ----------------- | ------------------ |
| Installation der App / Onboarding | Zum Download | Ich möchte wissen, wo ich die App finden kann so kann ich die app | installieren 1.0 (muss haben) | |
| Installation der App / Onboarding | Betriebssystem nicht auf dem neuesten Stand, Zum Download | Ich möchte informiert werden, ob das Betriebssystem auf meinem Telefon auf dem neuesten Stand ist, um die App zu installieren. Und wissen, was zu tun ist, wenn dies nicht der Fall ist so kann ich die app | installieren 1.0 (muss haben) | |
| Installation der App / Onboarding | Erste Nutzung der App | Ich möchte verstehen, wie die App mir und meiner Umgebung hilft, wenn ich mit jemandem zusammen war, der mich möglicherweise mit dem Corona-Virus infizieren könnte. | So kann ich abschätzen, ob die App für mich ist. | 1.0 (muss haben) | F1, F15, Q8 |
| Installation der App / Onboarding | Erste Nutzung der App | Ich möchte über den Betrieb der App informiert und um Erlaubnis gebeten werden, bevor sie auf meinem Handy wirksam wird. | damit ich die Erlaubnis zur Teilnahme an der medizinischen Forschung gegeben habe. | 1.0 (muss haben) | F1, F2, Q28 |
| Installation der App / Onboarding | Erste Nutzung der App | Ich möchte auf abstrakter Ebene erläutern, wie die App funktioniert und wie sie mit persönlichen Daten und Standortdaten umgeht damit ich beruhigt bin, dass meine Privatsphäre nicht beeinträchtigt wird. Und es ist klar, dass die App keine Standortdaten verarbeitet. | 1.0 (muss haben) | F1, F16, Q8 |
| Installation der App / Onboarding | Erste Nutzung der App | Möchte ich die Auswirkungen der Belichtungsbenachrichtigungen auf die Akkunutzung meines Smartphones verstehen? damit ich abschätzen kann, ob ich mein Smartphone weiterhin so verwenden kann, wie ich es gewohnt bin 1.0 (muss haben) | F1, Q8 |
| Täglicher Gebrauch Berechtigungen geändert Möchte ich benachrichtigt werden, wenn die App nicht ordnungsgemäß funktioniert, weil ich die Berechtigungen widerrufen (oder nicht erteilt) und bei der Erteilung der richtigen Berechtigungen geholfen habe? damit ich die App wieder einschalten kann, wenn sie unbeabsichtigt deaktiviert ist 1.0 (muss haben) | F1, F2, Q14 |
| Täglicher Gebrauch keine Internetverbindung
| Kontaktwarnung und Folgemaßnahmen Aktion nach Kontaktwarnung möchte ich die Kontaktwarnung entfernen können? so dass meine mögliche Kontamination für andere nicht sichtbar ist oder gegen mich verwendet werden kann. | 1.0 (muss haben) | |
| Kontaktwarnung und Folgemaßnahmen Aktion nach Kontaktwarnung Ich möchte die Anweisungen aus der Kontaktwarnung später noch einmal lesen können damit ich eine Antwort auf Fragen finden kann, die mir später einfallen. | 1.0 (muss haben) | |
| Positives Testergebnis und Auslösen der Kontaktwarnung Positiv getestet | Wenn ich ein positives Testergebnis erhalten habe, möchte ich Menschen warnen, die ich getroffen habe, als ich bereits ansteckend war Also habe ich alles getan, um zu verhindern, dass sie mehr Menschen infizieren. | 1.0 (muss haben) | |
| Generisches | Benutzer hat Fragen oder Bedenken möchte im Detail verstehen, wie die App funktioniert, einschließlich der Möglichkeit, den Quellcode der App usw. zu überprüfen. | Damit bin ich sicher, dass alles in Bezug auf Datenschutz und Sicherheit getan wurde. | 1.1 (sollte haben) | F1, Q29 |
| Generisches | begrenzte Sprachkenntnisse, begrenzte technische Kenntnisse, senso- / motorische Beeinträchtigung möchte ich alle funktionalitäten in der app | nutzen können? damit ich helfen kann, eine weitere Ausbreitung des Virus zu verhindern 1.0 (muss haben) | Q17, Q18 |
| Deinstallation der App / Offboarding | Ich möchte die App nicht mehr verwenden möchte ich mein Belichtungsprotokoll löschen können? damit ich zurückgehen kann, wenn ich es mir später anders überlege 1.0 (muss haben) | |
| Deinstallation der App / Offboarding | Ich möchte die App nicht mehr verwenden Ich möchte die App von meinem Telefon entfernen können damit ich es nicht mehr benutzen kann / muss. | 1.0 (muss haben) | |
| Täglicher Gebrauch will Einblick in Daten und Verhalten Ich möchte einen Einblick in die Anzahl der Benachrichtigungen auf Postleitzahlebene erhalten damit ich sehen kann, wie es meiner Nachbarschaft im Vergleich zu anderen Nachbarschaften geht Wird nicht haben | |
| Täglicher Gebrauch will Einblick in Daten und Verhalten will die Rohdaten verstehen, die das Telefon speichert, das Logbuch | Damit bekomme ich eine zusätzliche Bestätigung, dass die Anwendung ordnungsgemäß funktioniert, und registriere Besprechungen Wird nicht haben | |
| Täglicher Gebrauch Aktion nach Kontaktwarnung


#### Todo: Die folgenden nicht funktionalen Anforderungen müssen noch verarbeitet oder diskutiert werden:

- Q32. Alle in der App angezeigten Texte haben Quellenangaben und werden von der genannten Quelle bestimmt.
- Q33. Dem Benutzer ist klar, dass es sich bei der App um eine App handelt, die von der niederländischen Regierung empfohlen, verwaltet und genehmigt wurde.
- Q16. Die App kann damit umgehen und ist in den wichtigsten Sprachen für die Benutzer verfügbar.

HINWEIS: Dieses Dokument ist auch [auf Englisch] verfügbar (../en-US/job-stories.en.md). Die niederländische Sprachversion ist führend.
HINWEIS: Dieses Dokument ist auch [auf Niederländisch] verfügbar (../../job-stories.md). Die niederländische Sprachversion ist führend.
