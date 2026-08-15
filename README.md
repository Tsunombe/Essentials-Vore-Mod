This is a vore mod for Pokemon Essentials 21.1

This is not a plugin, so make sure to read the guide for installation. This is also intended for game development instead of modding existing games, since there is a large amount of set up required.

DOWNLOAD -[Predmon mod 1.32 .zip](https://github.com/user-attachments/files/31104220/Predmon.mod.1.32.zip)







Guide - [Pokemon Vore Mod Guide.pdf](https://github.com/user-attachments/files/29044398/Pokemon.Vore.Mod.Guide.pdf)


![prey ability showcase](https://github.com/user-attachments/assets/34c461b7-4c5d-4512-8f48-f4d4816ea357)


Changelog

If using gen 9 plugin, go to settings and set restore items to false

Motherly brought back. deals fairy digestion damage with chance to attract (ignores genders)

Infatuated pokemon have a chance to massage instead of struggle when eaten

Added Battery Acid and Caustric Cauldron Abilities. Deal Electric/Poison digest damage with 20% chance to Paralyze or Poison prey if able to.

Added Gastric Grave Move. Deals 50 damage * number of total prey digested that battle.

Shiny chaining - digesting the same type of pokemon without breaking the chain increases odds of finding pokemon of that type as shiny. 1 reroll every pokemon of that type eaten. needs to be turned on in settings with SHINYVORECHAINS = 1

plays bgm ShinyHunt when in chain battles if a bgm called ShinyHunt is in the files.

fixed bug where having under 6 pokemon in your party, then getting 2 or more eggs from unbirth and adding them all to your party caused a crash

Added punctuation to some lines missing them.

Massage function code changed to allow it to be used when eaten if in the pokemon's base moveset.

Pokémon with unlosable items like megastones give them back to the player when digested.

Pokémon that become mega now will stay invisible if they are currently eaten.

Moves with function code including phrase "usableifeaten" can hit opponents using moves like fly or dive if the user is eaten

Poison types with black sludge equipped don't lose overworld weight, functions like leftovers

Having the "Player" character be eaten in perma-digest mode but game overs turned off, makes you auto lose the battle, but the player character isn't digested.

Ability Gutslut increases odds of encountering a pred in random encounters

Fixed issue where digestion text wouldn't play the correct dialogue

If a pred endoes a prey then falls asleep, the prey will be digested instead of healed until the pred wakes up.

Added simple function code for 2 form transformation pokemon. Eats target and transforms between forms. use function code TransformsUserEatTarget

Added snippet of example code in Battler_ChangeSelf.pbDigestPrey for how to add rewards to a pokemon for digesting certain prey like Arceus

Gut Punch rework. 1.5x damage if the target has eaten a prey, prevents use of vore moves by target for 2 turns

Protective ability reworked. endoed allies take half damage from attacks

fixed crash on checking pokemon indexes for indexes where no pokemon are set, usually during a 1v2 (doubles only)

Pokémon unbirthed or breast vored by the opponent no longer give eggs or milk on digestion

New flag "NoPerma" cannot be perma digested if owned by player

Hefty now scales directly with weight stages. 10% damage reduction per weight stage.

Fix for eattarget score calculations

Steps needed for a pokemon to lose weight now an option in Settings

New setting for the following pokemon to eat one of your party pokemon randomly. odds are set in settings. chance can be from 0 to 100

Endo Buffs

healing set to 1/4 per turn instead of 1/8

endo pred spits out endoed prey if they spent a turn eaten and are full hp. pred does not need a recovery turn after

Heals status of prey every turn

Massage now boosts a random stat by 2

Struggle now the ??? type

Gluttonous nerfed to only scale off the number of preds eaten without switching out.

Unbirth only gives egg if the player owns pred and doesn't own the prey

Motorboat now has correct odds of activating.

mod now supports mid battle dialogue with the following triggers with Deluxe Battle kit plugin. Are additional keywords that can be used. Opponent and player activates on their side's respective pokemon, pokemon devoured/digested activates for either side.
"PokemonDevoured"
"PlayerDevoured"
"OpponentDevoured"

"PokemonDigested"
"PlayerDigested"
"OpponentDigested"

ABILITIES

[BLISTERINGBELCH]
Description =  Lets out a belch of pure heat after digesting prey, causing harsh sun.

[SNOWYSPITTLE]
Description =  Lets out a large burp of snow after digesting prey, causing a snowstorm.

[SANDYSPITTLE]
Description =  Lets out a large burp of sand after digesting prey, causing a sandstorm.

[STORMYSPITTLE]
Description =  Lets out a large wet burp after digesting prey, causing a rain storm.

[LADYKILLER]
Description =  Deals more damage to female prey.

[MANEATER]
Description =  Deals more damage to male prey.

[FATTYFOOD]
Description =  Boosts pred's weight up massively and heavily lowers their speed when digested.

[ASSIMILATE]
Description =  Transforms into their prey after digestion

[ASSETTHIEF]
Description =  Takes on the typing of a prey it digests.

[KLEPTO]
Description =  Burps up and equips items of prey on eating them.

[SELFPRESERVATION]
Description =  Digests an endoed ally to save themself when low hp.

[CLUMSY]
Description =  Chance to trip on a random Pokemon on miss.

[PROTEINBOOST]
Description =  Burns off weight to increase punching power.

[SADIST]
Name = Sadist
Description =  Bonus accuracy and eat chance for vore moves on debuffed prey.

MOVES

[GASTRICGRAVE]
Description = Move’s power increases with each pokemon digested this battle.

[PARASITISM]
Description = The user's HP is restored by half the damage taken by the target. Usable when eaten.

[WRITHE]
Description = The user's thrashes around with chance to flinch. Usable with priority when eaten.

[CANDYBEAM]
Description = The user turns the target into candy for them to swallow.

[HYPNOTIZE]
Description = Hypnotizes target into wanting to be eaten. Changes their ability to Gutslut.

[POUNCEANDPILFER]
Description = The user pounces on their prey, eating them and burping up their item to equip.

[SNACKBREAK]
Description = The user takes a snack break to recover it's or ally's hp 16% 2-5 times.

[RAMPAGE]
Description = The user rampages and eats all in it's path for two to three turns. User is confused after.

[COCKSLAP]
Description = The user slaps foe with their hard cock. High critical hit and CV chance.

[CLIMAX]
Description = The user masturbates with their prey, causing infatuation. fails if not CV or UB.




