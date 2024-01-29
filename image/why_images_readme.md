This describes the tools used for the images on the why page
  and the color space and choices used.

# Diagramming tool

The images were created with draw.io 
  and can be loaded to and edited on that site, which is currently free. 
The png files have the draw.io source embedded within them. 
When saving a final copy, you do want to use file | export 
  and set zoom 200%, border 10.
Otherwise they'll look pixilated.
See the refs below for the color picker used. 

# Color design

The main goals for the colors were:

- Meeting the web font readability standards 
  for color [contrast](https://www.w3.org/TR/WCAG21/#contrast-minimum). 
  All the keys have a color contrast of at least 7, 
    and for the darker keys it's around 9.
  An exception is a few historical keys that are less or rarely used today,
    which have a gray font and a contrast around 5.
- Highlighting the five central 'home' columns
   to separate the mostly standard center 
   from the more varied edges.
   Despite this, we didn't use a lighter shade 
     when the central columns held special colored keys
     as that threatened to complicate the color scheme. 
- Having distinct colors for the different key groups.

## Color space
The colors were managed in the 
  [Okhsl color space](https://bottosson.github.io/misc/colorpicker), 
  which makes it easier to independently vary human perceivable 
  hue, saturation and lightness. 
For fixed lightness, 
  this allowed varying the hue or lightness 
  while keeping a fairly consistent color contrast to off-white. 
We used an accompanying [color picker](https://bottosson.github.io/misc/colorpicker).

## Color thoughts

- Gray brown
  - A base, nothing unique, muted color. 
  - Default brown is is HSV: 30, 100, 59; Okhsl: 55, 100, 42. 
   We desaturate it significantly as we mostly wanted a muted neutral.
  - Using pure gray looked too similar to the uncolored page background 
     vs the colored keymap.
  - Brown is also the color of soil, and this is a Hillside keymap. 
- Blue for mods: no real meaning, just a primary color.
- Light blue for layer keys
  - Layers are sort of a mod key, so a different blue.
  - Lighter than the mod blue for emphasis as layers come before any other key use.
- Green for motion.
- Red for change/edit.
- Purple for media as a color less common in the natural world, thus media/culture. 

## Color codes

Some highlights:

- To show key borders as being lower, they're set seven points darker in Okhsl. 
- A few more historical keys keys (print screen, scroll lock and pause) use a darker font,
  I decided they can fall under the deactivated control part of the spec. 

The colors are:

| Item       | Color        | OKHSL     | RGB      | Comment                    | Edge Okhsl|
| ---        | ---          | ---:      | ---     | ---                         | ---:      |
| Core       | gray l.brown |  55 17 30 | #50423A | con 7.1, desaturated to 17  |  55 17 23 |
| Side       | gray brown   |  55 17 23 | #3E332C | con 9.2, desaturated to 17  |  55 17 16 |
| Modifiers  | blue         | 271 80 23 | #1F2B74 | con 9.3                     | 271 80 16 |
| Layers     | azule light  | 262 88 30 | #164092 | con 7.1, saturated to 88    | 262 88 23 |
| Navigation | green        | 144 80 23 | #1C3E1C | con 8.8                     | 144 80 16 |
| Editing    | red          |  15 80 23 | #611422 | con 9.5                     |  15 80 16 |
| Media      | purple       | 291 80 23 | #391e76 | con 9.5                     | 291 80 16 |
| Font       | white off    |  90  0 88 | #DDDDDD |                             |   |
| Font rare  | white dark   |  90  0 66 | #A1A1A1 | con 4.7 to dark keys        |   |
| Page       | black gray   |  90  0 14 | #212121 | 40% wiki page background    |   |

# References

- Wed content accessibility guidelines level AAA (enhanced) call for a contrast ration 
   of at least 7:1 between text and background, https://www.w3.org/TR/WCAG21/#contrast-enhanced.




