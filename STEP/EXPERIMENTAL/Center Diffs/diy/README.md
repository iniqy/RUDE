# DIY Center Diff option

## Introduction

There are two configurations of the center diff:
- HSP 02030 shaft on one end and regular diff cup on the other end. This allows to use dogbone shafts in the front axle, and either dogbone shafts or adjustable shafts in the rear axle.
- HSP 02030 shaft on both ends. This allows to use adjustable shafts on both axles.

Choose the Center Diff plate accordingly.

## BOM

* 4x M3x8 countersunk hex screws
* 4x M3 square nuts (DIN 562, not the thicker ones)
* 1x HSP 02024 diff. If you have spares parts of one, the crown gear and 1-2 diff cups are not needed
* 1-2 HSP 02030 (to use in the diff conversion)
* 4-5mm of steel tubing (OD 5mm, 0.2mm wall thickness)

## Printing guidance

Print in stiff materials. ASA/PC/PC-CF are good choices for motor plates. ASA is a good choice for gear mount (testing is appreciated, PC _should_ probably work)

Gear mount needs supports in the center.

## Assembly instructions

### 1. Center diff conversion

* Print the corresponding adapter depending on the spur gear revision
1. Disassemble the diff, on the crown gear side, remove spider gear from diff cup.
2. Cut 4-5mm of steel tubing, grab a HSP 02030 shaft and place the steel tubing on the thinner end. Install the spider gear there. It should look like this (TODO: insert picture here)
3. Place the rubber washer in the pocket of the printed adapter.
4. Install the shaft - don’t forget the metal washer!
5. If using shafts for both ends of the diff, repeat steps 3 through 6 on the other end. Otherwise, proceed to next step.
6. Fill with diff oil and close the diff with the printed adapter. Make sure diff case fits in the groove and screws are as tight as possible. Don’t forget loctite if using metal diff case.
7. Place the square nuts on the adapter. Grab the spur gear and secure it with 4 M3 8mm countersunk screws.

### 2. Center diff installation

1. Install center diff on motor plate (using bearing).
2. Place another bearing on the center diff plate, place center diff in the middle.
3. Install the above subassembly on chassis. Tuning note: Center diff should spin without binding but not loose, i.e. similar rotation as with rear/front diffs. Use shims as needed.
4. Install cup on motor plate side shaft.
5. Install motor on motor plate, do the gear mesh at this time.

### 3. Tuning

1. Tuning step - at this time, give the motor a spin for ~10-15 seconds. Everything should roll smoothly, if anything binds or diff gets hot, stop and check diff rolls smoothly without the motor.
2. Check that Diff is not leaking any diff oil. If it does, stop and verify screws from step 1.f are screwed to the very end and that diff case is correctly seated on the adapter.
3. Set up the rear diff part of the car as you would the front one, i.e. using the shorter 02030.
4. Assemble the rest of the car using normal procedure, repeating motor test after finished installing front and rear diffs.
