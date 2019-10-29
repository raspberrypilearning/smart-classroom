## Verzamel voorbeelden voor training

\--- task \---
+ Sluit het Scratch-venster en ga terug naar de trainingstool.

+ Klik op de link **< Terug naar project**. \---/task\---

\--- task \---
+ Klik op de knop **Train**. ![Project hoofdmenu](images/project-train-annotated.png)

Je moet enkele voorbeelden verzamelen om de computer te trainen. To collect different examples, you need to create 'buckets' to put the examples in.

+ To create a bucket, click on **+ Add new label** and call the bucket “fan on”. Click on **+ Add new label** again and create a second bucket called “fan off”. Create a third and a fourth bucket called “lamp on” and "lamp off". ![4 lege klassen genaamd ventilator_aan, ventilator_uit, lamp_aan en lamp_uit](images/empty-buckets.png)

+ Click on the **Add example** button in the “fan on” bucket, and type in a command asking for the fan to be turned on. Je kunt bijvoorbeeld typen "Kun je de ventilator inschakelen".

+ Click on the **Add example** button in the “fan off” bucket, and type in a command asking for the fan to be switched off. Je kunt bijvoorbeeld typen: "Ik wil de ventilator nu uit".

+ Do the same for the “lamp on” and “lamp off” buckets.

\--- /task \---

\--- task \---
+ Continue to **Add example**s until you have at least **six** examples in **each** bucket.

Wees fantasierijk! Probeer verschillende manieren te bedenken om elke opdracht te geven. Bijvoorbeeld:

+ Voor "ventilator aan", zou je kunnen klagen dat je het te warm hebt.
+ Voor "ventilator uit", zou je kunnen klagen dat het te fris is.
+ Voor "lamp aan", zou je kunnen klagen dat je niet kunt zien.
+ Voor "lamp uit", zou je kunnen klagen dat het te fel is.

![4 gevulde klassen genaamd ventilator_aan, ventilator_uit, lamp_aan en lamp_uit](images/full-buckets.png)

\--- collapse \---
---
title: Tips voor het selecteren van goede voorbeelden
---
+ **Meer is goed**: hoe meer voorbeelden je geeft aan je programma, hoe beter het programma zou moeten worden in het herkennen van je opdrachten.

+ **Gelijke getallen**: voeg ongeveer hetzelfde aantal voorbeelden toe voor elke opdracht. Als je veel voorbeelden voor één opdracht hebt en niet voor de andere, kan dit de manier beïnvloeden waarop het programma opdrachten leert herkennen.

+ **Maak de voorbeelden echt verschillend van elkaar**: probeer veel verschillende soorten voorbeelden te bedenken. Zorg er bijvoorbeeld voor dat je enkele lange en zeer korte voorbeelden toevoegt.

\--- /collapse \--- \--- /task \---

In the next step you will train your program to recognise any new command automatically by comparing it to the examples in the four buckets.
