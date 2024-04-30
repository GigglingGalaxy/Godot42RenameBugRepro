#First, set up is like this where second toon (Priestess) doesn't have AnimTree yet.
#Steps:
#1. copy/paste AnimTree from AnimationPlayer Scene to here.
#2. Then, copy node: AnimationPlayer from AnimationPlayer scene & paste here
#3. Note the copied/pasted one is named AnimationPlayer2.
#4. In this Priestess AnimTree in inspector, in the Anim Player path, 
#   click it and select AnimationPlayer2 node to 'reparent'
#5. Delete the original AnimationPlayer from this scene (Priestess scene)
#!!!!!warning read #6 now before executing bc that's where crash happens
#6. In Scene Tree hierarchy, click/enter or double click (tried both, same thing happens) 
#   on the name of node AnimationPlayer2 to rename it (goal is to remove the 2)
#   after crash, upon reopen, all works fine and the 2 is gone.

!!!Below is my Output as I was trying to put things in as they were in my original
NOTE LINE 100!!
Godot Engine v4.2.stable.mono.official (c) 2007-present Juan Linietsky, Ariel Manzur & Godot Contributors.
--- Debug adapter server started ---
--- GDScript language server started on port 6005 ---
New Scene Root
Create Node
Create Node
Reparent Node
Reparent Node
Set tree_root
Rename Node
Change type of node(s)
  scene/main/node.cpp:1437 - Condition "p_child->data.parent != this" is true.
  scene/resources/importer_mesh.cpp:518 - Ignoring face with non-finite normal in LOD generation.
res://PaladinMaleX_rgb.jpg: Texture detected as used in 3D. Enabling mipmap generation and setting the texture compression mode to VRAM Compressed (S3TC/ETC/BPTC).
res://PaladinMaleX_Normals.jpg: Texture detected as used as a normal map in 3D. Enabling red-green texture compression to reduce memory usage (blue channel is discarded).
res://PaladinMaleX_Normals.jpg: Texture detected as used as a roughness map in 3D. Enabling roughness limiter based on the detected associated normal map at res://PaladinMaleX_Normals.jpg.
res://PaladinMaleX_Normals.jpg: Texture detected as used in 3D. Enabling mipmap generation and setting the texture compression mode to VRAM Compressed (S3TC/ETC/BPTC).
res://PaladinMaleX_texture_kd_1.jpg: Texture detected as used in 3D. Enabling mipmap generation and setting the texture compression mode to VRAM Compressed (S3TC/ETC/BPTC).
res://PaladinMaleX_texture_kd_4.jpg: Texture detected as used in 3D. Enabling mipmap generation and setting the texture compression mode to VRAM Compressed (S3TC/ETC/BPTC).
res://PaladinMaleX_texture_kd_3.jpg: Texture detected as used in 3D. Enabling mipmap generation and setting the texture compression mode to VRAM Compressed (S3TC/ETC/BPTC).
res://PaladinMaleX_knight_texture.png: Texture detected as used in 3D. Enabling mipmap generation and setting the texture compression mode to VRAM Compressed (S3TC/ETC/BPTC).
res://PaladinMaleX_texture_kd.jpg: Texture detected as used in 3D. Enabling mipmap generation and setting the texture compression mode to VRAM Compressed (S3TC/ETC/BPTC).
Create Node
Set shape
Change type of node(s)
Instantiate Scene(s)
Make Local
Make node as Root
Reparent Node
Reparent Node
  core/string/node_path.cpp:234 - Condition "!p_np.is_absolute()" is true. Returning: NodePath()
Remove Node(s)
Set advance_expression_base_node
Set anim_player
  scene/animation/animation_node_state_machine.cpp:1572 - Index p_transition = 0 is out of bounds (transitions.size() = 0).
Add Node and Transition
Set settings/loop_mode
  scene/animation/animation_node_state_machine.cpp:1572 - Index p_transition = 1 is out of bounds (transitions.size() = 1).
Add Node and Transition
Add Transition
  scene/animation/animation_node_state_machine.cpp:928 - AnimationNodeStateMachinePlayback: parameters/playback aborts the transition by detecting one or more looped transitions in the same frame to prevent to infinity loop. You may need to check the transition settings. (User)
