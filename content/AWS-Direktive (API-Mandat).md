- Auch bekannt als *„Bezos API-Direktive"* oder *„Amazon API-Direktive"*
- Im Jahr **2002** von Jeff Bezos herausgegeben
- Verpflichtete alle Amazon-Teams, ihre Daten und Funktionen über [[API (DE)|APIs]] bereitzustellen- jede andere Form der internen Kommunikation wurde verboten
- Steigerte die Leistung der Teams erheblich: Jedes Team konnte unabhängig arbeiten, ohne die Arbeit anderer Teams zu beeinträchtigen
- Keine vorgeschriebene Programmiersprache- jedes Team nutzte, was es wollte, solange die Schnittstelle vernetzt und dokumentiert war

Das interne Memo zur API-Direktive (sinngemäß; kein genaues Original bekannt):

```
1. Alle Teams stellen ihre Daten und Funktionen ab sofort über Service-Schnittstellen bereit.

2. Teams kommunizieren ausschließlich über diese Schnittstellen miteinander.

3. Jede andere Form der Prozesskommunikation ist verboten: kein direktes Einbinden, kein direktes Lesen fremder Datenspeicher, kein gemeinsames Speichermodell, keine Hintertüren. Kommunikation erfolgt ausschließlich über Netzwerk-Schnittstellen.

4. Die verwendete Technologie spielt keine Rolle. HTTP, Corba, Pubsub, eigene Protokolle- egal.

5. Alle Schnittstellen müssen von Grund auf so gestaltet sein, dass sie auch externen Entwicklern zugänglich gemacht werden können. Keine Ausnahmen.

6. Wer das nicht umsetzt, wird entlassen.

7. Danke und noch einen schönen Tag!
```
(es ist übersetzt, siehe den Original [[AWS Launch (API Mandate)|hier]])