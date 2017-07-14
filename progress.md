# [.tasproj files](https://mega.nz/#F!U3pV1QTJ!UaVEckaGbxKMvkNHss93Mg)

# [Complete run, v0.9](https://www.youtube.com/watch?v=Or5ShUZxYgc)

# Benchmarks
```
 47109 Sprohm
 62486 Lutia
 86299 Nubs
106317 Eluut
127497 Ulei
163020 Cadoan
198034 Aisen
(todo)
653404 Mewt!
```

# Things to fix/consider

- use B during world map cursor movement
- sell the Cuirass?
- scrap Human2, or replace with something else
- get Lini? needs 1 extra mission though, and he's also slow as shit
- **get a MNK instead of WAR**
- replace 1 Atmos Blade with Wizard Hat for Desert Peril
- Air Render for Desert Peril/Famfrit?
- get Montblanc JP faster?
- ~~**Telaq** (redo from place Eluut)~~
- does Scouring Time count as 2 battles? if so then didn't need to fail Friend Trouble. but that doesn't really matter (like, at all) because Marche can only switch to PAL after Scouring Time
- scrap Telaq Flower -> get Gastra instead?
- micromanage equipment?
- enemies that may require stat rigging and/or optimised Attack: Cadoan ILU, Magic Wood TIM, Hidden Vein ANM

# Intro, Snowball, Lizards

- followed FellVisage's run more or less
- unequipped armor
- changed MNK -> WAR
- fired viera, nu mou

## Shop 1
- Sprohm, since cursor already on it
- sold: all armor except Cuirass, all Shields, Bandage, Phoenix Down
- buy: 3 Shortswords, 3 Gauntlets
- i sell largest valued items (450 to 300) to minimise dialog with shopkeeper
- in particular i didn't sell cuirass because i wanted to avoid the dialog, but it bit me in the ass later because it always gets in the way during equipping.

- equipped Shortsword + Gauntlets

# 1. Herb Picking

- placed units in normal order
- mont doesn't do anything useful here
- was a rather easy fight - i doubt bringing 1-2 more units would speed it up
- ~~need 2 atmos blades on dueling sub AND thesis hunt, which is pretty hard, so i settled for 1; atmos on dueling wouldn't appear even after 60+ frames~~ at most 3 Atmos Blades are necessary
- did Dueling Sub and Human Wanted
- warrior: 103 Speed WAR; no white monks appeared within this time so i didn't try further - big mistake!
- human: 132 Speed NIN
- changed NIN->SLD, equipped Shortswords on new recruits

# 2. Thesis Hunt

- law is currently recommend fire; used it instead of Thunder for JP since the frame cost is low; this will be important for Totema later

