Download Link: https://assignmentchef.com/product/solved-cpsc-121-lab-7
<br>
Using Classes

The following program is going to revolve around creating and using the “Gladiator” class, which is included in your github repository. You must use that class definition in your project. In addition to writing a main function that uses the class correctly, you will also be responsible for defining 4 member functions of the gladiator class.

Write a program that performs the following:

<ol>

 <li>Tell the user that they are going to be hosting a fight! But first, we need to…</li>

 <li>Declare your gladiator objects. This will call the constructor, which is where you will assign stats and assign, or ask for, a name.

  <ol>

   <li>Max Health should be 150, 200, or 250</li>

   <li>Evasion and Crit should be two separate random values chosen from 5, 10, or</li>

  </ol></li>

</ol>

15%

<ol>

 <li>Minimum Damage should be in the range 8-14, with Damage Range in the range 16-22</li>

</ol>

<ol start="3">

 <li>Display the names and stats of both fighters to the user, and inform them that the fight will begin</li>

 <li>Your gladiators will alternatingly attack each other using the appropriate member functions (think about who is attacking, and who is taking *how much* damage)

  <ol>

   <li>Each attack should display info about damage and/or remaining health</li>

   <li>This will continue until a gladiator loses all their health</li>

  </ol></li>

 <li>Inform the user who was victorious. Ask if the user wants to run another fight (return to step 2) or not (end program)</li>

</ol>

Min_damage_roll = min(8) + rand() % range(6+1)

—Maximum Damage = Minimum Damage + Damage Range

—Min 30, range 50 would result in damage between 30-80

—To roll for a 10% chance, due to the % (per “cent” ie century) we will be taking rand() % 100 and comparing it to the chance, 10. If the random number generated is lower than the chance, an 8 for example, that’s considered a success.

—End of Chapter 8 slides contain more help with random numbers. Use srand properly (ie once)


