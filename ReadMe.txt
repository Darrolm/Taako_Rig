Taako Rig

To get started, just download the files into the correct folders of the Maya project you want to use and the textures should load without issue.

If you notice anything early on that you want added or see something that you feel should be different, let me know and I'll look at addressing it right away. I can easily be reached on Twitter @Darrolm

Taako model by Danny Sweeney


08 - 22 - 19

Version 0.8

Update: Rig now has face rig added in for animation. Visibility toggle for face, hair, hat, shawl, and shirt can also now be found on the Master control instead of split up. I also added a proximity toggle that applies to the hair, hat, and shirt controls so that they will be hidden until the cursor moves towards them.

Additionally, I've adjusted control colors a lot. I opted to switch the left and right colors while making the blue a bit lighter. I've also put in other colors in various places like the hair, hat, and auto controls.


06 - 25 - 19

Version 0.7

State of the rig:

- Core body rig is present with IK/FK limbs.

- Helper systems in place for the shawl, lower shirt, and the shirt cuffs. These systems have an auto function that is on by default but can be disabled or only partially used. The shawl's are on the Chest control, shirt on the CoG control, and cuffs on the Hand settings control. The cuff's control visibility is currently missing in this version.

- Hair control visibility can be toggled on the head control. 

- Glasses don't fold yet and are currently tied only to the hat while the hat is only in Head space.

- Space switch is there for the IK controls, the hat, glasses, UmbraStaff, and eye controls.

To-do List:
- Spine is currently just a 3 control FK chain which seems to suffice the rig.

- Add stretch options if desired by animators.

- Fully integrate the UmbraStaff into the Taako rig - There are current scaling issues when it comes to the shield geo.

- I want to add a squash to the puffy part of the sleeves for when the arms are at his side.

- The face rig hasn't even been started yet

- Rework Umbrastaff rig for stability. It is occasionally wonky at the moment.

- Set up controller tags 

- Potentially create a GUI with Python or PyQT.

- I'm open to suggestions and feedback.
