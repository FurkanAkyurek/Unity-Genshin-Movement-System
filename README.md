# Genshin Impact Movement System

An attempt on replicating 3 *(Moving, Gliding, Swimming)* Genshin Impact Movement Systems.

https://user-images.githubusercontent.com/71723988/163194989-ad110106-573e-4103-b024-60d573fd56cd.mp4

[Click here for longer video (41.5MB)](https://imgur.com/C0FF5CI.png)

When coming from the **Falling State**, 2 new **Landing States** are added: **Hard Landing** and **Rolling**.

**Hard Landing** happens when the **Player** falls from an **high height** and has no **Movement Input Key** being pressed at the moment of contact.

https://user-images.githubusercontent.com/71723988/163195012-df532031-a5ab-49a0-b65b-ebfb1170a11d.mp4

**Rolling** happens when the **Player** falls from an **high height** and has a **Movement Input Key** being pressed at the moment of contact.

https://user-images.githubusercontent.com/71723988/163195031-6aff52aa-9971-4fe2-abe7-ebe45ae09a21.mp4

## Animations

Animations are added through an Animator Controller using **Reusable Sub-State Machines** *(No Blend Trees are used)*.

https://user-images.githubusercontent.com/71723988/163195047-36ab2a11-cc99-42e5-8358-40ffd697f80f.mp4

There are Animations for every State.

## Gliding System

[![Generic badge](https://img.shields.io/badge/Status-WIP-yellow.svg)](https://shields.io/)

- [X] State Machine & States *(Transitions Included)*
- [X] Glides
- [X] Different Camera Settings
- [X] Player Animations *(Glide Start Animation Included)*
- [ ] Player Tilt *(Needs to be fixed)*

## Swimming System

[![Generic badge](https://img.shields.io/badge/Status-WIP-yellow.svg)](https://shields.io/)

- [X] State Machine & States *(Transitions Included)*
- [X] Swims *(Fast Swim Included)*
- [X] Dives
- [X] Floats
- [X] Submerges
- [X] Different Camera Orbit
- [X] Different Camera Settings
- [X] Player Animations
- [ ] Can go back to the Ground *(Needs to be fixed in a certain Situation)*
- [ ] Movement *(Needs to be reviewed to make sure it's working as intended)*
- [ ] Rotation *(Needs to be fixed in a certain Situation)*

# License

[![License](https://img.shields.io/badge/LICENSE-MIT-ff1709?style=for-the-badge&logoColor=white&color=orange&labelColor=gray)](LICENSE.md)

**Mixamo Animations** & **Kenney's Prototype Textures** are not considered in my License and are provided just so you can test the System.

Their licenses still apply.

# Version

![License](https://img.shields.io/badge/VERSION-1.0.0-ff1709?style=for-the-badge&logoColor=white&color=blue&labelColor=gray)




# Notes

Animations were downloaded from https://www.mixamo.com.

I use [Kenney's Prototype Textures](https://www.kenney.nl/assets/prototype-textures) for the Included Map.

As of the moment I released this repository, [I'm on a break](https://youtu.be/FwHlWprug9M).

This means that the System won't be updated soon and it might take a while for the rest of the Systems to be released.