WHT, ARC - easy OHKO (turn 1-2)
THF - 2HKO (
SLD - 3HKO

actual
```
>SLD2 move DL, wait, +2 frames to make THFA move to WAR1
THFA miss WAR1 (didn't need manip)
THFB will advance D (69800), R (69811)
>WAR1 fight THFA, crit, move DL to move closer to SLD
WHT almost always moves to THFB, but does nothing
ARC advance, miss SLD1
>SLD1 advance, let someone else kill THFA
>MAR crit SLDB, turn back/side makes him move AFTER fight, letting him hit makes him run away
SLDB almost always fight WAR1, didn't need manip
>MON KO [THFA]
>WAR2 crit SLDA 26
SLDB miss MAR, move behind MAR

>SLD2 cannot OHKO ARC, 
THFA miss SLD2 (didn't need manip)
WHT didn't do anything, miraculously
>WAR1 can't OHKO WHT, so KO [ARC]
>SLD1 takes 73 (!) frames to CKO WHT so i decided against it, 1 hit + mont later will kill anyway
>MON KO [WHT] + damage THFB
>WAR2 can't fight SLDA, else first aid, so crit THFB
>MAR CKO [SLDB]
SLDA miss SLD
>WAR1 fight SLD
THFB miss SLD
>WAR2 KO [THFB]
>SLD2 KO [SLDA]
```

satisfactory; just over 2 turns

- human1 and bangaa1 mastered first aid; forgot to consider dispatch AP
- 1 atmos is quite fast this time (4 frames), but i'm going to need 2 - doesn't help that i need to sit through the stupid dialog before i can check
- 2 atmos came faster than expected

## Shop 2

- bought 3 Silver Sword + 1 Jack Knife; Jack Knife is just a page below Silver Sword, conveniently

# 3. The Cheetahs

- Lightning banned on this day, not a big deal tho
- units reduced by 2, so left the new recruits behind (reaching new jobs is priority, and the first 2 have Gauntlets anyway)

actual
```
>RIT advance, CKO [THF]
>SHA fight, only 1 frame allowed crit, but it will make ARC use an ability, so i decided against it
ARC has a few patterns, seemingly dependent on how much damage SHA does
1. move 3 tiles (blocks path), fight MON <- this is best
2. move 4 tiles, fight WAR <- i thought this was best, but it later causes FGT to block MAR's path
3. Disable/Blind
-THF dead-
WAR fight ARC (don't crit, or will block MAR), wait 8 frames to make MNK fight
MNK fight RIT, wait 2 frames to make FGT fight
FGT can use Blitz, but this can be nanip'd during MNK
SLD can't reach anyone yet
MAR can't CKO ARC, leave it for MON
MON Fire, KO [ARC], wait 4 frames to make BLK fight RIT (lmao)
BLK fight RIT

RIT almost always fights MNK, so let her CKO; only 1 frame actually causes that, and it unfortunately makes SHA use Disable
SHA Disable BLK, didn't bother manip
WAR can't CKO FGT
SLD KO FGT, did a bit of judge manip
MAR KO BLK, just needed a bit of that damage fluctuation
```

- marche ended quite near ritz so this saved some frames
- just below 2 turns, quite satisfactory
- i don't think the clan can be manip'd to not spawn
- quest reward is generated on the frame you select Missions in the pub
- khukuri only took 2 frames

## Shop 3

- bought 2 Gauntlets; i presume i'm gonna need all the power i can get
- also 2 Silver Swords for later
- whether a clan is going to move cannot be manipulated. however, where it moves to can be. particularly, a clan going offscreen saves quite a few frames (~4).

# 4. Desert Peril

- montblanc simply cannot OHKO Flan without a Wizard Hat
- Speed requirements:
* Antlion > Marche, so that ANT can be reached on turn 1
* Montblanc > Flan, duh
- place 2 Silver Sword users (1 being MAR) on ANT side

actual
```
placed units in normal order, except mont (1 tile down)
SLD2 advance, but out of reach of panthers
COE, PAN advance
WAR1 advance
SLD1 crit PAN
ANT advance
MAR crit ANT
MON fire FLN (no KO)
WAR2 advance
FLN miss

SLD2 KO PAN
COE advance
WAR1 KO ANT
PAN miss SLD2
MON KO FLN
SLD1 crit PAN
WAR2 KO PAN
MAR wait

SLD2 wait
COE miss
WAR1 wait
2 crits, Thunder and 1 hit KO COE
```

2+ turns, blame the COE
areas for improvement: Air Render for COE? OHKO FLN with Magic Ring

- mont stil has only 4 JP. don't think i'm going to reach 10 by Diamond Rain without using laws. therefore here are my options: 

1. do diamond rain normally - most straightforward, but the battle may be difficult
2. farm JP at Famfrit with self-target Ice / Fire (Ice costs 6\*40=240 frames, but Fire costs in-game days)
3. farm JP at Cadoan with Ice / Fire
4. farm JP at Famfrit AND Cadoan (4 days apart) - 6 JP can likely be gotten naturally (3 each), but involves weird routing and costs in-game days

- i went ahead with 4

- just realised i should have bought 2 more Silver Swords when i bought the Gauntlets. so i redid the entire fight to test if reducing shop visits really saves time. it does. each additional visit costs about 4 secs.

- Sprohm -> Ulei in 8 days = Sprohm -> above Lutia -> right of Ulei -> Ulei

# 5. Famfrit

- dumbest, slowest fight in the game
- manip'd AHR to Roulette his allies most of the time; i think 2 Roulettes is the sweet spot. another one didn't seem necessary.
- did with 2 different tactics: surround and take counters / avoid counters by pushing famfrit around. the former turned out to be significantly (~6s) faster since moving around is so time-consuming. therefore, for all subsequent bosses, surround will be used over push where possible.
- used crits unless there was a level up to be optimised
- damage calcs are EXTREMELY important here. it is crucial to remember that calculated damage can only vary by at most +10%, and that damage rounds down, so if you're doing below 10 calculated damage, you won't benefit from the variance. doing 1 less damage can mean an extra turn.
- mont used Blizzard to gain 3 JP
- in terms of speed, 1st (surround) > 3rd (surround) > 2nd (push). will revisit the 1st run to see why it was so fast; it certainly didn't feel very fast

# 6. Antilaws

- laws changed, so i had to spend some days to get recommend Fire at Cadoan
- it was only HERE that i remembered you could hold B to speed up the world map cursor... shit. there goes like at least 50 frames.
- DEF is easiest to kill - a crit to the right, then down (with fall damage)
- FGT and GLD are probably 2-3HKO
- ILU should be OHKO from Marche, if not, reset
- the 2 enemies at the top are tricky to deal with quickly; send at least 2 units up (usually marche + bangaa1). though there is no fall damage, at least 1 of them should be knocked down so they can be more quickly killed by the units left at the middle section.
- mont reached 10 JP
- getting 2 Speed for Marche was incredibly tedious (78 frames), especially since he had the last turn

- due to a mistake in map placement, i was delayed telaq by 2 battles. i decided to go all the way back to desert peril to fix this mistake. however i did manage to save 800 frames, presumably due to slightly better tactics against COE. was really pissed that i had to redo, but i'm glad i did it in the end.
- i actually forgot to optimise a level up (a last turn one, no less) when i redid desert peril, but i went back to fix it relatively easy since i had spare frames while waiting for atmos. thank god for determinism! this fight is FINALLY done.

# 7. Diamond Rain

- failed 2 quests to upgrade shop now.
- changed FGT+GLD (Shadow)
- straightforward. Famfrit kills Flan, and 1 more Fight kills Bomb. Beatdown kills Lamia. The Dragons need 2-3 Beatdowns.

# 8. Hot Awakening

- Logos is VERY difficult to rig. trust me. ban Charm is important.

# 9. Magic Wood

- on turn 1, most important units to sleep are: SUM, BLK, THF (at least 1). the magic users AI is very aggressive.
- try to make sure TIM can be OHKO'd (i redid when GLD fell short by just 1 HP)

# 10. Emerald Keep

- can be done extremely quickly if sleep hits all. i don't think Babus ever fights, but Quarter is the fastest spell.

# 11. Adrammelech

- 2 Estreledge Beatdown (from now on referred to as EB) + 1 from Marche (may not be necessary if WAR has ~220 Attack) + sleep-all

# 12. Jagd Hunt

- BLU has Immunity
- sent WAR up to kill HUN and BLU, then come back down to EB the turtle
- Marche and Bangaa2 killed ASN and NIN
- Human1 dealt with ANT, later joined by Marche

# 13. The Bounty

- used Telaq for the first time
- strongly dependent on enemy formation
- BLK must be slower than Mont
- WAR must kill RED before she takes her turn
- FGT must be Beatdown'd twice with Atmos

# 14. Golden Clock

- would seem trivial, but there are a number of things that must be considered
- Shara should crit KO TIM
- Damage > MP must be nullified by Disable; it is still active during Sleep. then kill with EB.
- JGL must be killed by Shara and Ritz; Air Render does jack shit to it.
- Marche and Human deal with ALC

# 15. Scouring Time

- A very interesting fight. at this point, only WAR can OHKO (either with EB or crits), and the rest can barely 2HKO. so i decided to let WAR do all the work. this involved planning a good route around the map, and manipulating enemy movement with Marche and Montblanc. You'll notice I wasted one of WAR's turns because I couldn't manipulate the last 2 units properly. I was hoping they would come to Marche but this didn't happen.
- Babus is easily 3HKO'd (killing him saves time, obviously)
- 3 of the fruits take less damage than the rest, despite having the same defense.
- this helped Marche gain a bunch of levels to put him on par with WAR (after switching to PAL with SaveTheQueen)

# 16. The Big Find
- Shop upgraded. Bought Headbands, Power Sashes, Lohengrins (for Llednar) and Dash Boots.
- Got Tiptaptwo. It's immensely useful since Montblanc now becomes the 2nd fastest unit.
- Changed Marche + FGT to PAL with SaveTheQueen.
- with 5 Move, WAR is the only one who can reach the uppermost Bishop (and OHKO it) in 2 turns
- Sleep requirements are pretty relaxed here. Only both Bishops and 1 Fighter need to be hit. 1 Thief can be dealt with by PAL+FGT, the other is KO'd by WAR while he makes his way up. The other Fighter is easily OHKO'd by Marche.
- Marche finishes up the next Bishop, and PAL+FGT KO the next Fighter.
- I'm starting to wonder if I really need Bangaa 2...
- Discarding law cards is a tricky thing. I thought discarding 15 of them through Clan menu would be faster, but it actually takes about 1105 frames, while discarding after quests should take around 63 * 8 = 504 frames. Could trading with Ezel be faster?

# 17. Desert Patrol

- walked around a bit due to a bad law (I forget what it was though)
- DEF could not be OHKO'd with EB
- GLD was a bitch

# 18. Quiet Sands

- 1st fight is easily done by killing Marche; no crit needed
- I let the 2 dudes die since I don't use them anyway
- 3 Beatdowns + 1 fight kills Mateus

# 19. Materite Now

- used one strong Totema (WAR) and one average one (PAL); Totema damage is still determined by Attack
- technically I still have a still have an average one (Marche) and a weak one (FGT) left, but they didn't seem useful in any of the future battles
- 2nd Estreledge makes Bangaa2 finally worth using, though he's still average and slow as shit
- Human2 is more or less useless at this point

# 20. Present Day

- Easy OHKOs (2HKO for TEM); even Bangaa2 managed to OHKO ALC
- Rigged Llednar to Fight only. Maybe turning my back to him stops him from moving?

# 21. Hidden Vein

- wasted 2 days due to a bad law
- ANM stats were rigged to make him OHKO-able
- MNK will rarely fight, instead preferring abilities
- BLU kills self with Roulette
- I don't know why I brought FGT; he served no purpose whatsoever
- upper half is easily dealt with by Bangaa1 and Marche

# 22. To Ambervale

- by far the biggest waste of days; this last set of laws needs to be studied carefully
- FGT helps Coeurl become OHKO-able
- quite proud of how I killed the Lilith, though this came at the expense of giving the Dragon a turn

# 23. Over the Hill

- Techniques was banned, but crit+fall is both faster and funnier
- I suppose any unit with 5 Move would do, since I'm pretty sure the fall damage is enough to kill her (though it's never actually shown)
- Ritz and Shara have Ribbons

# 24. Royal Valley

- I let Marche die so NIN has nothing to do
- maybe could have reset so WAR would be faster than GUN? haven't checked if they have comparable Speed tho
- Llednar is easy EB OHKO
- Remedi and Li-Grim are kind of like Scouring Time all over again, with WAR doing all the work (both ~4HKO); WAR's damage is >4x that of anyone else, and I didn't feel like Beatdown animations were worth it if I was just doing like 30 damage
- Haste-all could come in handy here. I do wish I could've killed Remedi/Li-Grim before the minions woke up
