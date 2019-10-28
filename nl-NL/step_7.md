## Hoe betrouwbaarheidsscores te gebruiken

Ten slotte leer je wat betrouwbaarheidsscores betekenen en hoe je ze moet gebruiken.

\--- task \---
+ Laat Scratch open, want je komt zo terug.

+ Ga terug naar de pagina **Leer & Test** in de trainingstool.

+ Typ iets dat niets te maken heeft met lampen of ventilatoren in de testbox. Je kunt bijvoorbeeld typen 'geef me een boterham met kaas'. ![Result of entering "make me a cheese sandwich" is lamp off with 21% confidence](images/cheese-sandwich-annotated.png)

+ Kijk naar de betrouwbaarheidsscore, die erg laag zou moeten zijn.

+ Vergelijk dit met de betrouwbaarheidsscore die je krijgt voor een commando zoals "doe de lamp aan".

**De betrouwbaarheidsscore is de manier van het programma om je te vertellen hoe zeker het is dat het een opdracht begrijpt.** Als een opdracht erg lijkt op de voorbeelden waarmee je het programma hebt getraind, is de betrouwbaarheidsscore hoog. If a command is **not** similar, the confidence score is low.

\--- /task \---

\--- task \---

+ Go back to your classroom assistant project in Scratch.

+ Modify the script for the 'classroom' sprite so that it uses the confidence score:

![New code to be added into scratch program](images/code-with-confidence.png)

+ Click the green flag and test your program to check that your classroom assistant reacts in the right way:
    + Type in commands that have nothing to do with the fan or lamp
    + Ask for something to be turned on or off

Now, if your program is not sure what you mean, it tells you so. Then you can try giving it another command. \--- /task \---

You’ve used machine learning to train a smart assistant that is a simple version of the assistants you can get on smartphones (e.g. Apple’s Siri or Google’s Assistant) or at home (e.g. Amazon’s Alexa or Google’s Home).

Training the program to recognise commands is much easier than trying to make a list of every possible command. And the more examples you give the program, the better it gets at recognising commands, and the more its confidence scores increase. 