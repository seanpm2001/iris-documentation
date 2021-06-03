## 3.1 Funktionsüberblick Indexfall-Nachverfolgung


Im Bereich Indexfall-Nachverfolgung bietet IRIS die Möglichkeiten:



* Eine neue Indexfall-Abfrage zu starten
* Offene Indexfall-Anfragen einzusehen
* Übertragene Daten aus einer Indexfall-Anfrage zur Weiterbearbeitung zu übernehmen


### 3.1.1 Starten einer neuen Indexfall-Abfrage

Nach dem Starten einer neuen Indexfall-Abfrage wird eine spezifische TAN-Nummer für den/die Infizierten generiert und kann per E-Mail an diese/n versendet werden, oder sie wird beim Erstgespräch telefonisch übermittelt.

In der E-Mail werden der/dem Infizierten verschiedene Optionen zur Übermittlung der eigenen Kontakthistorie genannt:



* Via Kontakttagebuch-App (z.Zt. bereits Coronika angeschlossen): Hier kann der/die Infizierte durch Eingabe eines Tokens die Daten für das Gesundheitsamt freigeben und versenden. Voraussetzung ist natürlich, dass der/die Infizierte die eine Tagebuch-App installiert hat und verwendet.
* Via Online-Webformular: Über die Webseite [https://digitales-wartezimmer.org](https://digitales-wartezimmer.org) können Infizierte selbständig Daten erfassen, wann sie wo mit wem gewesen sind. Die Übermittlung erfolgt mittels eines Tokens direkt an das zugeordnete Gesundheitsamt. 
* Als weitere Alternative wird eine Anbindung an das Kontakttagebuch und die Meldefunktionen der Corona Warn App gemeinsam mit den Entwicklern der CWA konzipiert. Hier gibt der Schlüssel des positiven Testergebnisses die Möglichkeit, Daten ins Gesundheitsamt zu senden. Es wird also eine Möglichkeit der freiwilligen Partizipation gegeben.

**_» Das IRIS Portal geht neue Wege, indem es die Bevölkerung befähigt, an der öffentlichen Gesundheit positiv mitzuwirken «_**


### 3.1.2 Prüfen offener Indexfall-Abfragen



*   In einer übersichtlichen Liste werden alle aktuell vom Gesundheitsamt angefragten Indexfälle gelistet.
*   Hier ändert sich der Status eines Eintrags, sobald der Indexfall via Webformular oder App Daten für das Gesundheitsamt bereitgestellt hat.
*   Eine Filter- und Sortierfunktion erleichtert die Übersicht.


![IRIS_index_dashboard](images/IRIS_index_dashboard.png "Offene Indexfall-Abfragen (Screenshot enthält Beispiel- oder Testdaten)")
_Offene Indexfall-Abfragen (Screenshot enthält Beispiel- oder Testdaten)_


### 3.1.3 Weiterbearbeitung bereitgestellter Daten


Daten eines Indexfalls, die dieser via Webformular oder App bereitgestellt hat, können in IRIS zur Voransicht geöffnet werden.



* In der Voransicht hat der Mitarbeitende des Gesundheitsamts die Möglichkeit, einzelne Ereignisse, Begegnungen und Kontakte manuell an- oder abzuwählen. Dies ist deshalb erforderlich, weil es doppelte Einträge oder bspw. auch evtl. Fantasieorte geben kann, die der Indexfall angegeben hat.
* Nach der Anwahl der zu übernehmenden Daten können diese an eine Fachanwendung übergeben werden.
* Hier stehen als Optionen derzeit eine direkte Schnittstelle zu SORMAS und ein JSON/CSV-Export zur Verfügung. In Planung sind mögliche Anbindungen an weitere Systeme wie bspw. Octoware, Äskulab21, ISGA, Mikado, o.a. bzw. Eigenentwicklungen, sofern diese Anwendungen entsprechende Funktionen haben oder entwickeln.
* In SORMAS werden automatisch die entsprechenden Aufgaben für die Kontaktnachverfolung zur Weitergabe an entsprechende weitere Mitarbeitende erstellt. Dies erleichtert ggf. die Koordinierung innerhalb des Gesundheitsamts.
