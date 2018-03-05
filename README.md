# OneHourOneLifeDocumentation
This is documentation for OneHourOneLife. If you would like to add to the documentation you can do so by making a pull request.
We will go over the game per folder.

<!---## OneLife_vXX/animations--->
## OneLife_vXX/categories
This folder houses categorie files.   
A categorie has the following attributes

| variable name | description |
| --- | --- |
| parentID    | parent ID |
| numObjects  | number of Objects |
| [nameless]  | multiple child Ids |

parentID and ChildId are also the ids of objects.  

Child objects can be used in transitions which require the parent object.
### Example
file name: 367.txt
```
parentID=367
numObjects=12
132
131
66
64
67
68
69
107
390
344
496
498
```
<!---## OneLife_vXX/graphics--->
<!---## OneLife_vXX/ground--->
<!---## OneLife_vXX/groundTileCache--->
<!---## OneLife_vXX/languages--->
<!---## OneLife_vXX/music--->
<!---## OneLife_vXX/objects
This folder houses object files.   
A object has the following attributes

| variable name | description |
| --- | --- |
| id    |  |
| [nameless]  | name of the object |
| containable |  |
| containSize |  |
| vertSlotRot |  |
| permanent |  |
| minPickupAge |  |
| heldInhand |  |
| blocksWalking |  |
| leftBlockingRadius |  |
| rightBlockingradius |  |
| drawBehindPlayer |  |
| mapChance |  |
| heatValue |  |
| rValue |  |
| person |  |
| noSpawn |  |
| male |  |
| deathMarker |  |
| foodValue |  |
| speedMult |  |
| heldOffset |  |
| clothing |  |
| clothingOffset |  |
| deadlyDistance |  |
| useDistance |  |
| sounds |  |
| creationSoundInitialOnly |  |
| numSlots |  |
| slotSize |  |
| numSprites |  |
| spriteID |  |
| pos |  |
| rot |  |
| hFlip |  |
| color |  |
| ageRange |  |
| parent |  |
| invisHolding |  |
| invisWorn |  |
| behindSlots |  |
| headIndex |  |
| bodyIndex |  |
| backFootIndex |  |
| frontFootIndex |  |
| numUses |  |
| useVanishIndex |  |
| useAppearIndex |  |
| pixHeight |  |

Objects can be used in transistions to create other objects

### Example
file name: 33.txt
```
id=33
Stone
containable=1
containSize=1,vertSlotRot=-0.250000
permanent=0,minPickupAge=3
heldInHand=1
blocksWalking=0,leftBlockingRadius=0,rightBlockingRadius=0,drawBehindPlayer=0
mapChance=1.000000#biomes_0,3
heatValue=0
rValue=0.000000
person=0,noSpawn=0
male=0
deathMarker=0
foodValue=0
speedMult=1.000000
heldOffset=5.000000,-5.000000
clothing=n
clothingOffset=0.000000,0.000000
deadlyDistance=0
useDistance=1
sounds=-1:0.250000,-1:0.250000,-1:0.250000,-1:1.000000
creationSoundInitialOnly=0
numSlots=0#timeStretch=1.000000
slotSize=1
numSprites=1
spriteID=144
pos=0.000000,-31.000000
rot=0.000000
hFlip=0
color=1.000000,1.000000,1.000000
ageRange=-1.000000,-1.000000
parent=-1
invisHolding=0,invisWorn=0,behindSlots=0
headIndex=-1
bodyIndex=-1
backFootIndex=-1
frontFootIndex=-1
numUses=1
useVanishIndex=-1
useAppearIndex=-1
pixHeight=0
```
<!---## OneLife_vXX/otherSounds--->
<!---## OneLife_vXX/playbackGame--->
<!---## OneLife_vXX/recordedGames--->
<!---## OneLife_vXX/reverbCache--->
<!---## OneLife_vXX/scenes--->
<!---## OneLife_vXX/settings--->
<!---## OneLife_vXX/sounds--->
<!---## OneLife_vXX/sprites--->
## OneLife_vXX/transitions
## Algoritme











