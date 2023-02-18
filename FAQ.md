# Frequently asked Questions
**Before opening an issue or asking anywhere else, please read this carefully.**
<br>
<br>

### Q: Where can I download Discord Oxygen?
**A:** You can't. Its not released yet.

### Q: Will there be a free tier?
**A:** Yes, but it will be released later than the patron-only version.

### Q: Is Discord Oxygen Open Source?
**A:** I'd really like to open-source it, but unfortunatley I can't. There are several reasons I have to do this:
1. Discord could fix the exploits immediatley if they had the source code.
2. I don't want skids to copy it, I'd loose control over the code and skids would probably insert token loggers into the script.
3. If some exploits would fall into the wrong hands, many Communites and Servers could be destroyed. Just imagine what would happen if every Account gets hacked and every Server raided. That wouldn't be good for anyone.
4. I spend lots of time working on this project, I don't want some skids taking credit for my work

### Q: What data does Discord Oxygen collect?
**A:** The only data that will be stored is on what accounts a certain license is activated.<br>
It looks similar to this: `License xyz: 000000000000000000, 000000000000000000`.<br>
If more than the maximum allowed IDs register one a certain license key, the authentication will fail and the license key is deactivated.<br>
No other data is ever collected.

### Q: Crossplatform?
**A:** Yes. Discord Oxygen compiles to native javascript which can be run by most modern Browsers. The Discord Desktop app is more or less Google Chrome ([Electronjs](https://github.com/electron/electron)) displaying the same website as the web version + some added tracking + features that would work on web perfectly well re-enabled. Discord Oxygen includes some patches which re-enable some of the "Desktop exclusive" features on web.
Besides the browser version of Discord Oxygen there will be installers for Linux, Windows, maybe BSD and a flake/module/overlay for NixOS.
All the installer code will be GPL, so feel free to add your own platform if not supported yet.

### Q: Are there any other undocumented features not included on this list?
**A:** Possibly. The patron-only version always receives the latest exploits, as soon as they are discovered. And the feature list already is really long, it just makes sense to not include every single Feature in the readme.

### Q: niTro HaCk wHeRe?
**A:** Discord Oxygen is the sucessor of "nitro hack". The original script (which was spagetti-code anyways) is *patched*, that's why I made Discord Oxygen, which is meant to be *unpatchable* or at least easy to maintain / fix if Discord tries patching it.<br>
And because so many people keep asking this question, I translated it to skid language:<br>
<img src="https://user-images.githubusercontent.com/91915462/187090116-95d9fd68-3024-40ce-86aa-3003fac7bd2d.png" width=500px alt="Nitro Hack, Discord Oxygen, they're the same picture" />
