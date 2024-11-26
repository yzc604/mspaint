# mspaint
> [!IMPORTANT]
> This script is now depericated

A decent script hub that *was* free and open source

```lua
-- THIS IS THE OLD SCRIPT, WE DO NOT ADVISE YOU USING THIS AS OVER TIME STUFF WILL GET PATCHED
loadstring(game:HttpGet("https://raw.githubusercontent.com/notpoiu/mspaint/main/main.lua"))()
```

**Links**:
- [🌐 Website](https://www.mspaint.cc/)
- [💬 Discord](https://discord.gg/mspaint)

# Addons
You can find documentation on how to create an addon here: https://docs.upio.dev/mspaint/addons/getting_started

# Website
our website is at https://www.mspaint.cc (source code here at https://github.com/notpoiu/webmspaint)

## Bundling mspaint via wax
To bundle all the scripts, you have to follow these steps:

1. Install [rokit](https://github.com/rojo-rbx/rokit) if you haven't already
2. Open Powershell or the command-line shell of your liking and [cd to this repository](https://www.quora.com/What-does-it-mean-to-CD-into-a-directory-and-how-can-I-do-that-Can-someone-explain-it-in-a-laymans-term)
3. Run `rokit install` and wait for it to install all the dependencies
4. Run `lune run Build bundle input='default.project.json' minify=false output='Distribution/Script.luau' env-name="Script" darklua-config-path="Build/DarkLua.json" temp-dir-base="Distribution" verbose=true`

You can find the bundled script in `/Distribution/Script.luau`.
