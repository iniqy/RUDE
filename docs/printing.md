# Print settings

For an upgrade from v1.0 to v1.1 the chassis, bellcranks and motorplate must be replaced. (Body can be saved for last.)

The chassis requires a 261x261 bed.

Everything must be printed with 8 walls and 100% infill, unless otherwise noted.

Abrasive filaments are not weak but have worse layer adhesion. On the other hand CF/GF-filled TPU could be stiffer. More testing needs to be done to know what is best.

### Calibration [Important: shrinkage!!!]

Make sure to print [this](/Calibration.stl) first for every filament to make sure your shrinkage is fine. As a reference: my TPU shrinkage is 99.8% and for ABS shrinkage 99.3%.

For quality prints I recommend this guide: https://ellis3dp.com/Print-Tuning-Guide/ basically walk through Tuning once and after that you only have to adjust PA and EM for different filaments and adjust first layer squish every now and then.

### Before printing TPU

Always dry your new TPU spool for a few hours in the oven at 60C. It's always wet from factory, which makes it hard to print and causes rough texture. If you use a new brand for the first time: set a low speed and set retraction to 0 mm, these can be experimentally increased (especially for harder TPU's) in consequent prints. You may need to do more adjustments but these are most important.


## PC

[For motorplate & bellcranks, ABS/ASA are fine too, but they are too weak for link/diffcase/servomount. PA deforms so Nylon is disrecommended.]

Part | Number | Support
--- | --- | ---
SteeringLink | 1 | Yes
MotorPlate | 1 | Yes
DiffCase | 2 | No
BellCranks | 1 | No
ServoMount | 1 | No
CarrierHubF | 2 | No

ServoMount may need adjustments for a specific ESC. Ezrun MAX10 and Quicrun 8BL150 are supported with bolted mounts. [Unverified but I suspect that Ezrun MAX8 has same mounting pattern as 8BL150 and that the Quicrun 10BL120 has same mounting pattern as MAX10.] Please share your custom mounts on discord.

CarrierHubF was previously recommended to print in TPU 98A or harder, but this seems to impact steering because its too soft. In PC its very rigid and seems to hold up well.

Our member makavelli tried diffcases in PLA+, but they gave bearing problems because they melted, so you must use high-temp filament for this and motorplate. Also shrinkage is really important for diffcases. A 0.2mm difference destroys your diffs. [And you need to disassemble and reassemble the car again..] Read more about the diffs in discord #troubleshooting.


## TPU 98A or harder

Note: TPU 95A is close in number but much more flexible than 98A and likely won't result in a good car.

Part | Number | Support
--- | --- | ---
Chassis | 1 | No
Arms | 1 | No
UpperArms | 1 | No
CarrierHubR | 2 | No
TopDeck | 1 | No
Tower | 2 | No
HSP02016_insert | 0-2 | No

Use a HSP02016_insert if your middle axis can (almost) escape. That one doesn't need to be TPU.


## TPU

2/3 walls and 0-40% infill (depends on hardness of your TPU, but a soft brace can absorb some impact).

Part | Number | Support
--- | --- | ---
Brace | 2 | No




# Stock body

## Any material

Avoid materials with weak layer adhesion. ASA/ABS bodies crack easily along the thin layer lines. In discord is a mod that includes a rear wing. BodyR_Clip has been removed in favor of an M8 bolt through TopDeckR, [see here](Assembly.md).

Part | Number | Support
--- | --- | ---
BodyF_Clip (only v1.0) | 1 | No
Body | 1 | No
