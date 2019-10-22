## Add a list of rules

In this step, you will edit the project to include a list of rules to activate and de-activate the fan and the lamp.

\--- task \---
+ Click the **classroom** sprite to select it, as shown below:

![Scratch template project](images/scratch-template-annotated.png)

+ Click on the **Scripts** tab and create the following script:

```blocks3
when green flag clicked
forever
ask [Enter your command] and wait
if <(answer) = [Turn on the fan]> then
broadcast (turn-fan-on v)
end
if <(answer) = [Turn off the fan]> then
broadcast (turn-fan-off v)
end
if <(answer) = [Turn on the lamp]> then
broadcast (turn-lamp-on v)
end
if <(answer) = [Turn off the lamp]> then
broadcast (turn-lamp-off v)
end
end
```

+ Click on **File** and then on **Save to your computer**, and save the program to a file. \--- /task \---

\--- task \---

+ Click on the **green flag** to test your program.

![Scratch interface just after green flag is clicked](images/click-flag-annotated.png)

+ Type in a command and watch the program react! The following commands should all work:
    * “Turn on the lamp”
    * “Turn off the lamp”
    * “Turn on the fan”
    * “Turn off the fan”

* Type in anything else, and your program does nothing! Even if you make a small spelling mistake, the program does not react.

\--- /task \---

You’re telling your virtual classroom assistant to react to commands using a simple rules-based approach. But if you wanted your program to understand commands that are phrased differently, you would need to add extra `if` blocks.

The problem with this rules-based approach is that you need to exactly predict all the commands the smart classroom assistant will get. Listing every possible command would take a very, very long time.

Next, you will try a better approach: teaching the computer to recognise commands by itself.