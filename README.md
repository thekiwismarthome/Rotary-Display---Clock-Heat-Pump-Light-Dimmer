# Rotary Display - Clock | Heat Pump | Light Dimmer Control
This uses the Rotary Display and has a Clock, Heat pump and Light Dimmer control

## THIS IS STILL BEING DEVELOPPED.  THE CODE IS SHIT - TO BE TIDIED UP
# TODO LIST

### Todo

- [ ] fix timeout for screen burn #Bug
- [ ] add Weather Page
- [ ] add visualisation Video
- [ ] add Visualisation images
- [ ] Update documentation with explanations
- [ ] light on clock page does not go to grey when light switched off #Bug
- [ ] add HA option to change background #Enhancement
- [ ] add option to add/remove min & hr hands #Enhancement
- [ ] add option to renoce digitalk clock #Enhancement
- [ ] LOADS more! TBC
- [ ] CLEANUP CODE!! Seriously!

### In Progress

- [ ] add Weather Page 

### Done ✓

- [x] change weather image on clock screen (100x100)
## Quck visual of what I have created
ADD PICTURES HERE

ADD VIDEO HERE

There are some aspects of the main file missing, I use a common.yaml file, you can use as many as you like, I'll probably split out fonts and  a few other items as well to clean the mess up TBC...

I have added this into the code, <<: !include common.yaml

It includes the following

logger: | api: | ota: | wifi: | ap: | button: | text_sensor:

These are all the common/reusable settings I use for all projects.  To create this just create a new device but without all the extra crap and place what you wnat in there.  This can be placed elsewhere in the file structure, but I leave it here for easy access.



.
