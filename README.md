# Log Analysis Visualizations - Creating new, hacking old

## Background:

Ever want to create a new visualization or hack on one of the existing ones?  Everything in Log Analysis v1.3.2 and earlier is based upon an IBM technology called Rapidly Adaptive Visualization Engine (RAVE).

## Prep:

1. Backup all of your RAVE chartspecs before starting!
2. All RAVE chartspecs are found in $LAHOME/AppFramework/chartspecs
3. All of the chartspecs are in a very specific JSON format.  Getting something out of whack is easy to do and likely will result in errors when attempting to render. 

## Hacks: 

* Hate the color scheme for the OOTB heat map?  I sure do!  Use this updated heatmap.json chartspec to get a more proper heat map color scheme with the normal green to red transitions.

