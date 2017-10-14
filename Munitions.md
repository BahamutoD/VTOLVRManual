## Munitions

In this section we will discuss the various types of munitions available in VTOLVR
and how to employ them.

Here's a quick overview by type:

- [**Guided Weapons**](#guided-weapons)
    - [*Air-to-Air*](#air-to-air)
        - [AIM-9 Sidewinder](#aim-9-sidewinder)
        - [IRIS-T Advanced Short Range Missile](#iris-t-advanced-short-range-missile)
    - [*Air-to-Ground*](#air-to-ground)
        - [Optically Guided](#optically-guided)
            - AGM-65D Maverick
            - CAGM-6 Cluster Missile
        - [Laser-Guided](#laser-guided)
            - AGM-114 Hellfire
        - [GPS-Guided](#gps-guided)
            - GBU-38 Bomb
            - GBU-39 SD Bomb
            - AGM-89 Anti-ship Cruise Missile
- **Unguided Weapons**
    - Mk. 82 Bomb
    - Hydra 70 Rockets
    - Gau

---

### Guided Weapons

Guided weapons are the bread and butter of safe, efficient strikes. Though more expensive
than their unguided counterparts—the GBU-38 is about 10x the price of the Mk. 82—they are
also much easier to fire accurately outside the range of anti-air missiles that threaten
to knock you out of the sky.

#### Air-to-Air

##### AIM-9 Sidewinder

The Sidewinder is a standard, heat-seeking air-to-air missile.

*Cost*: $850 / missile
*Mass*: 120kg

##### IRIS-T Advanced Short Range Missile

A short range, heat-seeking missile with advanced capabilities. While nearly twice the
price of a Sidewinder, if you can afford the IRIS-T it will rarely let you down!
With improved maneuverability, range, and a counter-countermeasure system, the IRIS-T
is perfect for swatting pesky enemy aircraft when you've got better things to do than
engage in dogfights.

*Cost*: $1500 / missile
*Mass*: 123kg

##### *Employment*

The Sidewinder and the AIM-9 both have similar methods of employment. After selecting
the weapon, you'll have a big circle in the middle of your HUD, and you'll hear a
low growling through your headset. This represents the missile's seeker head. The basic
principle is to put your target inside this circle, wait for the growl to change into
a high-pitch screech, and squeeze the trigger.

Both missiles have a few different modes of target acquisition to help you get your
target inside the circle. As with any other configurable weapon, this can be found by
accessing the EQUIP page of the MFD, setting the mode to CONFIG, and selecting one of
the lines indicating the appropriate weapon.

The different targeting modes and their descriptions are:

Mode          | Description
--------------|------------
Caged         | The default mode; the targeting cue is locked to the middle of the HUD
Uncaged       | The targeting cue wanders around the middle of the HUD
Vertical Scan | The cue scans up and down the middle of the HUD
Head Track    | The cue follows the motion of your head.

> 🚨 **NOTE**: When using Head Track mode, make sure you've enabled HMCS power and lowered
> your HMCS visor!

---

#### Air-to-Ground

The most variety of munitions is currently of the air-to-ground variety, for taking out
tanks, SAM sites, radars, ships—you name it. Because of this variety, this section is broken
down by the different guidance systems used in the various weapons.


##### Optically Guided

Optically guided weapons generally have a shorter range and stricter lock requirements than
GPS-guided weapons, but they are also vastly better for hitting mobile targets, since they aren't
simply moving towards a fixed position. Make sure to be aware of any anti-air defences when
going in for a strike with an optically guided weapon!

###### AGM-65D Maverick

TK

###### CAGM-6 Cluster Missile

TK

###### *Employment*

The optically-guided missiles initially acquire their targets using the TGP. First, open the TGP
page on an MFD and slew it to a target until it locks on in POINT mode—making sure the ITT
reads "FOE," of course! Then, turn towards the target. Like the air-to-air missiles, when selecting
an optically-guided missile you will initially get a circle in the middle of your HUD. Once you
are in range and the missile has a lock, you will hear a tone. At this point, squeeze the trigger
and move on to your next target

---

##### Laser-Guided

TK

---

##### GPS-Guided

GPS-Guided weapons are a bit more complicated than other weapons, but are also very accurate and
can generally be employed from much safer distances, as well.

###### GBU-38 Bomb

TK

###### GBU-39 SD Bomb

TK

###### AGM-89 Anti-ship Cruise Missile

TK

###### *Employment*

There are currently two-types of GPS-guided weapons: the bombs, and the cruise missiles.

*GPS-Guided Bombs*

Selecting a GPS-guided bomb will put two concentric rings on your HUD, with the outer and
inner rings representing the max radius the bomb can steer to and the optimal steering
radius, respectively. Any GPS targets from the current GPS group will appear on the hud,
which a diamond around the current target. Simply maneuver until the target is in one of
the rings (preferably the "optimal" inner ring, especially if you're not very high up)
and squeeze the trigger.

Creating GPS targets can seem a bit daunting, but is easy enough once you get used to it.
Currently, you can create GPS targets from either the MAP or the TGP. In either place,
slew onto the target and press the `GPS-S` (GPS "Send") MFD button. This will add the
location to the current GPS *group*, creating a new group if there is none.

You can manage GPS targets and groups from the GPS page of the MFD, as you might expect.

GPS-guided bombs also have a couple configuration options:

- Targeting Mode:
    - Manual: The default mode
    - Auto: After each trigger pull, the next target in the GPS group will be selected
    - Dumb: The bomb acts like an unguided bomb using [CCRP](#ccrp-employment) (see below).
- Deploy Rate: TK?

> ⭐ **NOTE**: If you want a bit more accuracy from your MAP-created GPS targets, you can
> use the `GPS-A` (GPS "Acquire") MFD button on the TGP to slew the TGP onto the GPS target
> you created from the MAP, then manually slew the TGP until it locks, and use `GPS-S` one
> more time to create a new, more accurate, target.

*GPS-Guided Cruise Missiles*

Cruise Missiles are designed to follow a *path* of GPS points. To use them, you generally
create a new GPS group, switch to PATH mode, and add GPS points as above. You may also use
it in non-PATH mode, however, and the missile will cruise directly to the GPS point and search
for a target nearby.


### Unguided Weapons

Unguided weapons are perfect for when you don't have the time—or money—to nicely paint a target
the way you need for the more complicated guided weapons!

#### Mk. 82 Bomb

TK

##### *CCRP Employment*

TK

#### Hydra 70 Rockets

Cheap and plentiful, Hydras are your friend when you need something blown up quick. To use,
just put whatever you want to blow up inside the little circle and keep squeezing the trigger
until it's gone!

#### Gau minigun

TK
