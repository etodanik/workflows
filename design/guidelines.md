Design Submission Guidelines
============

This document contains some guidelines in order to enable a smooth and enjoyable workflow between the different parts of a web development team, whether in a company or a group of freelance professionals. Below is a set of gudelines / questions that are relevant to most designs before they arrive at a frontend guy's desk.

---

##General Stuff
|Parameter|Value|
|-|-|
|Site width on large screens|980px|

If you're doing anything else (full width design, a different base width e.t.c) - be specific.

##Typography
Let's spend a few moments getting our typography straight.

The base size is the size of text in a paragraph. This value is given in pixels.

Please specify heading sizes in `em` units ([understanding em units](http://www.impressivewebs.com/understanding-em-units-css/)).

A good guideline is to have uniformly sized levels of  heading sizes throughout the design, to keep the user well oriented in the content hierarchy. We want to have a main heading somewhere on the page, indicating the title of the current page.

Still find it confusing to specify `em` sizes? Try the [px to em calculator](http://pxtoem.com/)

|Parameter|Value|
|-|-|
|Base Size|16px|
|h1|2.75em|
|h2|2.25em|
|h3|1.75em|
|h4|1.25em|
|h5|1em|
|h6|0.85em|

## Grid ([What is a grid?](#typography/grid))
For some reading material and resources regarding grids, check out [this article](http://www.smashingmagazine.com/2007/04/14/designing-with-grid-based-approach/).

For most projects you won't need to mess too much with the grid values. However, if you feel like playing aorund with things, head over to [gridpak.com](http://gridpak.com/).

While designing avoid absolute `px` values and make sure you follow the distances between columns set by the grid.

|Parameter|Value|
|-|-|
|Columns|12 (normally 12 for most uses or 16 for highly detailed sites)|
|Column padding|1%|
|Gutter width|2.75%|

##Colors
|Parameter|Value|
|-|-|
|Primary|e.g #5A89F0 or rgb(90,137,240)|
|Secondary||
|Links||

##Icons
When using icons in your design, please try to make use of icon fonts, such as [Font Awesome](http://fortawesome.github.io/Font-Awesome/) or something from [We Love Icon Fonts](http://weloveiconfonts.com/). Why? mainly because you never know what size the screen of the user will be and you want to keep icons scalable.

If you have to use a custom designed icon, please try to submit it in the `svg` format, and if for some reason you insit on using image, make sure you submit *both a regular resolution version and a 2x version for high DPI screens*

All icons have to be sent in a folder/archive along with the design `psd` file.

##Images
For any images, such as backgrounds, slider images e.t.c, always provide a high-res version of any image to leave flexibility for scaling down on image size.

*Any icons found inside a PSD and not supplied according to the above guidelines will cause the design to be rejected for resubmission*

##PSD structure
This one is important - if you're submitting a PSD file, please pay extremely careful attention to the following:

- All layers **must** have meaningful names. Layer names like `Layer 238 Copy 2 Copy 3` will cause the PSD to be rejected, and you will have to re-submit your design.
- Group your elements logically. Ideally - each logical group of layers will have its' own folder, such as `Header`, `Footer`, `Sidebar`, that could contain groups named `Submit Button` and `Sample News Paragraph`. The rule of thumb is that any group could be exported to a [Smart Object](http://helpx.adobe.com/en/photoshop/using/create-smart-objects.html) and saved as a PNG file, and it would still make sense.
- Avoid destructive changes to layers, use [Adjustment Layers](http://helpx.adobe.com/en/photoshop/using/adjustment-fill-layers.html)
- Shadows, borders, and the like should be done with [Layer Styles](http://helpx.adobe.com/en/photoshop/using/layer-effects-styles.html) - anything else will be rejected for redesign and resubmission

##Fonts
It is ok to use special fonts, as long as you:

- Remember to specify a fallback. In case your font doesn't load, here are a few [safe fonts that every computer should have](http://cssfontstack.com/)
- Supply the font, preferably in multiple formats. [Here is a good read on @font-face and web fonts](http://www.smashingmagazine.com/2011/03/02/the-font-face-rule-revisited-and-useful-tricks/)
- Make sure you have a license for the use of the font on the web
- Also, avoid webfonts for the paragraph text. Going overboard with webfonts causes performance issues, and decreases readability