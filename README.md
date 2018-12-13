# MobileCraft

The well-known game [Minecraft](https://minecraft.net/) inspired to create a MobileCraft game for an open source sandbox for mobile devices that run the Android system.

MobileCraft is based on [Minetest](https://github.com/minetest/minetest/) project.

The engine and the game is licensed under [LGPL-3.0](doc/LGPL-3.0.md) (or higher) and you should be familiar with [Other_License.txt](doc/Other_License.txt). Resources games licensed under CC-BY-SA 3.0, unless otherwise stated.

Copyright (C) 2016-2018 Sergcomp

This program is free; You may redistribute and / or modify it under the terms of the GNU General Public License published by the Free Software Foundation; either version 3 of this license, or (at your choice) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; even without an implied warranty of MERCHANTABILITY or FITNESS FOR CERTAIN NEEDS. See the GNU General Public License for details.

You should have received a copy of the GNU General Public License along with this program; if not, see <https://www.gnu.org/licenses>.

Additional permission under section 7 of the GNU GPL version 3

If you change this program or any work covered by the license, composing or combining it with armeabiv7a (or a modified version of this library) containing the parts covered by GNU LGPL, then the licensors of this program provide you additional permission to transfer the resulting work. {The corresponding source code for the non-source form of such a combination will include the source code of the used parts of the armeabiv7a along with the source text of the work covered by the license.}


#Project build

To build the project and get the apk file, this version of the integrated development environment (IDE) for Windows-10-64 was used:
Android Studio 3.2.1
Build #AI-181.5540.7.32.5056338, built on October 9,2018
JRE: 1.8.0_152-release-1136-b06 amd64
JVM: OpenJDK 64-Bit Server VM by JetBrains s.r.o

SDK Platform: from Android 5.0(Lollipop) API Level 21 Rev 2 to Android 9.0(Pie) API Level 28 Rev 6

#Warning!:
If when builds an project there will be a problem with the NDK,
you must install Android NDK r16b instead of the available Android NDK r18b!
For this, the contents of the folder <c:\Users\<user-name>\AppData\Local\Android\Sdk\ndk-bundle\> should be removed. Instead, paste the contents of the folder <...\android-ndk-r16b\> pre-downloaded NDK.

Before you build the project, pack the <Files> folder into the zip archive of the same name in the directory:<...MobileCraft\app\src\main\assets\>.

If when creating an APK release there is a problem with signature keys, try removing debug key: <c:\Users\<user-name>\.android\debug.keystore.
