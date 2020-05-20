# Odyssey-of-the-Dragonlords-GGMM-Creatures
A collection of creatures made for the D&amp;D 5e adventure Odyssey of the Dragonlords, using GiffyGlyph's Monster Maker.

## Using GiffyGlyph's Monster Maker

GiffyGlyph's Monster Maker is a set of rules for creating creatures in 5e that are meant to present a wider array of combat options and more engaging boss fights. The most recent version of this ruleset as of this writing can be found at https://drive.google.com/file/d/1DTdevsM641DQRA2sI1f6w1aPpFmlLIiM/view. I strongly recommend reading over this before using any of the creatures presented here, since most or all of them use mechanics that are unique to this module (which I will be referring to from here onwards as "GGMM"). You can easily create your own creatures using the GGMM app here: http://www.giffyglyph.com/monstermaker/app/

## Downloading and Reading the Files

The files in this repo are .json files. What this means is that you can download the file, go to the GGMM app linked above, navigate to the Vault tab, and click on the gear in the bottom-right corner. From the menu that appears, select "Import Monsters from .json", and upload the file. You should then have a copy of the monster's stat block, available for you to view and edit.

This readme file also contains my commentary on some of these creatures, and I recommend reading this before running these creatures in your own adventures.

## Commentary

These creatures are presented as .json files to be used in the GGMM app. These stat blocks, unless stated otherwise, do not have accurate values for their ability scores, saving throws, movement speeds, senses, or languages. These are instead taken from the creatures that these stat blocks are meant to convert.

A quick aside - I've given each of these creatures a name of the format "\[name\], \[title\]", so that my players know what to expect when they see that format. I've also for the most part tried to match the level of a creature to its CR in the adventure, but I take some liberties with this in some cases.

I've also used the shorthand "\[amount\] ongoing \[type\] damage" to mean "At the start of each of the target's turns, it takes \[amount\] \[type\] damage", and "(save ends)" to mean "the target can repeat this saving throw at the end of each of its turns, ending the effect on a success".

Lastly, note that these creatures were all designed to face a party of 5 PCs. If your group has a different number of PCs, adjust the creature's stats accordingly, using the GGMM rules (I believe this just requires adjusting the hp to match the party size - e.g. for a party of 4, multiply all bosses' max hp by 4/5).

### Ventis, the Tyrant

This was the first GGMM boss I threw at my party. I converted Ventis (originally a copper dragon) to a white dragon, primarily because I'd found some cool artwork for a white dragon and wanted an excuse to use it. In his first phase, Ventis is a Striker, making reckless attacks and prioritizing enemies who have recently dealt damage to him, and using his breath weapon as a devastating AoE attack. In his second phase, Ventis uses his breath weapon to enhance his scales with icy armor, becoming a Defender that tries to wear down his already-weak enemies and simply outlast them. He uses the last of his breath weapon to freeze the most-threatening enemy in place, turning the fight into a struggle for survival on both sides.

Ventis went fairly well for my first GGMM boss. The only major change I would make would be to have used Icy Tomb much sooner than I did in the fight, and maybe give him something else to do in phase 2 other than his basic attacks - maybe an attack that deals less damage but inflicts ongoing damage from frostbite.

### Hexia, the Traitor

This boss was built around supporting a mind-controlled Pythor. The first phase consists of Hexia playing support for Pythor, staying behind him and using her Commander trait to force him to attack the party (he otherwise refuses to attack, being too charmed to fight Hexia and too strong-willed to attack the party without direct control). The second phase is meant to be a shift in tactics, where she begins attacking the party directly, using a multitude of debilitating conditions to harry them while trying to finish them off. At this point, Pythor should be either unconscious or freed of the charm.

This fight was one of several that went sideways, not necessarily in a bad way, just in a way that resulted in a very unorthodox battle. One of the PCs had a feature that allowed them to remove charms (among other conditions), and the larger battle pivoted around a fight between this PC and Hexia for control of Pythor. Ultimately, the group ended up being able to maintain control of Pythor for the majority of the fight, which made it a lot easier than I had intended it to be, but I feel it was still a satisfying and unique encounter.

### Helios, the Rising Sun

This boss was probably my biggest mistake using GGMM. My original plan was to try something different for a dragon with this boss - give it a breath weapon without a cooldown condition, so it can spam it as much as it wants. Then I came up with the idea of instead giving it two breath weapons - a recharging fire breath, and an at-will radiant beam, the latter being a big part of why the dragon was once worshipped as a sun god. However, I failed to correct the damage for the fire breath, and for some reason had greatly reduced the base damage, so it ended up being severely underwhelming, aside from the blinding presence replacing frightening presence.

Overall, I think this boss was not a bad concept, being a gold dragon that can generate a seemingly-endless amount of fire and light between Immolate, Brilliant Beam, and Fire Breath. It just needs the damage to be correctly updated - below are some suggestions for changes that would fix this:

- Claw: damage becomes 2d6+3 slashing
- Immolate: damage becomes 15 ongoing fire damage
- Fire Breath: damage becomes 6d10 fire damage

### Diomedes, King of Eons

This boss was easily harder than any my party had fought before it, GGMM or otherwise. This androsphinx started the fight by laying into the party with claw attacks, and messing with them by teleporting them around (dealing force damage with this via telefrag) and plaguing them with traumatic flashbacks (leading to some fun RP material). Diomedes teleported the party to the Far Realm to fight grells after Phase 1 ended, resuming the fight in Phase 2 once they returned. By the end of Phase 3, the party was nearly dead, and completely depleted of resources. Note that my party was greatly helped by the fact that our warlock (the primary spellcaster in the group) had obtained a Rod of Absorption, and was able to negate Diomedes' Counterspell.

