# Palmic Hunger, Thirst, Sleep and Radiation adjustment
## Anomaly 1.5.1 optimized

_This is Addon for S.T.A.L.K.E.R. Anomaly, go find "Stalker Anomaly addons" if you don't know what i am talking about_


This Anomaly Addon is my adjustment of needs in game.
Basic idea is that in reality, you really don't start to lose any Health after several hours without water or food.
Actually it's quite opposite, after few days without water, your natural healing goes through the roof.
However this is not implemented here.

Only motivation for this mod was to balance Anomaly to not to have to haul gallons of water to longer trip, or to need to drink liters of water every few hours like some twisted aquaholic.
I also wanted to scale hunger and thirst a little differently.

## Thirst
At thirst level 1 (gray icon) you will slowly lose stamina from point where you will not even recognize it, however as your thirst go further, stamina los is higher.
Once red icon of thirst will appear, you will start to lose health.
99% of this mechanic is already in Arzi's Radiation Overhaul, however it's tuned up differently.
I just changed configuration of his mod here - all credits to Arzi for his great mod!

### If you are not moving:
* Gray icon should show after about 24 hours ingame time from full hydration, this is what i ment by different scaling - gray icon now means dehydration feeling. Thats the feeling which you maybe had as child when you returned from whole summer afternoon playing football with no water. This is not state which will lower your health, but it's still unpleasant because it lowers stamina.
* Yellow icon is the same, just more intensive
* Red icon means you are severely dehydrated, now you are also starting to lose health. But this state should not appear sooner than after 2 days without water.

### If you are moving however, situation is different:
* By walking, next thirst level will appear 2.3x sooner (grey from full hydration about 10,5 hour of walk)
* By running or sprinting (there is no difference now), next thirst level will appear 5x sooner (grey from full hydration in 6 hour of running)

So now, you are drinking to not to feel dehydrated and lose any stamina benefit. If you will get lost at trip, you can dehydrate enough to start to lose health, however, its not so often now.
Basically 1,5L of water should be enough to hydrate for a day now, if you will not be running too much.
You will still have to drink after dehydrating meds and food.

## Hunger
Hunger is Anomaly mechanic and i was not digging deep enough to find how it works deeply, so i just slower it down similarly as thirst by config.
Thirst should knock on your door always quicker.

## Sleep
Sleep is now just about 20% more rewarding, than with immersive sleep.

## Radiation
This mod is based on Arzis' Radiation overhaul (which is also requirement - see installation).
I just felt Arzis radiation is sometimes too deadly at beginning (especially with Black road mod, which i like). It is still deadly, just no so much now.
So with this mod, radiation satiation damage is about 2x lower and health damage about 3x lower (player will die with full irradiation in ~120 ingame hours).
Don't forget to bring Geiger counter with you as you can, because you will not know about radiation without it with Arzis radiation overhaul mod!

### Why i built this mod on Arzis radiation?
Thirst was implemented into Anomaly by Arzi in his thirst mod, however it's not optimized on Anomaly 1.5. Arzi never updated it because he implemented thirst as part of his radiation overhaul mod.
This is the reason why i built upon it and if you would ask me, i like this radiation overhaul mod, i just needed to nerfe radiation sickness a little.

## Changelog:
You can see changelog here: https://github.com/palmic/palmic-thirst-hunger-sleep-adjustment/commits/main
There you can get idea about how to adjust it on your own and see what exactly was changed and why.

## How to install it:

### 1. You will need to install these dependencies:
1. https://www.moddb.com/mods/stalker-anomaly/addons/immersive-sleep
2. https://www.moddb.com/mods/stalker-anomaly/addons/100-groks-body-health-system-redux-for-151
3. https://www.moddb.com/mods/stalker-anomaly/addons/arszis-dynamic-radiation-zones-and-radiation-overhaul
4. https://www.moddb.com/mods/stalker-anomaly/addons/immersive-sleep-compatibility-with-arszi-radiation-and-count-your-rounds

### 2. (optional) recommended
1. https://www.moddb.com/mods/stalker-anomaly/addons/hunger-thirst-sleepiness-bars
   * with this, you will see your hunger, thirst, sleep in health state in inventory

### Why all this?
About Arzis Radiation Overhaul i already written above and others were simply mods which i will be always using, so its not tested without them.
If you will like, you can test it on your own with your mods setup, i don't guarantee anything anyway, this is simply how i like it.

### 3. Then download this mod by green "Code" button here at top ^^

### 4. Install all of them in this order:
Always put these mods as last to be sure, it will work and always follow this order:

![mods order](https://github.com/palmic/palmic-thirst-hunger-sleep-adjustment/blob/main/adr_palmic_tunning.png?raw=true)

### 5. Start your game and enjoy!

## Recomendation about modding
I am strongly recommending to use Mod organiser over JSGME.
The advantage is not just about that MO2 is not changing your anomaly dir and put mods "into game" just in memory when you run the game, so you can very easily drag drop order just in MO2 interface, but also because MO2 will show you additional info about mods, like what they are rewriting between each other.
Based on this you can simply fix any issue because you will realise thanks to that, what rewrites which config file:
![MO2](https://github.com/palmic/palmic-thirst-hunger-sleep-adjustment/blob/main/adr_palmic_tunning_deps.png?raw=true)
when you mark one mod, it will show you what overwrites his files and other way. Here i marked Grocks Body Health System Redux in middle. Red mods overwrite his files, Green ones are mods with files overwritten by him.


![MO2](https://github.com/palmic/palmic-thirst-hunger-sleep-adjustment/blob/main/adr_palmic_tunning_deps2.png?raw=true)
By showing mod info (right click -> information) it will show you details about conflicting files.


For more info see this great tutorial: https://www.youtube.com/watch?v=ghXyVPiG0uo
