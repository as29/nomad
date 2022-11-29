# The Nomad

![final product image ](/images/testing.png )

[[toc]]


## About

Nomad is a ergonomic, wireless, split keyboard for a commuter or traveling worker. It strikes a balance between convenience, productivity, and aesthetics. But above all, it is a design that works for me personally.

## Using this Repository
Use the **output** and **zmk-config** folder contents as is for the PCB design and default ZMK configurations. Modify them to suit your needs...have fun!

**ergogen** - contains the yaml files to generate the outlines and PCB that can be further refined using other tools such as Fusion360 and KiCad. Modify them to change the layout or components. Head to the Ergogen (add link here) repository for more information.

**output** - outputs of running Ergogen on the yaml inputs in the Ergogen folder

**zmk-config** - files, including the default keymap, for compiling ZMK (add link here) for the Nomad shield

**images** - keyboard renders, layout, and keymaps for reference


## Design Drivers

The need to design a new keyboard arose from a lack of existing designs that satisfied **all** of the following:

| #| Driver                |   Description                                                                                                                                                                                                                                                                        | Design Decision             |
| -| --------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------| --------------------------- |
| 1| **Column Stagger**    |   I could not find any other keyboard with the column stagger that addresses how my fingers naturally fall on the keyboard                                                                                                                                                           | **High Column Stager**      |
| 2| **Portable**          |   I needed the board to fit into my laptop bag or luggage without bulking it up or needing extra care to prevent from damaging during my commute/travels                                                                                                                             | **42/36 keys, low profile** |
| 3| **Wireless**          |   Also plays into # 2 .  No cables  so its easier to grab and go.                                                                                                                                                                                                                    | **Nice!Nano**               |
| 4| **Beginner friendly** |   I   have mostly used 65%  or 60% layouts so this would be my first time diving into using layers more frequently in an environment where productivity matters. Having something that will help with the transition, like showing what layer I am on etc. would make the difference.| **Nice!View**               |


## Design Process
TBD

## Inspirations and References
TBD