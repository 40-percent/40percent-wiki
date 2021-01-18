---
title: Corne
description: Corne Keybaord
published: true
date: 2021-01-18T17:31:03.000Z
tags: split, column stagger
editor: markdown
dateCreated: 2021-01-18T04:35:40.444Z
---

# Corne
The Corne keyboard (also known as crkbd and Helidox) is a split keyboard with 3x6 column staggered keys and 3 thumb keys, based on the Helix. It uses Pro Micro-compatible boards for the MCU, TRRS interconnect cables, and optionally supports OLED screens and per-key RGB LED's. This keyboard was created by [foostan](https://twitter.com/foostan) and is open-source.

![corne.jpg](/corne.jpg){.align-right}

## Overview
Many features of the Corne were initially developed in the Helix, such as symmetrical PCB's which are cheap to manufacture, mounting the Pro Micros on the top of the board in the innermost columns, support for OLED screens over the Pro Micros, and breakable rows/columns. The Corne has moderate columnar stagger, as made famous by the Ergodox. Many versions of the Corne feature a breakable outer column that can be removed to transform the board into a 10u or 3x5+3 board.

Because the Corne is open-source, cheap, and easy to solder (except for the RGB LED's), it has become very popular in both the Japanese and Western communities. It has a subreddit at [/r/crkbd](https://www.reddit.com/r/crkbd/) and a dedicated Discord server, [Pastry Keyboard](https://discord.gg/aWCZWnS).

The Corne is named after the [cornetto pastry](https://en.wikipedia.org/wiki/Cornetto_(pastry)).

### Types
There are many versions of Corne keyboards developed by foostan, in several versions.

*   ###### [Corne Classic](https://github.com/foostan/crkbd/tree/master/corne-classic)
    This variant uses symmetrical PCB's and through-hole soldering of switches. It supports MX, Choc, and ALPS switches. RGB LED's are supported.

*   ###### [Corne Cherry](https://github.com/foostan/crkbd/tree/master/corne-cherry/doc)
    This variant only supports Kailh MX hotswap sockets, for use with MX switches. RGB LED's are supported. V2 uses symmetrical PCB's, north-facing switches, and a breakable outer column. V3 uses non-symmetrical PCB's, south-facing switches, and a non-breakable outer column, and can also be partially soldered by the factory.

*   ###### [Corne Chocolate](https://github.com/foostan/crkbd/tree/master/corne-chocolate)
    This variant only supports Kailh Choc hotswap sockets, for use with Kailh Choc switches. RGB LED's are supported.

*   ###### [Corne Light](https://github.com/foostan/crkbd/tree/master/corne-light)
    This variant is designed to be easier to solder, using only through-hole parts, non-symmetrical PCB's, and no LED support. V1 only supports MX switches. V2 supports MX, Choc, and Choc V2 switches.

Version 1.0 of the Corne was released by Foostan on April 22, 2018.

Other community-made variants include:

*   ###### Easy LED version
    A variant of the Corne Cherry V2 which uses the easier to solder SK6812MINI-E RGB LED's.

*   ###### [Chocorne](https://github.com/davidphilipbarr/36keys/tree/master/42Keys)
    A version of the Corne which uses tighter Choc spacing to remove any gaps between keycaps. Versions available for Kailh Chocs and Kailh Choc Minis (PG1232).

*   ###### [Corne-ish Zen](https://geekhack.org/index.php?topic=109744.0)
    A Corne with Choc hotswap sockets, Choc spacing, full Bluetooth support, E-paper screens, and will be pre-soldered. Currently in interest check.

*   ###### [Corne ECWL](https://github.com/sekigon-gonnoc/CorneECWL)
    A wireless Corne which uses NiZ Plum EC rubber dome switches (similar to Topre).

*   ###### [Jorne](https://github.com/joric/jorne)
    A Corne with an extra key on an outer column for various international layouts.

### Case Options
Simple plate kits are commonly available, from [the plates directory of the main repo](https://github.com/foostan/crkbd/tree/master/plates). This inlcudes both SVG's for laser cutting and files for getting FR4 plates cut by a PCB manufacturer. Plates are most commonly available in FR4 and acrylic, though services can cut plates from metal if desired.

Many other kits have been developed by the community, including:

*   ###### [IMK Corne](https://imkulio.com)
    A unibody case made of aluminum or polycarbonate, with optional tenting holes and legs.

*   ###### [Burle](https://geekhack.org/index.php?topic=107689.0)
    A premium, high profile case made of aluminum or polycarbonate, with brass weights. Currently in interest check.

*   ###### [Corne LP](https://boardsource.xyz/store/5f2efc462902de7151495057)
    An aluminum low profile case for the Corne Chocolate.

*   ###### [Little Keyboards stacked cases](https://www.littlekeyboards.com/collections/corne-cases)
    Cases made from layers of stacked acrylic, wood, and metal.

*   ###### [Keyhive 3D printed cases](https://keyhive.xyz/shop/3d-printed-corne-helidox-case)
    Simple high profile cases, with solid or hex patterns available for the bottom. Only available when the KeyHive printing queue is clear.

*   ###### [High Profile 3D printed case](https://www.thingiverse.com/thing:3652379)
    A simple high profile case that replaces the bottom plate.

*   ###### [Bento Case](https://www.thingiverse.com/thing:4229965)
    A case for the above HiPro case, which lets you keep your Corne in a convenient carrying box with a handle for travel.

*   ###### [Low Profile 3D printed case](https://www.thingiverse.com/thing:4011269)
    A simple low profile case that repalces the bottom plate, with holes for bumpon feet.

This is not an exhaustive list - there are many more cases available!

### Build Tips
Starting with V3 of the Corne, SK6812MINI-E RGB LED's are used for per-key lighting. These feature small tabs on each pad which makes them much easier to install.

If you're using a version with symmetrical PCB's, use a small piece of tape to mark which side is "up" so you don't accidentally build 2 left half Cornes.

The SK6812MINI RGB LED's (without tabs) used in older versions of the Corne are heat sensitive and require a solder bridge to be installed. This is recommended only for experienced solderers with temperature-controlled soldering irons. These are completely optional and are not used in the Easy LED and Corne V3.

The default firmware does not have RGB LED's enabled by default. Community keymaps that have them enabled include drashna's and soundmonster's.

foostan suggests using a layer of foam or shelf liner underneath the PCB to make the board as low as possible if you don't want to use a case, or are using Choc V2's which have compatibility with most keycaps and plates.

## Availability
The files are open source and can be found at the [Git repository](https://github.com/foostan/crkbd).

Many vendors stock the Corne as well, including:

*   [Boardsource (US)](https://boardsource.xyz/store/5ecc0f81eee64242946c988f)
*   [Keyhive (US)](https://keyhive.xyz/corne) - Also has pages for [Easy LED](https://keyhive.xyz/shop/ez-corne) version and [Corne V3](https://keyhive.xyz/shop/corne-v3)
*   [Little Keyboards (US)](https://www.littlekeyboards.com/collections/corne)
*   [Mechboards (UK)](https://mechboards.co.uk/shop/kits/helidox-corne-kit/)
*   [Worldspawn (US)](https://www.etsy.com/listing/786867725/corne-easy-led-version-pcb-and) - Easy LED version only