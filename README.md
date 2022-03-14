# eaglercraft-plugins
A list of Bukkit plugins tested and compatible with Eaglercraft

Every plugin has a folder, the folder contains the JAR file containing the plugin which you can copy to your bukkit server's `/plugins` directory and the folder also contains the configuration directory containing the configuration recommended for using the plugin with Eaglercraft which you can also copy (the folder not the files inside) into your `/plugins` directory.

To make things easier, every plugin has a ZIP file in it's directory so you can easily download both the plugin and all of it's config files in basically a single click

**If you are looking to keep your server as secure as possible, do not use the existing config directory for the plugin you download and create your own instead, I cannot guarantee that the config files provided for each plugin will be safe and secure to use on all public servers**

To add a plugin, create a pull request containing the new plugin and it's configuration directory but **do not include a ZIP file** because I will create the ZIP myself to ensure it actually contains the same legitimate plugin and config files reviewed in the pull request

### Plugin Descriptions:

- **AuthMe** adds the `/register` and `/login` commands to your server

- **BitchFilter** is a **VERY IMPORTANT SECURITY FEATURE** to prevent people from gaining `/op` by logging in as 'laX1DUDE' or 'LaX1DuDE' if 'LAX1DUDE' is the username in the `ops.txt`. **USE YOUR BRAIN AND READ: [/BitchFilter/readme.txt](https://github.com/LAX1DUDE/eaglercraft-plugins/blob/main/BitchFilter/readme.txt) DO NOT IGNORE THIS MESSAGE**

- **Clearlag** deletes all dropped items every ~6 minutes (can be changed) and helps disable lag machines

- **Essentials** adds `/tpa` and `/sethome` and `/warp` and like 50 admin commands

- **InstantLeafDecay** speeds up leaf decay when you mine a tree

- **IPortal** allows players to use portals to switch servers without using the `/server` command

- **Multiverse** allows you to add more worlds to a server besides the overworld/nether/end

- **NoCheatPlus** deters any players from using your server to develop hacked clients

- **NoSpawnPVP** disables PVP in the server's `spawn-protection` radius set in `server.propeties`

- **PermissionsBukkit** allows you to create different roles for different specific groups of players on your server to allow a different configurable list of commands for each player. It allows you to have different ranks for every player on the server instead just using `/op` for every single person that wants to be a moderator on your server, or someone who wants to use like one specific command that they can't use without giving them `/op` and hoping they won't just randomly destroy your whole server

- **tpLogin** teleports players back to a specific location every time they log in

- **WorldEdit** allows you to build very large structures on your server in a very short amount of time using commands