---
title: How
description: How do you use a 40% keyboard?
published: true
date: 2023-02-09T21:23:18.331Z
tags: 
editor: markdown
dateCreated: 2023-02-09T21:23:18.331Z
---

# How

How do you use a 40% keyboard? 

To an outsider, 40% keyboards may look like just novelties. Numbers and symbols like $ are commonly typed and useful in a variety of situations. Most 40% keyboards lack things like a dedicated numrow and are often smaller than just a 60% with its numrow cut off, so how do people actually use 40% keyboards?

The key to the functionality of 40% keyboards and how the people that use them get work done while using them lies in some key features of the QMK firmware. QMK allows a variety of complex actions to be carried out on keyboards aside from only macros. The QMK functionality that enables 40% keyboards to function just as a full keyboard would are as follows:
1. Layers 
2. Tap Dance 
3. Combos 

## Layers

Layers are probably the easiest to understand as many people who use keyboards larger than 40% also use layers. Using shift is technically using a layer. Shift changes the keymap you type on so that instead of typing a lower case letter you type a captial letter or a symbol instead of a number. Caps lock in this case essentially functions as a toggle for layers rather than a momentary switch like shift.

40% users will often have more than two layers on a keyboard, depending on what they use the keyboard for. The base layer (layer 0) is most commonly where all of the alphabetic keys are. Often—but not always—numbers will reside on the second layer. 

## Tap Dance

The tap dance funcitonality in QMK allows a key to act differently if it has been tapped once, double tapped, or held down within a certain user defined time span of pressing the same key again. Tap dance is especially useful on smaller 40% layouts or sub-40% layouts. In cases where a user is using a keyboard like a QAZ where there are not dedicated keys for mods, tap dance can be utilized to make keys function both as mods and as alphabetic keys.

## Combos

Combos are another way of making keys act as other keys. Combos would be used in circumstances that would make using layers or tap dance confusing or incovenient. Using a combo can allow for repeated keystrokes without misinput. 

A common use for a combo would be backspace on a QAZ. Using tap dance or layering on the P key (the topmost rightmost key) as backspace would be slower than using a combo of O+P and less accurate. The O+P combo can be repeated as quickly as both keys can be pressed and unpressed. 



To have access to these features, a lot of 40% keyboards use [Vial-compatible firmware](https://github.com/vial-kb/vial-qmk). [Vial](https://get.vial.today/) is a graphical interface for a lot of QMK features that allows you to set up those mechanics to match your needs.

Finding a *perfect* keymap for your needs is an iterative process which may take a lot of time. You can find examples of 40% keymaps in \#keymaps channel of [40% Keyboards](https://discord.gg/40percent) Discord server or on the [KeymapDB](https://keymapdb.com/) website.

## Example keymaps

### QAZ
![QAZ Keymap.png](/QAZ Keymap.png){.align-right}
