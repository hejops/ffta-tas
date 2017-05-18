# Benchmarks
```
 47109 Sprohm
 62486 Lutia
 86299 Nubs
106317 Eluut
128055 Ulei
```

# Intro, Snowball, Lizards
followed FellVisage's run more or less

- unequipped armor
- changed monk -> warrior
- fired viera, nu mou

## 1st shop
- Sprohm, since cursor already on it
- sold: all armor except Cuirass, all Shields, Bandage, Phoenix Down
- buy: 3 Shortswords, 3 Gauntlets
- i sell largest valued items (450 to 300) to minimise dialog with shopkeeper
- notably i didn't sell cuirass. moving right from armor to accessories tab while equipping costs 3+3+6 extra frames (Bangaa affected twice), but the shopkeeper dialog is far longer than 12 frames. further optimisation may be possible.

- equipped Shortsword + Gauntlets
- paid for herb picking
- 140 Gil left

- not sure what's the best way to move cursor
- currently testing enemy stats generated on different frames
- stat manipulation is too tedious for me right now

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

place lutia, 62597 frames -> 62451 after moving marche

need 2 atmos blades on dueling sub AND thesis hunt - this might be hard; if i can't do it within 60 frames i'll settle for 1
i settled for 1; atmos on dueling wouldn't appear even after 60+ frames [area for improvement, tho idk how much better 1 more atmos'd be]

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
bought 2 Gauntlets; i presume i'm gonna need all the power i can get

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