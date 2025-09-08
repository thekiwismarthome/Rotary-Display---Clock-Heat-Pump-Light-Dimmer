# Rotary-Display - Clock | Heat Pump | Light Dimmer Control
This uses the Rotary Display and has a Clock, Heat pump and Light Dimmer control

## THIS IS STILL BEING DEVELOPPED.  THE CODE IS SHIT - TO BE TIDIED UP

## Quck visual of what I have created
ADD PICTURES HERE

ADD VIDEO HERE

There are some aspects of the main file missing, I use a common.yaml file, you can use as many as you like, I'll probably split out fonts and  a few other items as well to clean the mess up TBC...

I have added this into the code, <<: !include common.yaml

It includes the following

logger: |
api: |
ota: |
wifi: |
ap: |
button: |
text_sensor:

These are all the common/reusable settings I use for all projects.  To create this just create a new device but without all the extra crap and place what you wnat in there.  This can be placed elsewhere in the file structure, but I leave it here for easy access.



.
