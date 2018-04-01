# Breezemite
Aurorae theme for KDE Plasma that mimics Yosemite window decoration, but with Breeze colors to match Breeze window theme.

### Installation:
Copy theme folders to `~/.local/share/aurorae/themes`

If you want to add a new colorscheme to this theme, feel free to send a PR, I'll prepare a package for KDE Store, and tag you as author here, and in the package name, so all color variants will be able via single store page, and same repository.

![Breezemite](https://cn.pling.com/img/6/6/d/d/5ee0d8f29801ecd2f6c418d05b4c77d6173a.png)
[KDE Store](https://store.kde.org/p/1169286/)

## F.A.Q.

**Q.** My borders are oversized!  
**A.** Check if you're using **display scaling**, or especially **font scaling**. This theme is sensitive to them (my fault)

**Q.** Titlebar is transparent!  
**A.** Youre usind **HiDPI** dipllay, right? check [this issue](https://github.com/andreyorst/Breezemite/issues/4#issuecomment-295890785) for solution. If not, open new issue and I'll try to help you

**Q.** No shade (roll up) button!  
**A.** Yes. No shade button. It is bugged in aurorae theme engine.

**Q.** Damn, draggable area of borders is 1px!  
**A.** Yes, i know, [this it what matters](https://www.youtube.com/watch?v=4MycEcQOSzc). [Check this issue](https://github.com/andreyorst/Breezemite/issues/2)

**Q.** Icon for title bar Application Menu button is missing!  
**A.** Check [this](https://github.com/andreyorst/Breezemite/issues/5) issue for explanations.

**Q.** Incorrect Application Menu position!  
**A.** I personally recommend you to use this theme with application menu widget, since it is a mac style theme. But check [this](https://github.com/andreyorst/Breezemite/issues/6) issue for explanations.

## 

Due the limitation of aurorae engine active development of this theme stopped. Since I can't do much about issuers listed in **F.A.Q.** sections I will only accept PRs with color variants, and try to help with issues that can be solved by tweaking `rc` file. I'm thinking about diving into real breeze to create a patch, that adds Mac Os style buttons to it, and maybe some modifications to kwin, to add rounded corners to borderless windows, but that's nearly not a near future.

If you re interested in theme visually similar to Breezemite take a look on the theme from [Igor Shovkun](https://github.com/ishovkun). It has all features which are missing in breezemite. [SierraBreeze](https://github.com/ishovkun/SierraBreeze).
