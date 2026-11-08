# awesome-native

> A curated collection of open-source native GUI applications.

This list focuses on open-source desktop software built with native
operating-system APIs or native desktop toolkits such as
**Cocoa/AppKit, Win32/WinUI, GTK, and Qt/KDE**.
The goal is to find fast, integrated alternatives to Electron-heavy desktop
applications.

## Contents

- [Editors and terminals](#editors-and-terminals)
- [Reading and libraries](#reading-and-libraries)
- [Media](#media)
- [Files and system tools](#files-and-system-tools)
- [Productivity](#productivity)
- [Development](#development)
- [Graphics and creation](#graphics-and-creation)
- [Communication and remote access](#communication-and-remote-access)
- [Games](#games)
- [Excluded from this list](#excluded-from-this-list)
- [Contributing](#contributing)

## Editors and terminals

| Application | Platform | Toolkit / implementation | Repository |
| --- | --- | --- | --- |
| [Zed](https://zed.dev/) | macOS, Linux | Rust, GPU-native rendering | [zed-industries/zed](https://github.com/zed-industries/zed) |
| [Lite XL](https://lite-xl.com/) | Windows, macOS, Linux | C and Lua | [lite-xl/lite-xl](https://github.com/lite-xl/lite-xl) |
| [Lapce](https://lapce.dev/) | Windows, macOS, Linux | Rust | [lapce/lapce](https://github.com/lapce/lapce) |
| [Ghostty](https://ghostty.org/) | macOS, Linux | Native platform integrations | [ghostty-org/ghostty](https://github.com/ghostty-org/ghostty) |
| [Konsole](https://konsole.kde.org/) | Linux | Qt/KDE | [KDE/konsole](https://invent.kde.org/utilities/konsole) |
| [GNOME Console](https://apps.gnome.org/Console/) | Linux | GTK | [GNOME kgx](https://gitlab.gnome.org/GNOME/kgx) |
| [Kitty](https://sw.kovidgoyal.net/kitty/) | macOS, Linux | Native GPU rendering | [kovidgoyal/kitty](https://github.com/kovidgoyal/kitty) |

## Reading and libraries

| Application | Use | Toolkit / implementation | Repository |
| --- | --- | --- | --- |
| [Okular](https://okular.kde.org/) | PDF and document reader | Qt/KDE | [KDE/okular](https://invent.kde.org/graphics/okular) |
| [Evince](https://apps.gnome.org/Evince/) | PDF and document reader | GTK | [GNOME evince](https://gitlab.gnome.org/GNOME/evince) |
| [Calibre](https://calibre-ebook.com/) | Ebook library and conversion | Qt | [kovidgoyal/calibre](https://github.com/kovidgoyal/calibre) |
| [JabRef](https://www.jabref.org/) | BibTeX/reference management | Java desktop UI | [JabRef/jabref](https://github.com/JabRef/jabref) |
| [Tellico](https://tellico-project.org/) | Collection and bibliography management | Qt/KDE | [KDE/tellico](https://invent.kde.org/office/tellico) |
| [YACReader](https://www.yacreader.com/) | Comic and manga reader | Qt | [YACReader/yacreader](https://github.com/YACReader/yacreader) |
| [MComix](https://sourceforge.net/projects/mcomix/) | Comic and manga reader | GTK | [MComix/mcomix](https://sourceforge.net/p/mcomix/git/) |

> Zotero is intentionally not listed as a strict native-toolkit application.
> It uses Mozilla/XUL technologies rather than GTK, Qt, Cocoa, or WinUI.

## Media

| Application | Use | Toolkit / implementation | Repository |
| --- | --- | --- | --- |
| [mpv](https://mpv.io/) | Video player | Native rendering backend | [mpv-player/mpv](https://github.com/mpv-player/mpv) |
| [Celluloid](https://celluloid-player.github.io/) | GTK frontend for mpv | GTK | [celluloid-player/celluloid](https://github.com/celluloid-player/celluloid) |
| [IINA](https://iina.io/) | macOS video player | Cocoa/Swift | [iina/iina](https://github.com/iina/iina) |
| [Strawberry](https://www.strawberrymusicplayer.org/) | Music library and player | Qt | [strawberrymusicplayer/strawberry](https://github.com/strawberrymusicplayer/strawberry) |
| [nomacs](https://nomacs.org/) | Image viewer | Qt | [nomacs/nomacs](https://github.com/nomacs/nomacs) |
| [digiKam](https://www.digikam.org/) | Photo management | Qt/KDE | [KDE/digikam](https://invent.kde.org/graphics/digikam) |
| [darktable](https://www.darktable.org/) | RAW photo workflow | GTK | [darktable-org/darktable](https://github.com/darktable-org/darktable) |

## Files and system tools

| Application | Use | Toolkit / implementation | Repository |
| --- | --- | --- | --- |
| [Dolphin](https://apps.kde.org/dolphin/) | File manager | Qt/KDE | [KDE/dolphin](https://invent.kde.org/system/dolphin) |
| [GNOME Files](https://apps.gnome.org/Nautilus/) | File manager | GTK | [GNOME nautilus](https://gitlab.gnome.org/GNOME/nautilus) |
| [Filelight](https://apps.kde.org/filelight/) | Disk usage visualizer | Qt/KDE | [KDE/filelight](https://github.com/KDE/filelight) |
| [Ark](https://apps.kde.org/ark/) | Archive manager | Qt/KDE | [KDE/ark](https://invent.kde.org/utilities/ark) |
| [GParted](https://gparted.org/) | Partition manager | GTK | [GNOME gparted](https://gitlab.gnome.org/GNOME/gparted) |
| [CopyQ](https://hluk.github.io/CopyQ/) | Clipboard manager | Qt | [hluk/CopyQ](https://github.com/hluk/CopyQ) |
| [Flameshot](https://flameshot.org/) | Screenshot tool | Qt | [flameshot-org/flameshot](https://github.com/flameshot-org/flameshot) |

## Productivity

| Application | Use | Toolkit / implementation | Repository |
| --- | --- | --- | --- |
| [LibreOffice](https://www.libreoffice.org/) | Office suite | Native desktop toolkit | [LibreOffice/core](https://github.com/LibreOffice/core) |
| [GIMP](https://www.gimp.org/) | Raster image editing | GTK | [GNOME/gimp](https://gitlab.gnome.org/GNOME/GIMP) |
| [Qalculate!](https://qalculate.github.io/) | Calculator | GTK/Qt frontends | [qalculate/qalculate-gtk](https://github.com/Qalculate/qalculate-gtk) |
| [Task Coach](https://www.taskcoach.org/) | Task management | wxWidgets | [frits/taskcoach](https://github.com/frits/taskcoach) |
| [KeePassXC](https://keepassxc.org/) | Password manager | Qt | [keepassxreboot/keepassxc](https://github.com/keepassxreboot/keepassxc) |

## Development

| Application | Use | Toolkit / implementation | Repository |
| --- | --- | --- | --- |
| [SQLiteBrowser](https://sqlitebrowser.org/) | SQLite database GUI | Qt | [sqlitebrowser/sqlitebrowser](https://github.com/sqlitebrowser/sqlitebrowser) |
| [GitAhead](https://gitahead.github.io/gitahead.com/) | Git client | Qt | [gitahead/gitahead](https://github.com/gitahead/gitahead) |
| [ImHex](https://imhex.werwolv.net/) | Hex editor | Native C++ UI | [WerWolv/ImHex](https://github.com/WerWolv/ImHex) |
| [Wireshark](https://www.wireshark.org/) | Network analysis | Qt/GTK | [wireshark/wireshark](https://github.com/wireshark/wireshark) |
| [FreeCAD](https://www.freecad.org/) | Parametric CAD | Qt | [FreeCAD/FreeCAD](https://github.com/FreeCAD/FreeCAD) |

## Graphics and creation

| Application | Use | Toolkit / implementation | Repository |
| --- | --- | --- | --- |
| [Krita](https://krita.org/) | Digital painting | Qt | [KDE/krita](https://invent.kde.org/graphics/krita) |
| [Inkscape](https://inkscape.org/) | Vector graphics | GTK | [inkscape/inkscape](https://github.com/inkscape/inkscape) |
| [Blender](https://www.blender.org/) | 3D creation | Native C/C++ UI | [blender/blender](https://github.com/blender/blender) |
| [Audacity](https://www.audacityteam.org/) | Audio editing | wxWidgets | [audacity/audacity](https://github.com/audacity/audacity) |
| [Kdenlive](https://kdenlive.org/) | Video editing | Qt/KDE | [KdenLive/KdenLive](https://github.com/KDE/kdenlive) |
| [OBS Studio](https://obsproject.com/) | Recording and streaming | Qt | [obsproject/obs-studio](https://github.com/obsproject/obs-studio) |

## Communication and remote access

| Application | Use | Toolkit / implementation | Repository |
| --- | --- | --- | --- |
| [RustDesk](https://rustdesk.com/) | Remote desktop | Native desktop clients | [rustdesk/rustdesk](https://github.com/rustdesk/rustdesk) |
| [Remmina](https://remmina.org/) | Remote desktop client | GTK | [remmina/remmina](https://github.com/remmina/remmina) |

## Games

| Application | Use | Toolkit / implementation | Repository |
| --- | --- | --- | --- |
| [Lutris](https://lutris.net/) | Game manager | GTK | [lutris/lutris](https://github.com/lutris/lutris) |

## Excluded from this list

The following are useful applications, but do not meet the strict native-toolkit
criterion used here:

- Electron applications such as VS Code, Obsidian, Joplin, Discord, and Postman
- Browser-based wrappers and most webview applications
- Applications whose native-looking shell still renders its main interface with HTML/CSS

“Native” here refers to the GUI technology, not merely whether an application
has a desktop binary. A project may still use cross-platform code, GPU
rendering, or a scripting layer while retaining a native desktop interface.

## Contributing

Please open a pull request with:

1. The application name and official website
2. Supported platforms
3. The GUI toolkit or implementation
4. The official source repository and its license
5. A short explanation of why it meets the native-toolkit criterion

Avoid adding duplicates, web wrappers, or applications only because they ship
as a desktop download.
