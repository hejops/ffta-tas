# [.tasproj files](https://mega.nz/#F!U3pV1QTJ!UaVEckaGbxKMvkNHss93Mg)

# Benchmarks
```
 47109 Sprohm
 62486 Lutia
 86299 Nubs
106317 Eluut
127497 Ulei
163020 Cadoan
198034 Aisen
```

# Things to fix/consider

- use B during cursor movement
- get a MNK instead of WAR
- Magic Ring/Air Render for Desert Peril?
- Air Render for Famfrit?
- get Montblanc JP faster?
- ~~**Telaq** (redo from place Eluut)~~
- does Scouring Time count as 2 battles? if so then didn't need to fail Friend Trouble. but that doesn't really matter (like, at all) because Marche can only switch to PAL after Scouring Time
- discard law cards before Big Find

# Intro, Snowball, Lizards
followed FellVisage's run more or less

- unequipped armor
- changed monk -> warrior
- fired viera, nu mou

## Shop 1
- Sprohm, since cursor already on it
- sold: all armor except Cuirass, all Shields, Bandage, Phoenix Down
- buy: 3 Shortswords, 3 Gauntlets
- i sell largest valued items (450 to 300) to minimise dialog with shopkeeper
- in particular i didn't sell cuirass because i wanted to avoid the dialog, but it bit me in the ass later because it always gets in the way during equipping.

- equipped Shortsword + Gauntlets

# 1. Herb Picking

placed units in normal order
bangaa1 OHKO'd fairy (cost 4 frames)
bangaa1 can crit redcap, but would cost 70 frames! (56935)
mont doesn't do anything useful
human1 crit only took about 20 frames, fortunately
marche crit only took 2 frames lmao

test from 58511; marche KO'd 2nd last enemy -> final input of battle; should marche move? YES
(i think goblin will always head for human1)
don't move, kill next turn - 60335
move 1 tile (don't block human1), let human1 kill - 60219

was a rather easy fight - i doubt bringing 1-2 more units would speed it up
got corpse shifted tho >:(

need 2 atmos blades on dueling sub AND thesis hunt, which is pretty hard, so i settled for 1; atmos on dueling wouldn't appear even after 60+ frames [area for improvement, tho idk how much better 1 more atmos'd be]

```
warrior
64060 - 1st allowed finish
64064 - 113/100
64081 - 114/101
64083 - 111/103 ! <- went with this dude
64093 - 116/101 !
64105 - 113/100
```
no white monks appeared within this time so i didn't try further

human (1st attempt)
```
64703 - 88/113 - ARC, 1st allowed finish
64705 - 99/107 - BLU
64707 - 100/106 - BLU
64708 - 105/104 - BLU
64710 - 105/132 - NIN !!! <- duh
64711 - 110/125 - HUN
64713 - 115/115 - FGT
64714 - 109/119 - HUN
64715 - 113/117 - HUN
64716 - 111/111 - SLD
64717 - 102/103 - PAL
64718 - 108/110 - SLD
64719 - 114/113 - FGT
64720 - 105/126 - NIN
```

human (2nd attempt; had to redo since i forgot an extra button press on warrior)
```
64644 - 92/120 - ARC, 1st allowed finish
64652 - 105/125 - NIN
64677 - 109/129 - NIN
64680 - 104/136 - NIN !!! <- even better, still earlier overall
```

human (3rd attempt; forgot to buy quest before going to lutia)
- 132 Speed on 1st frame lmao

changed NIN->SLD, equipped Shortswords

# 2. Thesis Hunt

law is currently recommend fire; will probably use it instead of Thunder for JP since the frame cost is low

position:
SLD2 WAR2 SLD1 WAR1 MON MAR

WHT, ARC - easy OHKO (turn 1-2)
THF - 2HKO (
SLD - 3HKO

observations
```
>SLD2 wait? advancing will attract THFA - not good; bait ARC by moving left?
THFA will always reach someone and fight, usually MON or unit to MON's left
THFB will advance
>WAR1 fight THFA, try to do 24-25
WHT will try to heal THFA, else wait, bait him to come down
ARC must fight, DON'T LET HIM ASCEND
>SLD1 advance and turn back to SLDA; let Mont KO THFA?
>MAR must CKO [WHT]
SLDA will fight SLD1
>MON KO [THFA] (try to hit SLD also)
>WAR2 crit SLDA ~24
SLDB will descend and fight

>SLD2 crit SLDA ~24
>WAR1 crit SLDB ~24
>SLD1 
>MAR CKO [ARC]
```

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

bought 3 Silver Sword + 1 Jack Knife; Jack Knife is just a page below Silver Sword, conveniently

# 3. The Cheetahs

Lightning banned on this day, not a big deal tho
units reduced by 2, so left the new recruits behind (reaching new jobs is priority, and the first 2 have Gauntlets anyway)

observations
```
>RIT advance, fight, KO THF possible
>SHA fight, can't KO BLK
ARC advance Disable
THF should be dead
WAR crit ARC (can't OHKO, need 2 crit)
MNK advance, try to avoid Air Render
FGT fight RITZ, good
SLD probably can't reach anyone yet
MAR can only reach 1 tile beyond the water
MON Fire, must try to KO tho very unlikely
BLK target MAR+MON, so keep them separate
```

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

marche ended quite near ritz so this saved some frames

just below 2 turns, quite satisfactory

i messed around with UU DD and ended up faster than the intuitive way, goes to show cursor mechanics still need to be studied

i don't think the clan can be manip'd to not spawn

took a lot of guesswork but i found out that quest reward is generated on the frame you select Missions in the pub
once i found this out khukuri only took 2 frames

## Shop 3

bought 2 Gauntlets; i presume i'm gonna need all the power i can get
[should have bought 2 Silver Swords as well]

whether a clan is going to move cannot be manipulated. however, where it moves to can be. particularly, a clan going offscreen saves quite a few frames (~4).

# 4. Desert Peril

1st allowed 111308
lowest flan HP i ever saw was 28
crits cannot do 2 damage
so flan will have to be 2HKO, sadly

COE, ANT easy 2CKO with SS

observations
```
SLD2 don't move
PAN advance
WAR1 don't move
COE1&2 advance
SLD1 crit
ANT advance
MAR crit ANT
MON can't KO flan with normal variance, shiiiiet
```

Speed requirements
ANT > MAR (108) - 111308 / 111324 (so that ANT is easier to reach)
MON > FLA

place 2 Silver Sword users (1 being MAR) on ANT side

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
areas for improvement:
Air Render for COE
OHKO FLN

mont stil has only 4 JP. don't think i'm going to reach 10 by Diamond Rain without using laws

therefore here are my options

1. do diamond rain normally - most straightforward, but the battle may be difficult
2. farm JP at Famfrit with self-target Ice / Fire (Ice costs 6\*40=240 frames, but Fire costs in-game days)
3. farm JP at Cadoan with Ice / Fire
4. farm JP at Famfrit AND Cadoan (4 days apart) - 6 JP can likely be gotten naturally (3 each), but involves weird routing and costs in-game days

i will try 2 first, since mont's damage against fam is minimal anyway

just realised i should have bought 2 more Silver Swords when i bought the Gauntlets. so i redid the entire fight to test if reducing shop visits really saves time.

- 2 visits - 129419
- 1 visit - 129197

so yes, it does. each additional visit costs about 4 secs.

Sprohm -> Ulei in 8 days = Sprohm -> above Lutia -> right of Ulei -> Ulei

# 5. Famfrit

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
- Fuck those law cards. Can't be arsed to redo this right now.
