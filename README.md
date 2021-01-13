# 3d-print-MR-headset
Here you will find the 3D files which contain the Aryzon 3D printable MR headset. This headset uses your iOS or Android phone to show content in true volumetric 3D, similar to other expensive headsets like the Microsoft HoloLens. It is developed by us at Aryzon and works with our AR Studio app so you can easily visualize models from Sketchfab, Google Poly or your own 3D models.

## The parts
There are some parts that cannot be printed, like the visor, mirror, lenses and headband. You can order these parts here: https://www.aryzon.com/3dprint

## Print instructions
On FDM printers place the flat front-most surface on the print bed. Print the parts at 100% of their size. We have had great results with a layer height of 0.2 mm. A smaller layer height is possible but will make your print a lot slower without much benefit since this is quite a large print.

1) Set your printer to the appropriate settings for the filament used, we tested PLA and ABS.
2) A layer height of 0.2 mm will provide great results, smaller is not necessary.
3) Use an infill percentage of 10-20%, higher will cause a heavier headset, meaning less comfortable.
4) Use a brim layer if curling up from the printbed is an issue.
5) Turn on support, if you are confident your printer can print up to a 45 degree angle tweak the support angle so it looks like this:

![Screenshot](Docs/SupportAngle.jpg)

Tip: Lowering the print speed helps to reduce the chances of many issues.

### Supported printers
Any 3D printer with a print bed of at least 200x150 mm that can print 150 mm high is supported.
If really necessary you can cut the model in half, print both halves and glue them together. A heated print bed is advised since curling can more quickly become an issue on larger parts.

## Assembly instructions
We made a video to help you quickly assemble the headset. You can find the instructions at https://www.aryzon.com/3dprint.

## Supported phones
There are two basic checks to see if your phone is supported:
1) Your phone must not be larger than 166 mm in length (that's quite big)
2) Your phone will need to be able to do room-scale tracking. You can see how well your phone does this by trying out the Aryzon AR Studio app.

## Unity3D Developers
All our headsets including the 3D printed one work with our Unity SDK, any Unity dev can easily create their own app for the headset. (You can even build HoloLens applications for your phone!) More details here: https://www.aryzon.com/creators.

## Idea behind the design
Our focus has been to make this headset easy to print and assemble so it can be printed by the average 3D printing enthusiast. The design therefore exists of only 2 parts to print and requires only little support material.

## Remix the design
We have open sourced the design of the headset and anyone is welcome to change it or make recommendations to improve it.

# License
All files in this repository are licensed under Creative Commons Attribution 4.0 International (CC BY 4.0). See file LICENSE for more details.
