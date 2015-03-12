![http://mupen64plus.googlecode.com/svn/wiki/Mupen64Plus-splash.jpg](http://mupen64plus.googlecode.com/svn/wiki/Mupen64Plus-splash.jpg)

**Mupen64Plus** is a cross-platform plugin-based N64 emulator which is capable of accurately playing many games.  Included are four `MIPS R4300` CPU emulators, with dynamic recompilers for 32-bit x86 and 64-bit amd64 systems, and necessary plugins for audio, graphical rendering (RDP), signal co-processor (RSP), and input.  There is 1 included OpenGL video plugin, called RiceVideo.  There are 3 other excellent video plugins being maintained by [wahrhaft](http://bitbucket.org/wahrhaft/), called Arachnoid, Glide64, and Z64.

[![](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=R8CQB9JZH9WMN)

### Features ###
  * Dynamic recompilers for 32-bit (x86) and 64-bit (amd64) machines
  * Two OpenGL video plugins, with [Hi-resolution texture](HighResolutionTextures.md) support
  * [LIRC](LIRC.md) Infrared remote control support
  * [Rumble Pak](RumbleSupport.md) support (Linux only)
  * Cheat system with gameshark code support
  * Speed adjustment with smooth sound output
  * Shared library interface for integration into other systems (front-ends)
  * Command-line Front-end application

# News #

**February 3, 2015**: I apologize for such a long period with no new releases.  There have actually been many many changes since the last release.  Development effort has picked up significantly in the past half year or so, and we now have quite a few very smart and dedicated programmers who are improving Mupen64Plus in different areas. I promise there will be a new release this year.<br>
<b>December 28, 2013</b>: We have migrated our source code repository from Mercurial (bitbucket.org) to Git (github.org)!  Check out the updated source code links in the "For Developers" section below.<br>
<b>July 4th, 2013</b>: After nearly 4 years of hard work, the 2.0 release is here!  Check out the release message in this <a href='http://www.emutalk.net/threads/54632-Mupen64Plus-v2-0-is-here!'>emutalk thread</a> for more information.<br>
<br>
<h1>Releases</h1>
<b>Mupen64Plus v2.0</b> is now available for all supported operating systems.  You can download it from the "Featured Download" section on the left.<br>
<br>
For detailed information about the differences between each release, check out the <a href='ReleasePage.md'>Release Notes Page</a>

<h1>Documentation</h1>

<h2>For Users</h2>
<a href='KeyboardSetup.md'>Keyboard</a> - Default keyboard setup & configuration<br>
<a href='ControllerSetup.md'>Joysticks</a> - How to set up your joystick if it is not auto-detected<br>
<a href='UIConsoleUsage.md'>UI-Console</a> - Mupen64Plus command-line UI usage<br>
<a href='FileLocations.md'>File Locations</a> - Places where Mupen64Plus installs and/or searches for various files<br>
<a href='RumbleSupport.md'>Rumble</a> - Instructions for setting up force-feedback (Linux only)<br>
<a href='HighResolutionTextures.md'>Hi-res textures</a> - Instructions for using hi-resolution texture packs with Rice Video<br>
<a href='ThirdPartyPlugins.md'>Third Party Front-ends and Plugins</a> - List of additional Front-ends (user interfaces) and plugins, compatible with Mupen64Plus 2.0 but not part of the bundle distributed here<br>
<a href='GameCompatibility.md'>Games</a> - Compatibility and game notes<br>
<a href='Screenshots.md'>Screenshots</a><br>

<h2>For Developers</h2>
<a href='https://github.com/mupen64plus/mupen64plus-core/wiki/Mupen64Plus-v2.0-Core-API-v1.0'>Mupen64Plus 2.0 API</a> - Full documentation of the new API between plugins, the emulator core, and the front-end application<br>
<a href='https://github.com/mupen64plus'>Mupen64Plus source code</a> - Link to Git repository containing the Mupen64plus modules - the emulator core, 10 plugins, command-line user interface program, Win32 build dependencies and test ROM source code.<br>

You can download, build, and test the latest source code from our Git repository.  For Linux users, instructions can be found at the <a href='CompilingFromGit.md'>CompilingFromGit</a> wiki page.  For Windows users, instructions can be found at the <a href='CompilingOnWindows.md'>CompilingOnWindows</a> wiki page.  For Apple OSX users, instructions are at the <a href='MacOSXInstructions.md'>MacOSXInstructions</a> page.<br>
<br>
<h1>Questions  / Problems / Bugs</h1>
If you have questions, you may post them in the <a href='http://groups.google.com/group/mupen64plus'>Mupen64Plus Google Group</a>.  To report a problem or a bug, you may post a message on the google group, or use the Issue Tracker above to file a bug report.<br>
<br>
We also have an IRC channel where many of the developers and fans hang out.  If you would like to stop by with a question or to say hi, it's #mupen64plus at irc.freenode.net<br>
<br>
<h1>Developers, Developers, Developers!</h1>

For those who are not Mupen64Plus project members but would like to submit a patch, please post it in the <a href='http://groups.google.com/group/mupen64plus'>Mupen64Plus Google Group</a>.  For those who would like to join the project, please send an email to the project owner, which is given at the top of this page, on the right.<br>
