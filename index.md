# AppImage appears in 8 of 14 Manjaro posts: 6 Loading / startup, 1 Other, 1 Crashing; Shotcut, FreeCAD, libicuuc.so.76, and libwebkit2gtk-4.0.so.37 accompany it.

Manjaro Forum users post third-party software problems, and each post carries replies, views, and tags. The posts name many applications, and counts alone cannot show which one recurs. Two Forum searches return 14 topics: eight by category and six by entity. Two of 8 category topics show Shotcut and FreeCAD AppImages failing at Loading / startup. AppImage appears in all 6 entity topics: 4 Loading / startup, 1 Other, and 1 Crashing. Two of four entity-sample Loading / startup topics name shared libraries: libicuuc.so.76 and libwebkit2gtk-4.0.so.37. These counts show correlation between entities and problem states, not cause.

> *Reply counts measure discussion, and they hint at user interest or support demand. Reply counts do not prove the frequency, severity, or technical significance of any problem. These priorities name topics to study, not places to spend resources. Engineers must weigh evidence from operations to judge each priority and choose a response. Reply counts are observations, support demand is an inference, and problem severity is a separate judgment.*

---

## Shotcut and FreeCAD fail to start from AppImage files in posts 49 and 2, both Loading / startup.

**Situation:** Eight Manjaro Forum topics in the Third-Party Software category name 13 entities and five problem states.

**Complication:** Which entity recurs across the eight topics, and under which problem state?

**Resolution:** AppImage recurs in topics 49 and 2, and both place it under Loading / startup.

| Sample number | Topic | Replies | Views | Tags | Named Entity 1 | Named Entity 2 | Problem |
|---|---|---|---|---|---|---|---|
| 49 | Appimage load error (Shotcut) | 38 | 638 | AppImage | Shotcut | | Loading / startup |
| 6 | Is it possible to install and run Python 3.11 script in virtual environment? | 17 | 3137 | plasma | Python | Python 3.11 | Other |
| 70 | Firefox addon:Open in VLC media player? | 16 | 621 | Firefox | VLC | | Incorrect output / behaviour |
| 51 | Are there instructions for how to build from source when a package is not in the repository? | 15 | 834 | package | repository | | Installation / updating / removal |
| 2 | Freecad appimage fails to start after update | 13 | 227 | FreeCAD | AppImage | | Loading / startup |
| 34 | Cannot build OpenShot | 12 | 487 | OpenShot | | | Installation / updating / removal |
| 56 | How do I install "debug package" of kwin? | 12 | 224 | plasma | KWin | | Installation / updating / removal |
| 16 | Zombied programs refuse to close with SIGKILL/SIGCHLD | 11 | 195 | SIGKILL | SIGCHLD | | Freezing / unresponsiveness |

> *TAB1: Category sample ranked by replies; subject lines supply entities and problem states.*

```
.
└── Third-Party Software Category Search Results/
    ├── Loading / startup/
    │   ├── AppImage
    │   ├── Shotcut
    │   └── FreeCAD
    ├── Other/
    │   ├── Python
    │   └── Python 3.11
    ├── Incorrect output / behaviour/
    │   ├── Firefox
    │   └── VLC
    ├── Installation / updating / removal/
    │   ├── package
    │   ├── repository
    │   ├── OpenShot
    │   └── KWin
    └── Freezing / unresponsiveness/
        ├── SIGKILL
        └── SIGCHLD
```

> *DIA1: Category sample entities grouped under five problem states.*

---

## AppImage appears in all six entity-search posts: four Loading / startup, one Other, and one Crashing.

**Situation:** Six forum topics from the entity search name five entities and three problem states.

**Complication:** Which entity recurs across the six rows, and under which problem states?

**Resolution:** AppImage appears in all six rows and attaches to Loading / startup, Other, and Crashing.

| Sample number | Topic | Replies | Views | Tags | Named Entity 1 | Named Entity 2 | Problem |
|---|---|---|---|---|---|---|---|
| 2 | Appimage will not launch, missing "libicuuc.so.76" | 15 | 110 | appimage | AppImage | libicuuc.so.76 | Loading / startup |
| 3 | AppImages kann ich nicht mehr öffnen | 14 | 333 | appimage | AppImage | | Loading / startup |
| 4 | Pcsx2 appimage (execv error: No such file or directory) | 9 | 930 | appimage | PCSX2 | AppImage | Loading / startup |
| 6 | Automate update checks for externally downloaded software (in .tar.gz or .AppImage) | 9 | 319 | bash; script; appimage | AppImage | | Other |
| 7 | Appimage - error while loading shared libraries: libwebkit2gtk-4.0.so.37 | 8 | 9092 | appimage | AppImage | libwebkit2gtk-4.0.so.37 | Loading / startup |
| 8 | AppImage can't find hicolor icon theme | 2 | 590 | none | AppImage | hicolor | Crashing |

> *TAB2: Entity sample ranked by replies; subject lines supply entities and problem states.*

---

## libicuuc.so.76 and libwebkit2gtk-4.0.so.37 appear beside AppImage in posts 2 and 7, two of four Loading / startup posts.

**Situation:** The entity tree groups five entities under three problem states: Loading / startup, Other, and Crashing.

**Complication:** Which entities sit under Loading / startup, and which of them are files rather than applications?

**Resolution:** Loading / startup holds AppImage, PCSX2, libicuuc.so.76, and libwebkit2gtk-4.0.so.37; two of them are shared libraries.

```
.
└── Third-Party Software Entity Search Results/
    ├── Loading / startup/
    │   ├── AppImage
    │   ├── libicuuc.so.76
    │   ├── PCSX2
    │   └── libwebkit2gtk-4.0.so.37
    ├── Other: AppImage
    └── Crashing/
        ├── AppImage
        └── hicolor
```

> *DIA2: Entity sample entities grouped under three problem states.*
