# Zombie-Barney-Half-Life-



I added on the zombie codes the ability to drop supply when killed with over 9 options. The idea came to my mind thanks to a HL demo mod called "Crowbar Deep in The Dead".

The code also comes with an additional thing, choosing what faction the zombie will join on spawn.



3 things to make the code:

1_Defining ( line 47) 

2_Spawn Function ( line 317 - 369)

3_Killed Function ( line 485)



"Drop Supply" codes in "FGD":

{
 weapons(Choices) : "Drop Supply" : 0 =
  [
    0  : "Random"
    1  : "Handgun"
    2  : "9mmClip - Ammo"
    3  : "None1"
    4  : "Python"
    5  : "Desert Eagle"
    6  : "None2"
    7  : "357 - Ammo"
    8  : "Buckshot - Ammo"
    9  : "None3"
    10 : "MP5Clip - Ammo"
  ]
}




Change Teams in "FGD":

{
team(choices) : "Team Faction" : 0 =
	[
                0 : "Zombie (Xen Alien)"
                1 : "Race X"
                2 : "Friendly"
                3 : "None"
	]
}

I hope you like it!
