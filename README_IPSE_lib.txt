# IPSE
 IPSE Prjects and libs

#########Adsorption############
Datei:
C:\Users\Gregor Tondl\Jlab_testbed\Objektorientiert\IPSE\IPSE Projects\adsorbtion\zerobin\AET_Lib_TSA_Mar2019\TSA_Model_1_Stage\TSA_1stage_V1.pro

mit Lib:
C:\Users\Gregor Tondl\Jlab_testbed\Objektorientiert\IPSE\IPSE Projects\adsorbtion\zerobin\AET_Lib_TSA_Mar2019

kann nur mit IPSE 5.1 gestartet werden!!!!

Simprop.dll muss ausgetauscht werden im Pfad

Ipse installations datei Pfad:
C:\Program Files (x86)\SimTech\IPSEpro\Exe


    Sehr geehrte Damen und Herren,

    wir sind gerade dabei am Institut für Verfahrenstechnik, auf die neue Version von IPSEpro 8 umzustellen.
    Dabei wollen wir natürlich alte bestehende Modellbibliotheken weiter benutzen.
    Als Beispiel verwenden wir eine Bilb namens AET_Lib mit eigenen Stoffdaten (Anhang). Bisher reichte es die Datei simprop.dll in den Pfad

    C:\Program Files (x86)\SimTech\IPSEpro\Exe


    zu kopieren und auszutauschen.

    In der neuen Version IPSEpro 8 gibt es jedoch keine simprop.dll mehr.

    Könnten Sie mir vielleicht hier weiterhelfen, damit wir unsere alten Bibliotheken weiterbenutzen können?

Ich habe vor gut zwei Monaten mit David Wöß ein sehr ähnliches Problem besprochen.




    Zum Fehler und der simprop.dll. Soweit ich mich erinnere, ruft die simprop.dll die PPSystem.dll auf. Damit das aber funktioniert, muss die PPSystem.dll im Exe-Verzeichnis der aufrufenden Applikation, das ist das IPSEpro-PSE, liegen. Lege also eine Kopie der PPSystem.dll ins Exe-Verzeichnis. Die simprop.dll gehört nur ins Verzeichnis der Modellbibliothek.




Bei ihm hat er im Anschluß seine Modellbibliothek wieder verwenden können. Bitte um eine kurze Nachricht, ob das auch bei Ihnen der Fall ist.

Mit freundlichen Grüßen,

Stefan Bergmann