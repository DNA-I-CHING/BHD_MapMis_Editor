This project ports the map editor from Delta Force: Black Hawk Down, released in 2003 by NovaLogic, into a simple HTML file using Three.js. We can keep it as a web app or later migrate it to something simple like Electron, or another platform that makes it easy to reuse and build on the existing work.

Todo:
- [x] 3D terrain rendering
- [x] Items conversion from .3DI to .GLB
- [x] General Information
- [X] Waypoints
- [X] Layer Names
- [X] Groups
- [ ] 90% - Item Attributes
- [ ] 90% - Area Triggers
- [ ] 60% - Item context menu
- [ ] Canvas context menu
- [ ] Briefing
- [ ] Events
- [ ] Global Replace
- [ ] Weapon Loadouts

itemsDef.js works similarly to the original items.def.  
otheritems.js lists all the items that aren’t in items.def by default and also uses new variables to indicate which 3D .glb file will be used for the item.

All 3D .glb items should be in the resources/3d_items folder, and you should download the items here: https://drive.google.com/file/d/1Ra4pI8aTDwG5vO3h0fLZYzqPM6YveKQH/view?usp=sharing

## Keep working on it.
Feel free to continue what’s already been done. 

## Contributors so far
biggy, Demonic, dataspiller, Scott (NovaHQ), AngelExalted
