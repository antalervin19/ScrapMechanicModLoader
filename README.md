# ScrapMechanicModLoader
This is a work-in-progress ScrapMechanic (SM) mod-loader, capable of changing (Loading) the mods that are not game but file mods.

# DOWNLOAD-INSTALL
To use it Download the latest release, unzip-it.
Run the ScrapMechanicModLoader.exe, and wait.
A window should popup, and there you should be able to install mods.

# MOD-CREATION
To make mods create a folder in the `"./Downloads"`.
In the newly created mod folder create a Mod.content file

Mod.content: `{"title":"ExampleMod","description":"This is an example file mod.","author":"ExampleModAuhor","date":"2024-12-09","version":"1.0.0."}`

After creating the Mod.content file, you can add additional files and name then accordingly;

`OriginalFileName.OriginalFileExtension.org` for the unmodified game files
&
`OriginalFileName.OriginalFileExtension.mod` for the modified game files

Example: 
`BasePlayer.lua.org`
`BasePlayer.lua.mod`