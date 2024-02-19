# BLENDER_TO_UE5_CHARACTER_TEMPLATE
Blender to UE5 Character template

This is a simple Blender scene file that includes Manny's base mesh and skeleton from UE5, from which I have removed all non-binding bones. Simply duplicate Manny's mnesh, and use it as template for your own character. Once you are done, bind it to the skeleton, and export it as FBX with "add lead bones" option UN-CHECKED. Finally, drop it into UE5 and choose Manny as the main skeleton.

#WARNING:

when dropping the final FBX into UE5 you will get warnings. Say NO to everything, to avoid a small but non-insignificant chance to corrupt your project's existing Manny skeleton, and cause UE5 to crash catastrophically.

