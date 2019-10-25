## Collect examples for training

--- task ---
+ Close the Scratch window and go back to the Training tool.

+ Click on the **< Back to project** link.
--- /task ---

--- task ---
+ Click on the **Train** button.
![Project main menu](images/project-train-annotated.png)

You need to collect some examples to train the computer. To collect different examples, you need to create 'buckets' to put the examples in.

+ To create a bucket, click on **+ Add new label** and call the bucket “fan on”. Click on **+ Add new label** again and create a second bucket called “fan off”. Create a third and a fourth bucket called “lamp on” and "lamp off".
![4 empty classes named fan_on, fan_off, lamp_on and lamp_off](images/empty-buckets.png)

+ Click on the **Add example** button in the “fan on” bucket, and type in a command asking for the fan to be turned on. For example, you could type “Please can you switch on the fan”. 

+ Click on the **Add example** button in the “fan off” bucket, and type in a command asking for the fan to be switched off. For example, you could type “I want the fan off now”.

+ Do the same for the “lamp on” and “lamp off” buckets.

--- /task ---

--- task ---
+ Continue to **Add example**s until you have at least **six** examples in **each** bucket.

Be imaginative! Try and think of lots of different ways to ask each command. For example: 

+ For “fan on”, you could complain that you’re too hot. 
+ For “fan off”, you could complain that it’s too breezy. 
+ For “lamp on”, you could complain that you can’t see. 
+ For “lamp off”, you could complain that it’s too bright.

![4 empty classes named fan_on, fan_off, lamp_on and lamp_off](images/full-buckets.png)

--- collapse ---
---
title: Tips for selecting good examples
---
+ **More is good**: the more examples you give your program, the better the program should get at recognising your commands. 

+ **Equal numbers**: add roughly the same number of examples for each command. If you have a lot of examples for one command and not the others, this can affect the way that the program learns to recognise commands. 

+ **Make the examples really different from each other**: try to come up with lots of different types of examples. For example, make sure that you include some long examples and some very short ones.

--- /collapse ---
--- /task ---

In the next step you will train your program to recognise any new command automatically by comparing it to the examples in the four buckets.
