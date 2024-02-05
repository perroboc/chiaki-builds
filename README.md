# Archive

This repo has been archived, as other people are doing a far better (and consistant) job than me. Please use [chiaki4deck](https://github.com/streetpea/chiaki4deck) as a great up to date alternative. I know I will :)

# (Unofficial) Chiaki builds

[![Build Release](https://github.com/alvaromunoz/chiaki-builds/actions/workflows/Build-win_x64.yml/badge.svg)](https://github.com/alvaromunoz/chiaki-builds/actions/workflows/Build-win_x64.yml)

This is just a repo with [Chiaki](https://git.sr.ht/~thestr4ng3r/chiaki) as a
Git submodule, automating the build scripts on GitHub Actions Workflows.

So far only Windows x64 builds have been automated, using both MSYS2 and Visual Studio.

If you want to download the official releases, please check out the original repo:
[https://git.sr.ht/~thestr4ng3r/chiaki](https://git.sr.ht/~thestr4ng3r/chiaki)

## Why?

[Because](https://git.sr.ht/~thestr4ng3r/chiaki/tree/master/doc/platform-build.md):

> Windows support is reduced to the absolute minimum for maintainability.

SDL2 has not been updated from 2.0.10 (2.0.14 introduced support for Dualsense
controllers in Windows), and the binary release has a problem with blinking
frames. It seems that building using updated libraries and software fixes
these issues, so I wanted to automate this to be as open as possible.

### What's updated by new libraries?

- Support for PlayStation Dualsense and XBox Series S|X controllers
- Hardware video acceleration for decoding

### What's not updated?

- Choppy audio (YMMV)

### What's missing (but from the official release, too)?

- Motion controls
- Rumble / force feedback
- Adaptative triggers

# About Chiaki

Chiaki created by Florian Märkl

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License version 3
as published by the Free Software Foundation.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License
along with this program. If not, see <https://www.gnu.org/licenses/>.

Additional permission under GNU AGPL version 3 section 7

If you modify this program, or any covered work, by linking or
combining it with the OpenSSL project's OpenSSL library (or a
modified version of that library), containing parts covered by the
terms of the OpenSSL or SSLeay licenses, the Free Software Foundation
grants you additional permission to convey the resulting work.
Corresponding Source for a non-source form of such a combination
shall include the source code for the parts of OpenSSL used as well
as that of the covered work.
