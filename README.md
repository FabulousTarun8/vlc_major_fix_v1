# VLC Media Player

**VLC** is a free, libre, and open-source **media player** and **multimedia engine** focused on **playing everything** and **running everywhere**.

**VLC** can play most multimedia files, discs, streams, and devices. It can also convert, encode, stream, and manipulate multimedia streams into numerous formats.

VLC is used by millions of people around the world on numerous platforms for a wide variety of purposes.

The **VLC engine** can be embedded into third-party applications and is called *libVLC*.

VLC is part of the [VideoLAN project](https://videolan.org) and is developed and supported by a community of volunteers.

The VideoLAN project began at École Centrale Paris, now known as CentraleSupélec. The university relicensed VLC under the GPLv2 license in February 2001. Since then, VLC has been downloaded **billions of times**.

## License

**VLC** is released under the GPLv2 license *(or any later version)*.

*On some platforms, VLC is effectively licensed under GPLv3 because of the licenses of its dependencies.*

**libVLC**, the underlying engine, is released under the LGPLv2 license *(or any later version)*. This allows the engine to be embedded into third-party applications while permitting those applications to be licensed under other licenses.

# Platforms

VLC is available on the following platforms:

- [Windows](https://www.videolan.org/vlc/download-windows.html) — Windows 7 and later, including UWP platforms and all versions of Windows 10.
- [macOS](https://www.videolan.org/vlc/download-macosx.html) — macOS 10.10 and later.
- [GNU/Linux](https://www.videolan.org/vlc/#download) and related distributions.
- [BSD](https://www.videolan.org/vlc/download-freebsd.html) and related systems.
- [Android](https://www.videolan.org/vlc/download-android.html) — Android 4.2 and later, including Android TV and Android Auto.
- [iOS](https://www.videolan.org/vlc/download-ios.html) — iOS 9 and later, including Apple TV and iPadOS.
- Haiku, OS/2, and several other platforms.

Not all platforms receive the same level of support because of our limited resources.

**Note:** The [Android app](https://code.videolan.org/videolan/vlc-android/) and the [iOS app](https://code.videolan.org/videolan/vlc-ios/) are maintained in repositories separate from the main VLC repository.

# Contributing and Community

**VLC** is maintained by a community of contributors. VideoLAN does not pay its community members. The community includes developers, helpers, maintainers, designers, and writers who want to help this open-source project thrive.

The main VLC codebase is written in C, but this repository also contains substantial amounts of C++, Objective-C, assembly, and Rust.

Other repositories associated with VLC use languages such as Kotlin and Java for [Android](https://code.videolan.org/videolan/vlc-android/), Swift for [iOS](https://code.videolan.org/videolan/vlc-ios/), and C# for [libVLCSharp](https://code.videolan.org/videolan/libvlcsharp/).

We welcome contributions in the following areas:

- Coding and software development.
- Packaging for Windows, macOS, and Linux distributions.
- Technical writing and documentation.
- Design.
- Support.
- Community management and communication.

Please consider contributing!

You can find us on IRC in the **#videolan** channel on *[Libera.Chat](https://libera.chat)*.

## Contributions

Contributions are made through merge requests on our [GitLab repository](https://code.videolan.org/videolan/vlc/).

Continuous integration checks and discussions must be resolved before a merge request can be merged.

# libVLC

**libVLC** is an embeddable multimedia engine for third-party applications and frameworks.

It runs on the same platforms as VLC, and sometimes on additional platforms. It provides playback, streaming, and conversion capabilities for multimedia files and streams.

**libVLC** offers bindings for several programming languages, including C++, Python, and C#.

# Support

## Useful Links

The following links may be helpful:

- [VLC Website](https://www.videolan.org/vlc/)
- [Support](https://www.videolan.org/support/)
- [Forums](https://forum.videolan.org/)
- [Wiki](https://wiki.videolan.org/)
- [Developer's Corner](https://wiki.videolan.org/Developers_Corner)
- [Bug Tracker](https://code.videolan.org/videolan/vlc/-/issues)
- [VideoLAN Website](https://www.videolan.org/)

## Source Code Sitemap

```text
ABOUT-NLS          - Notes on the Free Translation Project.
AUTHORS            - VLC authors.
COPYING            - The GPL license.
COPYING.LIB        - The LGPL license.
INSTALL            - Installation and build instructions.
NEWS               - Important updates and release information.
README             - Project overview.
THANKS             - VLC contributors.

bin/               - VLC binaries.
bindings/          - libVLC bindings for other programming languages.
compat/            - Compatibility library for operating systems
                     that lack essential functionalities.
contrib/           - Facilities for retrieving external libraries and
                     building them for systems that do not have
                     the required versions.
doc/               - Miscellaneous documentation.
extras/analyser    - Code analysis and editor-specific files.
extras/buildsystem - Additional build-system files.
extras/misc        - Miscellaneous files that do not fit into
                     the other extras/ categories.
extras/package     - VLC packaging files, such as specification files.
extras/tools/      - Tools for retrieving external build tools required
                     by the project.
include/           - Header files.
lib/               - libVLC source code.
modules/           - VLC plugins and modules. Most of the code is here.
po/                - VLC translations.
share/             - Shared resource files.
src/               - libvlccore source code.
test/              - Testing infrastructure.
```
