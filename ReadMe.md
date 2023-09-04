# Hideous-Wanderer
Hideous Wanderer is a mod for Wolfenstein3D, specifically the sourceport LZWolf, based on the mod for Doom of a similar name, Hideous Destructor.

It aims to make the game a little bit tac-shootery. It gives weapons a more real-world accurate feel, including more realistic firerate and damage, and adding reloading.

### Table of Contents:
Feature Guide - https://github.com/Beelzebold/Hideous-Wanderer/blob/main/ReadMe.md#feature-guide-for-hwand
#### I. WEAPONS - https://github.com/Beelzebold/Hideous-Wanderer/blob/main/ReadMe.md#i-weapons
#### II. ENEMIES - https://github.com/Beelzebold/Hideous-Wanderer/blob/main/ReadMe.md#ii-enemies
#### III. GETTING SHOT AND NOT DYING - https://github.com/Beelzebold/Hideous-Wanderer/blob/main/ReadMe.md#iii-getting-shot

Known Issues - https://github.com/Beelzebold/Hideous-Wanderer/blob/main/ReadMe.md#known-issues-as-of-hideous-wanderer-beta03

## FEATURE GUIDE for HWand

###  I. WEAPONS
You start with the Knife and the Pistol.

#### ---KNIFE---
A simple knife. It has your loose rounds ammo counter.
Fire to stab. It's more powerful than the standard Wolf3D knife. 

#### ---PISTOL---
The standard issue pistol. It's a Browning Hi-Power handgun. Luckily the mags for it are really hard to accidentally drop and really fast to reload.
Fire to shoot. Altfire to reload.

On top of that, there are a few weapons that you'll find around.

#### ---SMG---
A fully suppressed MP-40 "Maschinen-Pistole" (sub-machine gun). Fully suppressed, fully automatic, fully inaccurate. Less accurate than the pistol, but it has a large mag capacity and deals more damage per shot. On top of that, if you can manage to stealth kill your target, it might not alert anybody.
Fire to shoot, altfire to reload.

#### ---CHAINGUN---
The ultimate swiss cheesifying tool. It fires incredibly fast, and deals a fuck-ton of damage per round, but absolutely guzzles ammo. It's capable of killing heavily armored soldiers incredibly quickly.
Fire to shoot, altfire to reload.



### II. Enemies
Along your journies, you will meet many nazi scumbags who would love nothing more than to be able to jumpstart your tonsils or turn your balls inside out without puncturing them or creating sharp bends or creases. They range from the simplest of guards to the highly experienced elites.

#### -=Guard=-
A standard castle patrol guard. Hobbies include petting the dogs and popping holes through spies. They're slow to draw as well as having a measly 20 health. They drop a single magazine.

#### -=Guard Dog=-
A vicious dog. Would love nothing more than to chew your testicles off and spit them into your eyes, because theirs got cut off by an SS vet. Really fast, kill on sight.

#### -=Schutzstafell=-
A high ranking SS Officer. These guys are heavily armored and react quickly. Know them by their war cry. At least when you wipe them off of the floor you can snag their sick sub-machine-gun.

#### -=Mutant=-
A dead allied soldier brought back to unlife by the nefarious Dr. Schabbs with the help of Otto Giftmacher, a chemical specialist. These guys react 5 seconds before they even notice you, and immediately punch 2 holes through you with the pistol grafted to their chest, while slicing and dicing in close range. If you hear one, run toward cover, there could be more. They don't even drop much. Sheesh.

#### -=Elite Guard=-
The best of the best that the nazi forces have to offer. They're incredibly quick to fire, and could pop a fly off the wall at 40 yards. Know their presence when they call to you, spy. And don't count on that pistol. They take several shots with it to kill, and they usually come in pairs or trios. Try to get something better. Either react faster than them, or keep your distance and try your luck with your aim.

### II. a. Bosses
There are plenty of high ranking nazis who would like to add one of your eyes to their collection of war trophies. Here's a vague description of all of them.

#### -=Hans Grosse=-
A high ranked guard who stands over the entrance (and exit) to Castle Wolfenstein. He wields two chainguns and is heavily armored. He has supreme command over all guards in the castle.

#### -=Dr. Schabbs=-
A nazi doctor who experiments on allied soldiers for fun. We've heard rumors that he's been collaborating with the nazi chemist Otto Giftmacher to create some undead super-soldiers. Hitler was worried allied soldiers, who don't have the traits he so prizes, would be less effective, but Schabbs assures him that it's better than experimenting on their own. These soldiers follow his every command and lurk in every shadow. He could call forth an army at any time.

#### -=Hitler=-
The nazi mastermind Hitler himself. He battles wielding four chainguns, yes, FOUR, and wears a mech-suit into the fray. Two of the chainguns have Flammenwerfers attached to them. He commands and mobilizes all nazi officers and rules over the elite.

### III. Getting Shot
#### And not dying!

When you are shot, there's a pretty good chance you'll be wounded. If this happens, you won't recover as fast, or as fully. Aside from just resting about for awhile, you can recover health by eating meals (or dog food in a pinch) or by patching your wounds by picking up a medikit. If you get injured too badly, the blood loss may begin to drain your health to a certain point, so keep an eye on that stuff.

You can also pick up armor from fallen foes to grant your self a little bit of extra protection. This does nothing to prevent or stop wounds or blood loss though, so always be on the lookout for medikits.

On higher skill levels, you may find yourself losing 70-80 health to a single shot, so on skill levels higher than Bring 'Em On, it's extra important to keep an eye on your HP.

## KNOWN ISSUES as of HIDEOUS WANDERER BETA04

### =-=Crashes=-=

1. When reloading from empty, if you pick up a mag during the reload sequence,
the game hard-crashes. (I believe that this was just the second one that I
diagnosed wrong. fixed.)

2. If you reload from empty but don't have anything to put into the gun, the
game crashes for some reason. Note that this is rather inconsistent. (fixed as
of migrating to LZWolf)

3. Sometimes grabbing extra lives (looks like it happens while reloading?) will
crash the game.

4. Save games currently don't work well at all, commonly crashing the game
whenever dealing with savegames that last longer than a single level.

WARNING:
RELOADING FROM EMPTY IN GENERAL IS VERY BUGGY. I WOULD NOT RECOMMEND THAT YOU 
LET YOUR GUNS HIT EMPTY, AND BY NO MEANS SHOULD YOU RELOAD WITHOUT ANY BULLETS
IN YOUR INVENTORY. IT IS ALSO EVEN BUGGIER WHEN YOU TRY TO CHEAT IN GOODIES.

NOTE: The previous two bugs have not been confirmed for the Chaingun.


### =-=General Bugs=-=

1. The SMG has no pickup sprite. (fixed)

2. If you run out of loose bullets or pick up too many, the ammo counter 
(displayed on the knife) will disappear. (fixed)
