Each text file has everything it needs to work.
There should be no problems, and I'll update it and add new codes to it weekly.
If you dont understand and need help dm me on discord.
My discord: ඞ7855ඞ#7855
Or just add me on steam idrc.
------------------------------------------------------------
Make sure if you downloaded a script from a text file, you dont
edit the name or the code in it, and make sure you add it to MOD api,
Example:

{
  "Name": "MOD NAME HERE",
  "Author": "OWNER HERE",
  "Description": "DESCRIPTION HERE",
  "ModVersion": "1.22.2",
  "GameVersion": "1.18+",
  "ThumbnailPath": "THUMBNAIL HERE.png",
  "EntryPoint": "Mod.Mod",
  "Tags": [
    "Fun"
  ],
  "Scripts": [
    "npc.cs",
    "CategoryBuilder.cs",
    "script.cs"
  ],
  "Active": true,
  "UGCIdentity": null,
  "CreatorUGCIdentity": "2655118542"
}

-----------------------------------------------------------------------

When you add another script to the Mod api, make sure you
have a "," after the script before it, or else it wont read the script.

-----------------------------------------------------------------------

  "EntryPoint": "Mod.Mod",

It's a good idea to have your entry point as Mod.Mod as most scripts use this.

-----------------------------------------------------------------------
