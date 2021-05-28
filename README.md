# RWBYScripts
 A series of small utilities for RWBY Game on Roll20.

## Roll20 Roll Dice Script:
This project is intended to generate a string to make a custom roll output that you can post in the chat of Roll 20. An example of a roll in Roll20 looks like the following: \(taken directly from Roll20 examples shown in game, modified slightly\) 
    * /roll 2d10 or /r 2d10
        * this rolls 2d10 and sums them
    * /gmroll 2d6>5 or /gr 2d6>5
        * this secretly rolls the GM and checks to see if any d6 is greater than 5, reporting on the number of dice that are greater than 5, but not their sum total.
### Roll20 Chat and Dice Syntax References:
Found a number of references and have placed them here for ease of reference. If any of these prove to be poor references, let me know by posting a bugfix.
    * [Chat Commands](https://wiki.roll20.net/Complete_Guide_to_Macros_%26_Rolls#Chat_Commands) 
    * [Dice Reference](https://help.roll20.net/hc/en-us/articles/360037773133-Dice-Reference)
    * [Dice Reference \(old version\)](https://wiki.roll20.net/Complete_Guide_to_Macros_%26_Rolls#Dice_Syntax)

### Tasks: 
- [ ] create a string that generates a basic roll \(eg: /r 2d10 \)
- [ ] create a radio button for type of attack \(range or melee\) 
- [ ] create a list of things that could modify that roll \(ex: ROC would add another d10, AGI might affect to hit at range, etc.\)
- [ ] create a set of checkboxes/radiobuttons/selects that would store the values of those modifications
- [ ] create a comparison to add to the total of the string to show success or failure against a Grimm Defense value \(rather than individual dice comparison like above\)
- [ ] create function and call to function for output of string to page. The output could be in a specified div or even the alert or other 'popup like element'

## RWBY Action Sequence tracker:
This is designed to help players track what actions they chose so they can create compelling descriptions of their actions in game. There should be a drag and drop so they can place their actions in order.

### Tasks: 
- [ ] create HTML elements to store minor and major actions 
- [ ] create options within to show what you are doing based on type of action \(ex: moving, semblance, attack, etc.\)
- [ ] create sortable functionality, so actions are able to be placed in order.
- [ ] create a method that checks the type of actions so that nobody takes more than two major actions in a sequence.
- [ ] create an extra action reference that when chosen tells the players what they need to do \(ex: charge action \)

### Task Expansion Ideas:
    1. Create a dictionary of adjectives and actions to create a possible scripted narrative sequence for players to speak during play based on the choices and order above.
    2. Create a means for the party to be able to share their actions in real time so that they can be combined together. This may require a db, possibly Firebase. More research is needed on this idea.

## Any additional ideas, please post in the features.



