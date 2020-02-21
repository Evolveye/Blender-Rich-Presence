# Blender Rich Presence
 Adds Discord's rich presence system to Blender.

 Displays stuff like vertex and face count, project name, current render time, etc...<br>
 Please allow up to 15 seconds for it to update (it is made to be lightweight).

| State            | Presence preview |
| -----------------| ---------------- |
| Displays When Rendering and Elapsed Time  | ![img](https://cdn.discordapp.com/attachments/315215466215899146/680526000618340457/unknown.png) |
| Saved            | ![Saved](https://cdn.discordapp.com/attachments/315215466215899146/680526029923549255/unknown.png) |
| Not Saved        | ![Not Saved](https://cdn.discordapp.com/attachments/315215466215899146/680527483480965179/unknown.png) |
| Current Version  | ![Current Version](https://cdn.discordapp.com/attachments/315215466215899146/680526087989887017/unknown.png) |
| Disabled faces   | ![Disabled verts](https://cdn.discordapp.com/attachments/315215466215899146/680527097587826714/unknown.png) |
| Disabled verts and faces  | ![Disabled verts and faces](https://cdn.discordapp.com/attachments/315215466215899146/680526857073852440/unknown.png) |



# Installation
 1. Download this repository as a ZIP (top-right).<br>
 If you want to change visibility of shown vertices or faces, just change boolean values on top of `main_blender_rpc.py` file.<br>
 You will have to unzip files, change value, zip files again.
 2. Inside Blender, go to Preferences>Add-Ons.
 3. Press the Install button (top-right) and select the downloaded ZIP.
 4. Enable add-on (search or find under System category).

# Credits
Made by Woeful_Wolf, forked by me (Evolveye)

[![pypresence](https://img.shields.io/badge/using-pypresence-00bb88.svg?style=for-the-badge&logo=discord&logoWidth=20)](https://github.com/qwertyquerty/pypresence)
