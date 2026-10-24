---
layout: default
title: macOS File Managers Compared
---

# macOS File Managers Compared

Ferry, Commander One, Nimble Commander, Marta, Path Finder, ForkLift, QSpace Pro, muCommander, Double Commander and Finder, checked against each developer's site, changelog, App Store listing and Homebrew on 24 Oct 2026.

Key: ✅ yes · ◐ partial · ❌ no · ? not documented (not the same as missing)

## Price and platform

| App | Price | Model | Latest | Min macOS | Open source |
|:--|:--|:--|:--|:--|:--|
| [Ferry](https://ferry.indus3.org/) | $14.99 lifetime / $9.99 per year (early-adopter, to 31 Dec 2026) | One-time or annual | 1.10 (Oct 2026) | 14 Sonoma | No |
| [Commander One](https://commander-one.com/) | Free; PRO Pack $29.99 (1 Mac), $99.99 (5 Macs) | Freemium, one-time PRO | 3.18 (25 Sep 2026) | 10.13 | No |
| [Nimble Commander](https://magnumbytes.com/) | Free | Free | 1.8.0 (Dec 2025) | 11 | Yes (GPL-3.0) |
| [Marta](https://marta.sh/) | Free beta; paid licence planned at 1.0 | Free (for now) | 0.8.2 (Jul 2024) | 11 | No |
| [Path Finder](https://www.cocoatech.io/) | $29.95 per year | Subscription | 26.1.10 (Oct 2026) | 13 | No |
| [ForkLift](https://binarynights.com/) | $19.95 single, $29.95 family (1 yr updates) | One-time, updates expire | 4.7.7 (20 Oct 2026) | 14.6 | No |
| [QSpace Pro](https://qspace.awehunt.com/en-us/index.html) | $13.99 sale ($29.99 regular) + paid add-ons | One-time + add-ons | 7.0.4 (7 Oct 2026) | 10.15 | No |
| [muCommander](https://www.mucommander.com/) | Free | Free | 1.6.2 (14 May 2026) | 13 (older DMG for 10.15 and earlier) | Yes (GPL-3.0) |
| [Double Commander](https://doublecmd.sourceforge.io/) | Free | Free | 1.2.9 (27 Sep 2026) | 11 | Yes (GPL-2.0+) |
| [Finder](https://support.apple.com/en-us/109033) | Free (bundled) | Bundled with macOS | macOS 27.0.1 (28 Sep 2026) | 27 (Apple Silicon only) | No |

## Remote protocols and cloud

| App | FTP | SFTP | WebDAV | SMB | S3 | Google Drive | Dropbox | OneDrive |
|:--|:--|:--|:--|:--|:--|:--|:--|:--|
| [Ferry](https://ferry.indus3.org/) | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ | ❌ | ❌ |
| [Commander One](https://commander-one.com/) | ✅ PRO | ✅ PRO | ✅ PRO | ◐ | ✅ PRO | ✅ PRO | ✅ PRO | ✅ PRO |
| [Nimble Commander](https://magnumbytes.com/) | ✅ | ✅ | ✅ | ◐ mounts shares | ❌ | ❌ | ❌ removed in 1.8 | ❌ |
| [Marta](https://marta.sh/) | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ |
| [Path Finder](https://www.cocoatech.io/) | ◐ upload | ◐ upload | ? | ◐ via macOS | ◐ upload | ◐ upload | ◐ upload | ? |
| [ForkLift](https://binarynights.com/) | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| [QSpace Pro](https://qspace.awehunt.com/en-us/index.html) | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| [muCommander](https://www.mucommander.com/) | ✅ | ✅ | ? | ✅ | ✅ | ✅ | ✅ | ✅ plugin |
| [Double Commander](https://doublecmd.sourceforge.io/) | ✅ | ✅ | ◐ plugin | ◐ via macOS | ✅ | ❌ | ✅ | ✅ |
| [Finder](https://support.apple.com/en-us/109033) | ◐ read-only | ❌ | ✅ | ✅ | ❌ | ◐ via Google's app | ◐ via Dropbox app | ◐ via OneDrive app |

## Interface and file operations

| App | Panes | Terminal | Archive browse | Compare | Sync | Batch rename | Editor |
|:--|:--|:--|:--|:--|:--|:--|:--|
| [Ferry](https://ferry.indus3.org/) | Dual | ◐ command line under panels | ✅ ZIP, 7z, RAR, TAR, nested | ✅ | ❌ compare, then copy | ✅ regex, undo | ✅ Markdown + code |
| [Commander One](https://commander-one.com/) | Dual | ✅ PRO | ✅ | ❌ | ❌ | ❌ | ❌ viewer only |
| [Nimble Commander](https://magnumbytes.com/) | Dual | ✅ direct build | ✅ about 30 formats | ❌ | ❌ | ✅ | ❌ viewer only |
| [Marta](https://marta.sh/) | Dual | ✅ | ✅ | ❌ | ❌ | ? | ❌ |
| [Path Finder](https://www.cocoatech.io/) | Single or dual | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ text, RTF, hex |
| [ForkLift](https://binarynights.com/) | Dual | ❌ opens external terminal | ✅ | ✅ | ✅ one- or two-way | ✅ regex, metadata | ✅ local and remote |
| [QSpace Pro](https://qspace.awehunt.com/en-us/index.html) | Up to 4 (12 layouts) | ❌ opens external terminal | ✅ nested | ✅ | ✅ | ✅ paid add-on | ◐ text in preview |
| [muCommander](https://www.mucommander.com/) | Dual | ✅ | ✅ | ? | ? | ✅ | ✅ text, hex |
| [Double Commander](https://doublecmd.sourceforge.io/) | Dual | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| [Finder](https://support.apple.com/en-us/109033) | Single | ❌ | ❌ | ❌ | ❌ | ◐ | ❌ |

## Power features

| App | Plugins / scripting | Root mode | Git | Processes | Finder tags | Dev pace |
|:--|:--|:--|:--|:--|:--|:--|
| [Ferry](https://ferry.indus3.org/) | ❌ | ? | ❌ | ❌ | ✅ | Very active (13 releases in Oct 2026) |
| [Commander One](https://commander-one.com/) | ❌ | ✅ | ❌ | ✅ | ✅ | Active |
| [Nimble Commander](https://magnumbytes.com/) | ◐ external tools | ✅ direct build | ❌ | ✅ | ✅ | Slow (about yearly) |
| [Marta](https://marta.sh/) | ✅ Lua API, JSON config | ? | ❌ | ❌ | ? | Stalled (no release since Jul 2024) |
| [Path Finder](https://www.cocoatech.io/) | ◐ AppleScript | ✅ | ◐ in v10, unconfirmed in v26 | ✅ | ✅ | Active (about monthly) |
| [ForkLift](https://binarynights.com/) | ◐ custom shell tools, CLI | ◐ helper | ✅ | ❌ | ✅ | Very active (every 2-4 weeks) |
| [QSpace Pro](https://qspace.awehunt.com/en-us/index.html) | ◐ AppleScript, custom menus | ◐ Pro, Touch ID | ❌ | ❌ | ✅ | Very active (several a month) |
| [muCommander](https://www.mucommander.com/) | ◐ YAML commands | ? | ❌ | ❌ | ❌ | Active |
| [Double Commander](https://doublecmd.sourceforge.io/) | ✅ Total Commander plugins, Lua | ◐ | ❌ | ❌ | ✅ | Very active (about monthly) |
| [Finder](https://support.apple.com/en-us/109033) | ◐ Shortcuts, AppleScript | ❌ | ❌ | ❌ | ✅ | Yearly, with macOS |

## The apps

### Ferry

**Website:** [https://ferry.indus3.org/](https://ferry.indus3.org/)  
**Developer:** Superverse Industries  
**Latest version:** 1.10 (Oct 2026)  
**Minimum macOS:** 14 Sonoma

A new native dual-panel file manager (about 8 MB) from Superverse Industries, first released in October 2026. Each panel has its own tabs, history and view (list, tree, icon or column), and seven layout presets switch the window between commander-style, Mac-style, developer and photo-sorting setups. It connects to SMB, SFTP, WebDAV, NFS, AFP and FTP servers, browses archives as folders, and includes batch rename with regex and undo, folder and file compare, a Markdown and code editor, image conversion, and duplicate and big-file finders. It needs no account and works offline.

**Pricing (USD)**

- 1 year: $9.99 (regular $14.99); keeps working after expiry with a renewal reminder
- Lifetime: $14.99 (regular $19.99)
- Supporter: $30 (lifetime licence plus a name in the credits)
- Early-adopter prices run until 31 Dec 2026; one licence covers all your Macs
- Trial: 7 days of use, after which it keeps working with a reminder

**Standout:** Layout presets, image/Markdown tools, duplicate and big-file finders.  
**Main weakness:** Brand new (1.0 in Oct 2026); no cloud APIs or plugins.

### Commander One

**Website:** [https://commander-one.com/](https://commander-one.com/)  
**Developer:** Electronic Team  
**Latest version:** 3.18 (25 Sep 2026)  
**Minimum macOS:** 10.13

A dual-pane file manager from Electronic Team (formerly Eltima), modelled on Total Commander. The free version covers dual panes, tabs, hotkeys, regex and content search, ZIP and root mode. The one-time PRO Pack adds FTP, FTPS, SFTP and WebDAV, a long list of cloud services (S3, Google Drive, Dropbox, OneDrive, Box, Backblaze B2, pCloud, Mega and others) with optional encryption, extra archive formats, a terminal, themes, and iOS and Android device mounting.

**Pricing (USD)**

- Free version available
- PRO Pack, one-time: $29.99 for 1 Mac, $99.99 for 5 Macs, quote for 50+
- Mac App Store PRO in-app purchase: $29.99 (the App Store build lacks device mounting)
- Trial: 15 days of PRO

**Standout:** Widest cloud list, with encryption.  
**Main weakness:** No folder compare or batch rename; confusing tiers.

### Nimble Commander

**Website:** [https://magnumbytes.com/](https://magnumbytes.com/)  
**Developer:** Michael Kazakov  
**Latest version:** 1.8.0 (Dec 2025)  
**Minimum macOS:** 11

A fast, keyboard-driven dual-pane file manager by Michael Kazakov, free and open source under GPL-3.0 since 2024. It has a VT100 terminal that stays in sync with the panel, FTP, SFTP and WebDAV, network share mounting, browsing of about 30 archive formats, batch rename, regex and content search, admin mode, and a view that lists running processes as files. The direct download has more features than the sandboxed App Store build.

**Pricing (USD)**

- Free (GPL-3.0); no in-app purchases

**Standout:** Fast native free commander; processes shown as files.  
**Main weakness:** No cloud; creates ZIP only; App Store build limited.

### Marta

**Website:** [https://marta.sh/](https://marta.sh/)  
**Developer:** Yan Zhulanow  
**Latest version:** 0.8.2 (Jul 2024)  
**Minimum macOS:** 11

A keyboard-first dual-pane file manager by Yan Zhulanow, built to be extended. Every setting lives in a shareable config file, and a Lua 5.4 plugin API and custom "Gadgets" let you add your own commands. It has a built-in terminal, a command palette, archive browsing and a disk usage analyser. It works with local files only and is still in beta.

**Pricing (USD)**

- Free during the beta
- A paid licence is planned for 1.0; the price has not been announced
- Patreon backers of $15 or more total get a perpetual licence

**Standout:** Lua plugin API and command palette.  
**Main weakness:** No network support; beta has stalled.

### Path Finder

**Website:** [https://www.cocoatech.io/](https://www.cocoatech.io/)  
**Developer:** Cocoatech  
**Latest version:** 26.1.10 (Oct 2026)  
**Minimum macOS:** 13

Cocoatech's long-running Finder replacement, now on version 26. It is built from modules you arrange in single or dual-pane windows: preview, terminal, processes, hex editor, ACL editor and the Drop Stack for collecting files from several places before acting on them. Version 26 added a two-folder compare and duplicate finder alongside the existing folder sync, batch rename and root access.

**Pricing (USD)**

- Subscription: $29.95 per year
- Fixed-term licences: 1 year $32.95, 2 years $55.95, 5 years $122.95
- Each activation covers 2 Macs
- Also included in Setapp
- Trial: 30 days

**Standout:** Most built-in modules: Drop Stack, ACL and hex editors.  
**Main weakness:** Subscription; stability complaints in 26.1.x.

### ForkLift

**Website:** [https://binarynights.com/](https://binarynights.com/)  
**Developer:** BinaryNights  
**Latest version:** 4.7.7 (20 Oct 2026)  
**Minimum macOS:** 14.6

BinaryNights' dual-pane file manager and file transfer client. It connects to FTP, SFTP, WebDAV, SMB, AFP and NFS servers and to Amazon S3, Backblaze B2, Google Drive, Dropbox, OneDrive and iCloud, with several connections open at once. It has a configurable transfer queue, one- or two-way folder sync with preview, multi-rename with regex and file metadata, editing of remote files in place, Git status and commits, and custom shell tools on the toolbar.

**Pricing (USD)**

- One-time licence with 1 year of updates: Single $19.95, Family $29.95, Small Business (5 Macs) $69.95
- With 2 years of updates: Family $49.95, Small Business $119.95
- You keep the last version released during your update period
- Also included in Setapp; not on the Mac App Store
- Free trial available

**Standout:** Transfer queue, sync and Git in one.  
**Main weakness:** Updates expire; no built-in terminal; two panes only.

### QSpace Pro

**Website:** [https://qspace.awehunt.com/en-us/index.html](https://qspace.awehunt.com/en-us/index.html)  
**Developer:** Tian Wenda  
**Latest version:** 7.0.4 (7 Oct 2026)  
**Minimum macOS:** 10.15

A multi-pane file manager by Tian Wenda that can show up to four panes in one window, with 12 layouts and saved workspaces. It connects to FTP, SFTP, WebDAV, SMB, AFP and NFS, and to S3-compatible storage, Google Drive, Dropbox, OneDrive, Box and Aliyun. It also offers folder compare and sync, hash comparison, a Quick Look preview pane with text editing, and folder sizes.

**Pricing (USD)**

- Pro (direct download): $13.99 on sale, regular $29.99, one-time
- Mac App Store edition: $12.99 on sale, regular $27.99 (sandboxed, fewer features)
- Paid add-ons: Server Connections $0.99 (regular $9.99), Advanced Batch Rename $0.99 (regular $4.99), Stash Shelf $0.99 (regular $4.99); Enhanced Archiver free (regular $4.99)
- Licences cover 2 devices
- Trial: 30 days for the direct download

**Standout:** Only one with 3-4 panes.  
**Main weakness:** Key features are paid add-ons; cluttered settings.

### muCommander

**Website:** [https://www.mucommander.com/](https://www.mucommander.com/)  
**Developer:** muCommander team  
**Latest version:** 1.6.2 (14 May 2026)  
**Minimum macOS:** 13 (older DMG for 10.15 and earlier)

A free, open-source (GPL-3.0) dual-pane file manager written in Java that runs on macOS, Windows and Linux. It reaches an unusually wide range of locations: FTP, SFTP, SMB, NFS, HTTP, Hadoop HDFS, vSphere and oVirt, plus Amazon S3, Google Drive, Dropbox, OneDrive and Google Cloud Storage. It browses many archive formats, includes a terminal and a text editor, and can reach Android devices over ADB. The Mac download bundles its own Java runtime.

**Pricing (USD)**

- Free (GPL-3.0); donations optional

**Standout:** Widest free protocol list (HDFS, vSphere, GCS).  
**Main weakness:** Java app; unsigned builds; 181 MB download.

### Double Commander

**Website:** [https://doublecmd.sourceforge.io/](https://doublecmd.sourceforge.io/)  
**Developer:** Alexander Koblov  
**Latest version:** 1.2.9 (27 Sep 2026)  
**Minimum macOS:** 11

A free, open-source (GPL-2.0+) dual-pane file manager inspired by Total Commander, with a native Cocoa build for Apple Silicon and Intel Macs. It has a terminal, viewer and editor, full-text and regex search, folder sync, multi-rename, Lua scripting and support for Total Commander-style plugins. Version 1.2 added macOS cloud drives (Dropbox, OneDrive, Box, S3, iCloud), Finder tags and APFS cloning.

**Pricing (USD)**

- Free (GPL-2.0 or later)

**Standout:** Total Commander clone with plugins and Lua.  
**Main weakness:** Windows-style UI; Homebrew cask disabled.

### Finder

**Website:** [https://support.apple.com/en-us/109033](https://support.apple.com/en-us/109033)  
**Developer:** Apple  
**Latest version:** macOS 27.0.1 (28 Sep 2026)  
**Minimum macOS:** 27 (Apple Silicon only)

The file manager built into macOS, included here as the baseline. It is single-pane with tabs, mounts SMB, NFS and WebDAV shares, reads FTP, and integrates with iCloud Drive and cloud apps that install File Provider extensions. macOS 27 Golden Gate rebuilt Spotlight indexing, refreshed the sidebar, added AI-suggested file names, and removed AFP support.

**Pricing (USD)**

- Free, bundled with macOS

**Standout:** Deepest OS integration; AI file-name suggestions.  
**Main weakness:** Single pane; no SFTP; AFP removed.

## Notes

- Checked 24 Oct 2026 against official sites, changelogs, App Store listings, Homebrew and Setapp.
- "?" means the feature is not documented or could not be verified. It does not mean the feature is missing.
- "Via macOS" means the app browses shares macOS has mounted rather than connecting itself.
- macOS 27 removed Apple's AFP client. Test AFP in any third-party app before relying on it.
- Prices are list prices in USD; sale and early-adopter prices can change.
