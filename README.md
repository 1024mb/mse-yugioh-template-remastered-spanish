# mse-yugioh-template-remastered-spanish
<br>
Yu-Gi-Oh! Complete Package template for Magic Set Editor reworked in HD and Spanish.

Currently some graphics are kinda low quality, I'm in the process of reworking or searching for others with better quality. I've replaced several ones with better quality ones which should improve graphics.  
Also, MSE will now export the custom cards at 697 x 1016 px which at 300dpi is 59 mm x 86 mm for Standard and Pendulum templates. Bandai style is 756 x 1039 px which at 300dpi is 64 mm x 88 mm.

When I have been translating the English strings into Spanish I've encountered some errors in the original formatting of the template which I've fixed. Well, I've edited almost everything about sizes so I had to fix them when I was reworking that.  
There is currently at least one string (iirc) that I couldn't translate: "card".  
Yeah, that string that appears in the Random Packs tab, I don't know if is possible to translate that string because the little effort I put into changing it for "carta" didn't give any good results so I would have to look into it more deeply but that would be when I finish reworking the other card templates.  
<small>Update:</small> Upon some tiny... well I don't know if I can call it research but lets do it, I may have found that the only way of translating that is to change the source code of MSE, still will have to look into that more.

One complain tho, MSE is painful to work with when creating templates. I want to see if everything fits meticulously well but if one sets zoom to 200% you CAN'T see the bottom part of the card (it all depends on your resolution also, but with 1080p it was painful so...), I had to use my hawk vision to see if everything fit properly because exporting the cards as images was also SO damn tedious, I had to work with 90% zoom for the middle-bottom parts.

## Currently updated/reworked templates:

- Standard
- Standard Pendulum
- Bandai

## Unfinished templates (Either I'm still working on them or I haven't started yet):

- Standard Extra [It's currently harder than I thought with things not being fully implemented and other things wrong, all this on the original template so I left it to work on it when I finish the other templates]
- Comic
- TV Show
- Evolution
- Zotoshi
- CBG Style

## **Recommended** illustration sizes

- For Standard template: 498x502
- For Pendulum template: 614x462
- For Standard Extra template: 498x502, if choose no image frame then 528x529
- For Bandai template: 516x602

<br>

If I find the time I will translate this readme into Spanish, I'm lazy af :grin:.  
<small>(which I don't think is going to happen)</small>

## Changelog

- v0.1  
    - Initial work.
    - Finished Standard template.
    - Added resources with better quality.
    - Fixed some typos.
- v0.2  
    - Added Standard Pendulum template.
    - Added Standard Pendulum resources with high quality.
    - Fixed bad symbols size.
- v0.3 
    - Added Bandai style.
    - Added Bandai resources in high quality.
    - Improved the translation of some strings.
    - Fixed monster type text not shrinking when it was bigger than max width.
    - Fixed some words left untranslated and some that shouldn't have been.
    - Fixed the foil stamps of Pendulum cards, they weren't properly configured. 
    - Fixed position of foils on the Standard template, it was a little off.
    - Fixed Attribute not changing automatically when choosing Spell and Trap card types.
    - Fixed description of Bandai cards not shown in the "Description" column.
- v0.x **[Unreleased - WIP - Planned]**
    - Added Standard Extra template.
    - Added Standard Extra resources in high quality.
    - Added new custom attributes to the Standard Extra template, replacing the old custom ones as I don't have them in high quality nor did I found them on the Internet. Credits for the new awesome custom attributes goes to GraysoGoodwn from DeviantArt.


## Known Glitches <small>(yeah, you read it right)</small>

- It's better to set the zoom to 90% so the full card can be seen while editing.
- Levels (Stars, Spell/Trap type icons) may be shown by MSE as if they were very close to each other (this is more notorious with Stars because you usually add more than just one). Don't mind this, they are with the correct separation, if you want to see how the card will really look you have to set the zoom to 200% or just export the card and zoom the exported PNG with your favorite viewer.
- Words are not splitting when they are too large to fit in the same line, instead the whole word is being pushed to the next line and a big empty space is left. I haven't looked much into this so I don't know if it can be fixed or if it's hard-coded into MSE so in the mean time you should separate the words manually with an space.
- Description is always written in italics. I'm currently looking to fix this because is annoying, hopefully I will discover how to change this.

### Notes :notebook:

There are some bugs that belong to MSE itself and has nothing to do with the template thus I can't fix/change them from said templates.

- There is a text "double click to load image" that can't be translated, I tried looking for it on any other file but it isn't there so it must be on the source code of MSE.
- If you try to export and choose "Export All Images" and then pick "Custom Selection" and then proceed to select the cards you will face two errors, to fix them you have to go to "**\<mse-installation-dir\>**\\resource\\" and rename the file *"selected\_yes.png"* to *"selected.png"* and the file *"selected_no.png"* to *"deselected.png"*.
- You can set the Zoom at 200% and tick "Use zoom and rotation settings when exporting" on MSE settings to export the cards at twice the default resolution, of course that means that you will need at least an illustration at double the recommended resolution otherwise it wont look good. Although I'm not sure if MSE first resizes the illustration down to fit the configured illustration size (see up the recommended illustration sizes) and then proceeds to resize again the already resized illustration if one chooses the zoom at 200%, so use with care and compare results with the box ticked and unticked.


## Make sure to install the [required fonts](https://github.com/1024mb/mse-yugioh-template-remastered-spanish/tree/master/Fonts)

<br>

Please, if you see that something is misplaced, has the wrong size or something else open an issue and/or fork and commit.

<br>
<br>

<b><i>CREDITS FOR THE ORIGINAL WORK TO UNKNOWNGUEST, THE0NLYKYD, ART_FREAK, AND THE OTHERS WHICH I COULDN'T FIND INFORMATION OF.</i></b>