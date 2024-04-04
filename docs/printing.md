# Print settings

The chassis requires a 261x261 bed. In discord is a usermod available for 250x250 beds (cut corners) and another mod for 182x182 beds (split chassis).

Everything must be printed with 8 walls and 100% infill. Abrasive filaments are not weak but break faster and have worse layer adhesion. On the other hand abrasive TPU is stiffer. More testing needs to be done to know what is best.

### Calibration

Make sure to print [this](/Calibration.stl) first for every filament to make sure your shrinkage is fine. As a reference: my TPU shrinkage is 99.8% and for ABS shrinkage 99.3%.

For quality prints I recommend this guide: https://ellis3dp.com/Print-Tuning-Guide/ basically walk through Tuning once and after that you only have to adjust PA and EM for different filaments and adjust first layer squish every now and then.

### Before printing TPU

Always dry your new TPU spool for a few hours in the oven at 60C. It's always wet from factory, which makes it hard to print and causes rough texture. If you use a new brand for the first time: set a low speed and set retraction to 0 mm, these can be experimentally increased (especially for harder TPU's) in consequent prints. You may need to do more adjustments but these are most important.


## PC

PET is a good alternative (not PETG). PA12 is suspected to be a good alternative. PA6 may suffice too.

100% infill!

ABS/ASA are not recommended anymore because RUDE receives a lot harsh treatment and diffs are receiving a lot of forces, causing them to crack in places and your car to make noises everywhere [damaging metal parts].

Part | Number | Support
--- | --- | ---
Link | 1 | Yes
MotorPlate | 1 | Yes
DiffCase | 2 | No
BellCranks | 1 | No
ServoMount | 1 | No

ServoMount may need adjustments for a specific ESC. Ezrun MAX10 and Quicrun 8BL150 are supported with bolted mounts. [Unverified but I suspect that Ezrun MAX8 has same mounting pattern as 8BL150 and that the Quicrun 10BL120 has same mounting pattern as MAX10.] Please share your custom mounts on discord.


## TPU 98A or harder

Note: TPU 95A is close in number but much more flexible than 98A and likely won't result in a good car.

Part | Number | Support
--- | --- | ---
RRHubToeIn | 2 | Optional
Chassis | 1 | No
Arms | 1 | No
UpperArms | 1 | No
HubCarrierF | 2 | No
TopDeck | 1 | No
Tower | 2 | No
HSP02016_insert? | 0-2 | No

Use a HSP02016_insert if your middle axis can (almost) escape. That one doesn't need to be TPU.


## TPU

3 walls and 10-40% infill (depends on hardness of your TPU, but a soft brace can absorb some impact).

Part | Number | Support
--- | --- | ---
Brace | 2 | No




# Stock body

## Any material

Avoid materials with weak layer adhesion. ASA/ABS bodies crack easily along the thin layer lines. In discord is a mod that includes a rear wing.

Part | Number | Support
--- | --- | ---
BodyClip | 1 | No
BodyGroove | 1 | No
Body | 1 | No