Set xfade_time
Set xfade_time
Set advance_mode
Set switch_mode
Set active
Change Animation Loop
res://PriestessX_rgb_12.jpg: Texture detected as used in 3D. Enabling mipmap generation and setting the texture compression mode to VRAM Compressed (S3TC/ETC/BPTC).
res://PriestessX_material_13.jpg: Texture detected as used in 3D. Enabling mipmap generation and setting the texture compression mode to VRAM Compressed (S3TC/ETC/BPTC).
res://PriestessX_Normals_11.jpg: Texture detected as used as a normal map in 3D. Enabling red-green texture compression to reduce memory usage (blue channel is discarded).
res://PriestessX_Normals_11.jpg: Texture detected as used as a roughness map in 3D. Enabling roughness limiter based on the detected associated normal map at res://PriestessX_Normals_11.jpg.
res://PriestessX_Normals_11.jpg: Texture detected as used in 3D. Enabling mipmap generation and setting the texture compression mode to VRAM Compressed (S3TC/ETC/BPTC).
res://PriestessX_Image_0_10.png: Texture detected as used in 3D. Enabling mipmap generation and setting the texture compression mode to VRAM Compressed (S3TC/ETC/BPTC).
res://PriestessX_rgb_9.jpg: Texture detected as used in 3D. Enabling mipmap generation and setting the texture compression mode to VRAM Compressed (S3TC/ETC/BPTC).
res://PriestessX_Normals_8.jpg: Texture detected as used as a normal map in 3D. Enabling red-green texture compression to reduce memory usage (blue channel is discarded).
res://PriestessX_Normals_8.jpg: Texture detected as used as a roughness map in 3D. Enabling roughness limiter based on the detected associated normal map at res://PriestessX_Normals_8.jpg.
res://PriestessX_Normals_8.jpg: Texture detected as used in 3D. Enabling mipmap generation and setting the texture compression mode to VRAM Compressed (S3TC/ETC/BPTC).
res://PriestessX_rgb_7.jpg: Texture detected as used in 3D. Enabling mipmap generation and setting the texture compression mode to VRAM Compressed (S3TC/ETC/BPTC).
res://PriestessX_Normals_6.jpg: Texture detected as used as a normal map in 3D. Enabling red-green texture compression to reduce memory usage (blue channel is discarded).
res://PriestessX_Normals_6.jpg: Texture detected as used as a roughness map in 3D. Enabling roughness limiter based on the detected associated normal map at res://PriestessX_Normals_6.jpg.
res://PriestessX_Normals_6.jpg: Texture detected as used in 3D. Enabling mipmap generation and setting the texture compression mode to VRAM Compressed (S3TC/ETC/BPTC).
res://PriestessX_rogue_texture.png: Texture detected as used in 3D. Enabling mipmap generation and setting the texture compression mode to VRAM Compressed (S3TC/ETC/BPTC).
res://PriestessX_Image_0.jpg: Texture detected as used in 3D. Enabling mipmap generation and setting the texture compression mode to VRAM Compressed (S3TC/ETC/BPTC).
res://PriestessX_Image_1.jpg: Texture detected as used in 3D. Enabling mipmap generation and setting the texture compression mode to VRAM Compressed (S3TC/ETC/BPTC).
res://PriestessX_rgb.jpg: Texture detected as used in 3D. Enabling mipmap generation and setting the texture compression mode to VRAM Compressed (S3TC/ETC/BPTC).
res://PriestessX_material.jpg: Texture detected as used in 3D. Enabling mipmap generation and setting the texture compression mode to VRAM Compressed (S3TC/ETC/BPTC).
res://PriestessX_Normals.jpg: Texture detected as used as a normal map in 3D. Enabling red-green texture compression to reduce memory usage (blue channel is discarded).
res://PriestessX_Normals.jpg: Texture detected as used as a roughness map in 3D. Enabling roughness limiter based on the detected associated normal map at res://PriestessX_Normals.jpg.
res://PriestessX_Normals.jpg: Texture detected as used in 3D. Enabling mipmap generation and setting the texture compression mode to VRAM Compressed (S3TC/ETC/BPTC).
Set settings/loop_mode
Toggle Visible
Toggle Visible
Toggle Visible
Toggle Visible
Toggle Visible
Toggle Visible
Toggle Visible
Toggle Visible
Toggle Visible
Rename Animation Library: ToonAnims
Save Animation library to File: ToonAnims
Make Animation Library Unique: ToonAnims
******* I THINK THIS IS THE PROBLEM SOMEHOW  Another resource is loaded from path 'res://ToonAnims.res' (possible cyclic resource inclusion).
Change type of node(s)
Set anim_player
Set anim_player
Set animation
Set animation
Paste Node(s) as Child of PriestessX
Set shape
Rename Node
Attach Script
Remove Animation Library: 
Add Animation Library: ToonAnims