My original plan for Diomedes was actually even harder than this - it had a second reaction, and a 1/day ability that it would only use in Phase 3. If you want to make this boss even more brutal than it already is, consider adding the following features, which borrow mechanics from the lesser sphinxes introduced in the adventure.

- Time Loop (1/day) (Phase 3 Only): A creature within 120' of the sphinx must make a DC 17 CHA save or become trapped in a time loop (save ends). While trapped in the time loop, the target takes 20 psychic damage at the start of its turn, it makes attack rolls with disadvantage, and at the end of its turn it teleports to the space it was in at the start of its turn.

- Rewind (Reaction) (Phase 3 Only): Diomedes forces a creature not afflicted by his Time Loop ability to repeat an action it just performed, undoing the results of the action before making it repeat the attempted action.

### Hezzebal, the Forgotten

This boss was about as brutal as the one before it. As a high-level Striker, Hezzebal had incredible amounts of damage, and repeatedly downed party members, even killing one PC (she got better). I made the executive decision to shut off his damaging aura after he first used Necrotic Surge, since it was absurdly punishing to the melee characters in the party, and didn't present any engaging counterplay. I'd recommend you similarly remove this feature if you use this creature in your own game.

### Lutheria, the Empress / Lutheria, Lady of Dreams

Lutheria was a fairly brutal fight, but for very different reasons than the other bosses were. As our party had a Doomed One in it (a role in the adventure, one of which each player chose for their character), Lutheria spent the fight focusing all of her attacks on this character, and the battle became a sort of escort mission, with the party doing their utmost to defend the poor monk while trying to defeat the titan empress. The party also had an opportunity to burn her uses of Inspiration in a game of chance against her, meaning that she did not have full access to this resource during the fight.

Lutheria's first phase is a Striker, using her Emerald Scythe and her Blight spell to deal massive damage to the party, and occasionally using Madness or Hideous Laughter to try and weaken the most effective attackers. However, my party had fairly good success with saving throws, and were able to negate most of these attempts.

The titan's second phase is a Scout, dancing about the battlefield while her scythe hovers above, waiting to descend. I ended up changing the ability Curtain Call in particular to be Cooldown 3, instead of Recharge 5/6, so that the party knows exactly when it will strike next, and have to rush Lutheria down before it does. In the meantime, the goddess attacks by using Maddening Touch, Lullaby, and Invitation to Dance, relying on her scythe's Curtain Call as her primary source of damage.

In her third and final phase, Lutheria initially appears dead, but has actually turned invisible and begun the final stage of her attack. Her scythe destroyed, Lutheria relies wholly on her powers of madness and nightmares to destroy the party. She alternates between turning invisible, and using one of her attacks or spells - spreading blindness via Blinding Darkness, striking with her horrific claws, or using Nightmare Unleashed to show the party her true form.

This last phase ended up being slightly weaker than I'd intended, as a Lurker that has to waste every other action turning invisible without moving. I feel like this might've gone a bit better if she had been able to move as part of her Vanish action, or even remained constantly invisible throughout the fight, this phase might've been more climactic. However, as it is, I think this fight was still really tense and satisfying overall.

### Talieus, Son of Sydon

This boss and the next felt a little underwhelming. Talieus is a skilled smith, and wears a suit of magical armor, wielding a powerful hammer in combat. I gave him a few spells, loosely basing him on the Young Empyrean stat block provided in the adventure. This is also when I started experimenting with bosses that use spellcasting as part of their multiattack, to create hybrid casters that can use weapons and spellcraft to fight the party. Talieus is also capable of using a powerful Storm Rune, which expels his hammer's magic in two ways - a wave of thunder that strikes everyone near him, and bolts of lightning that strike distant targets as well. 

Overall, this boss felt somewhat underwhelming, but I suppose that was to be expected of its lower level (relative to previous bosses) and the fact that it was fought right after dealing with a trio of young dragons. This boss served well as a testing ground for hybrid spell/weapon boss mechanics.

### Chalcia, Favorite of Sydon

This boss also felt a tad disappointing to run, but worked out fine otherwise. Chalcia wields the Starmetal Solar Axe, which is from the Griffon's Saddlebag. Its stats as a magic weapon can be found here: https://www.reddit.com/r/TheGriffonsSaddlebag/comments/dnug7x/the_griffons_saddlebag_starmetal_solar_axe_weapon/

Chalcia fights by transforming the axe back and forth between a greataxe and two handaxes, and using her Smite spells with her Paragon Actions in order to empower her future attacks. I tried to balance this by making the Smite spells empower her next successful attack by an amount comparable to her intended damage per action - about half her damage value, plus a rider effect that makes the Smite useful beyond being a simple damage increase.

I think Chalcia ended up being a pretty balanced boss for her level, the issue is that she was fought right after facing Sydon's first two phases, so she felt if anything like a respite from that boss's damage output and insane defenses. Making her a Striker instead of a Scout might have been a more effective way to make her feel like a genuine threat after facing Sydon.

### Icarus, the King's Dragon

This boss was rather fun to play, although I feel I may have mishandled the twist at the end of this fight. Icarus is presented here as a really simple boss fight, little different from the default stat block for an ancient silver dragon, save for having the Reckless and Rampage traits.

The main gimmick of this boss is the fact that Icarus gains a level of exhaustion at the start of each of his turns (not represented in the stat block), eventually dying due to this. When I ran Icarus, I had the third level of exhaustion cause him to lose 720 max health and current health, but this resulted in him being left with so little hp that he was eliminated in a couple more attacks - barely giving him time to change from attacking the party to begging for help, as I had intended for him to do. If I were to run this again, I'd instead leave the boss's current health untouched, reducing it only if it was above 720 before reaching three levels of exhaustion.
