## Confidence scores

Finally let's have a look at confidence scores.

--- task ---
+ Leave Scratch open (we’ll come back in a moment) but go back to the **Learn & Test** page in the Training tool.

+ Type something in the Test box that has nothing to do with lamps or fans. For example, “make me a cheese sandwich”
![Result of entering "make me a cheese sandwich" is lamp off with 21% confidence](images/cheese-sandwich-annotated.png)

+ Look at the confidence score, and check that it’s very low. Compare this with the score you get from commands like “turn on the lamp”. **This is the computer’s way of telling you that it’s not very certain it understands your command, because it doesn’t look like what it learned from your examples.**
--- /task ---

--- task ---
+ Go back to Scratch. You can open your saved project from before if you closed the window.

+ Modify the script for the “classroom” sprite so that it uses this confidence score.
![New code to be added into scratch program](images/code-with-confidence.png)

+ Click the green flag and test again. Try typing commands that have nothing to do with the fan or lamp. Try asking for something to be turned on or off. Check that your classroom reacts in the right way.
--- /task ---

You’ve trained a smart assistant – like a simple version of the assistants you can get on modern smartphones (like Apple’s Siri or Google’s Assistant) or virtual assistant devices (like Amazon’s Alexa or Google’s Home).
You’ve used it to create a smart classroom assistant in Scratch, using machine learning instead of your earlier rules-based approach. 
Training the computer to be able to recognise instructions was hopefully much easier than trying to make a list of every possible command. And the more examples you give it, the better it gets at recognising instructions and the more confident it gets in doing that. 
And now, if it’s not sure what you mean, it will ask you to try again.