# FlourishingFoilage

This is an automated Minecraft Forge mod template.

Expected directory structure before run:
* newmod.sh (from Git repo other/util/newmod.sh)
* newmod (optional)
   * newmod.cfg (from Git repo other/util/newmod.cfg with options you've modified)
   * private.properties (optional)

Running ```newmod.sh NewMod``` will then create:

* NewModWorkspace
   * NewMod (local git repo for new mod with remote origin set)
      * (expected base Mod files)
      * Modify build.properties and private.properties
   * NewMod.wiki (local git repo for new mod's wiki with remote origin set)

## Notes

* To debug, '''cp build/resources/main/mcmod.info src/resources/mcmod.info''' beforehand since debugger does not run build with gradle string replacement.  Then '''git checkout src/resources/mcmod.info''' afterward to revert back to generated mcmod.info template.
