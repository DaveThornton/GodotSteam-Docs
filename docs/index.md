# GodotSteam Documentation

{==
## Introduction
==}

GodotSteam is an open-source and fully functional Steamworks SDK / API module and plug-in for the [Godot Engine](https://godotengine.org){ target="\_blank" }. It comes for all versions of Godot from 2.x to 4.x as well as GDNative and GDExtension plug-ins.

On this site, you can find tutorials, lists of functions and signals, and even [games currently using GodotSteam](games/games.md).

{==
## Download It
==}

Most people just want to download something and go. Just make sure you **don't mix and match** the pre-compiled editors with the plug-ins or you'll have a really bad time.

### Module Pre-Compiles

They contain the pre-compiled editors, templates, and necessary Steam shared libraries:

=== ":simple-godotengine: Regular Builds"
	
	[ :fontawesome-brands-github: Godot 4.2.1 - Steamworks 1.58 - GodotSteam 4.5.1](https://github.com/CoaguCo-Industries/GodotSteam/releases/tag/v4.5.1){ .md-button .md-button--resource target="\_blank" }

	[ :fontawesome-brands-github: Godot 3.5.3 - Steamworks 1.58 - GodotSteam 3.22.3](https://github.com/CoaguCo-Industries/GodotSteam/releases/tag/v3.22.2){ .md-button .md-button--resource target="\_blank" }

	[ :fontawesome-brands-github: For All Versions](https://github.com/CoaguCo-Industries/GodotSteam/releases){ .md-button .md-button--resource target="\_blank" }

=== ":fontawesome-solid-people-group: Multiplayer Peer Builds"

	[ :fontawesome-brands-github: Godot 4.2.1 - Steamworks 1.58 - GodotSteam 4.5.1 MP](https://github.com/CoaguCo-Industries/GodotSteam/releases/tag/v4.5.1-mp){ .md-button .md-button--resource target="\_blank" }

	[ :fontawesome-brands-github: For All Versions](https://github.com/CoaguCo-Industries/GodotSteam/releases){ .md-button .md-button--resource target="\_blank" }	

=== ":octicons-server-24: Server Builds"

	[ :fontawesome-brands-github: Godot 4.1.2 - Steamworks 1.58 - GodotSteam Server 4.0.1](https://github.com/CoaguCo-Industries/GodotSteam-Server/releases/tag/v4.0.1){ .md-button .md-button--resource target="\_blank" }

	[ :fontawesome-brands-github: Godot 3.5.3 - Steamworks 1.58 - GodotSteam Server 3.0.1](https://github.com/CoaguCo-Industries/GodotSteam-Server/releases/tag/v3.0.1){ .md-button .md-button--resource target="\_blank" }

	[:fontawesome-brands-github: For All Server Versions](https://github.com/CoaguCo-Industries/GodotSteam-Server/releases){ .md-button .md-button--resource target="\_blank" }

### GDNative Plug-ins

=== ":octicons-plug-24: GDNative"

	[ :simple-godotengine: Godot Asset Library | Steamworks 1.58 - GodotSteam GDNative 3.22.2](https://godotengine.org/asset-library/asset/1045){ .md-button .md-button--resource target="\_blank" }

	[ :fontawesome-brands-github: GitHub | Steamworks 1.58 - GodotSteam GDNative 3.22.2](https://github.com/CoaguCo-Industries/GodotSteam/tarball/gdnative-plugin){ .md-button .md-button--resource target="\_blank" }

	[ :fontawesome-brands-github: For All Versions](https://github.com/CoaguCo-Industries/GodotSteam/releases){ .md-button .md-button--resource target="\_blank" }

=== ":octicons-plug-24: GDNative Server"

	[ :simple-godotengine: Godot Asset Library | Steamworks 1.58 - GodotSteam Server GDNative 3.0.1](https://godotengine.org/asset-library/asset/2222){ .md-button .md-button--resource target="\_blank" }

	[ :fontawesome-brands-github: GitHub | Steamworks 1.58 - GodotSteam Server GDNative 3.0.1](https://github.com/CoaguCo-Industries/GodotSteam-Server/releases/tag/v3.0.1-gdn){ .md-button .md-button--resource target="\_blank" }

	[ :fontawesome-brands-github: For All Versions](https://github.com/CoaguCo-Industries/GodotSteam-Server/releases){ .md-button .md-button--resource target="\_blank" }

### GDExtension Plug-ins

=== ":octicons-plug-24: GDExtension 4.0 - 4.1"

	[ :simple-godotengine: Godot Asset Library | Godot 4.1.3 - Steamworks 1.58 - GodotSteam GDExtension 4.5.2](https://godotengine.org/asset-library/asset/1972){ .md-button .md-button--resource target="\_blank" }

	[ :fontawesome-solid-file-zipper: GitHub | Godot 4.1.3 - Steamworks 1.58 - GodotSteam GDExtension 4.5.2](https://github.com/CoaguCo-Industries/GodotSteam/releases/tag/v4.5.2-gde){ .md-button .md-button--resource target="\_blank" }

	[ :fontawesome-brands-github: For All Versions](https://github.com/CoaguCo-Industries/GodotSteam/releases){ .md-button .md-button--resource target="\_blank" }

=== ":octicons-plug-24: GDExtension 4.2"

	[:simple-godotengine: Godot Asset Library | Godot 4.2.1 - Steamworks 1.58 - GodotSteam GDExtension 4.5.2](https://godotengine.org/asset-library/asset/2445){ .md-button .md-button--resource target="\_blank" }

	[:fontawesome-solid-file-zipper: GitHub | Godot 4.2.1 - Steamworks 1.58 - GodotSteam GDExtension 4.5.2](https://github.com/CoaguCo-Industries/GodotSteam/releases/tag/v4.5.2-gde){ .md-button .md-button--resource target="\_blank" }

	[ :fontawesome-brands-github: For All Versions](https://github.com/CoaguCo-Industries/GodotSteam/releases){ .md-button .md-button--resource target="\_blank" }

=== ":octicons-plug-24: GDExtension Server"

	[ :simple-godotengine: Godot Asset Library | Steamworks 1.58 - GodotSteam Server GDExtension 4.0.1](https://godotengine.org/asset-library/asset/2218){ .md-button .md-button--resource target="\_blank" }
	
	[ :fontawesome-brands-github: GitHub | Steamworks 1.58 - GodotSteam Server GDExtension 4.0.1](https://github.com/CoaguCo-Industries/GodotSteam-Server/tarball/gdextension-plugin){ .md-button .md-button--resource target="\_blank" }

	[ :fontawesome-brands-github: All Server Versions](https://github.com/CoaguCo-Industries/GodotSteam-Server/releases
		){ .md-button .md-button--resource target="\_blank" }

{==
## Compile It Yourself
==}

Roll up your sleeves and build your own versions of GodotSteam. More instructions are availale on each branch's readme page or over to your left under ***Compiling How-To's***.

### Godot 4.x Branches

=== ":fontawesome-solid-gamepad: Godot Engine 4.x"

	Fully working module to compile into any Godot Engine 4.x versions

	[:fontawesome-solid-code-branch: See the Source](https://github.com/CoaguCo-Industries/GodotSteam/tree/godot4){ .md-button .md-button--resource target="\_blank" }

	[:fontawesome-solid-file-zipper: Get the TAR](https://github.com/CoaguCo-Industries/GodotSteam/tarball/godot4){ .md-button .md-button--resource target="\_blank" }

	[:fontawesome-solid-file-zipper: Get the ZIP](https://github.com/CoaguCo-Industries/GodotSteam/zipball/godot4){ .md-button .md-button--resource target="\_blank" }

=== ":fontawesome-solid-gamepad: GDExtension"

	The successor of GDNative, fresh for any Godot Engine 4.x versions

	[:fontawesome-solid-code-branch: See the Source](https://github.com/CoaguCo-Industries/GodotSteam/tree/gdextension){ .md-button .md-button--resource target="\_blank" }

	[:fontawesome-solid-file-zipper: Get the TAR](https://github.com/CoaguCo-Industries/GodotSteam/tarball/gdextension){ .md-button .md-button--resource target="\_blank" }

	[:fontawesome-solid-file-zipper: Get the ZIP](https://github.com/CoaguCo-Industries/GodotSteam/zipball/gdextension){ .md-button .md-button--resource target="\_blank" }

=== ":fontawesome-solid-gamepad: Multiplayer Peer"

	Use Godot's cool multiplayer nodes with Steamworks

	[:fontawesome-solid-code-branch: See the Source](https://github.com/CoaguCo-Industries/GodotSteam/tree/multiplayer-peer){ .md-button .md-button--resource target="\_blank" }

	[:fontawesome-solid-file-zipper: Get the TAR](https://github.com/CoaguCo-Industries/GodotSteam/tarball/multiplayer-peer){ .md-button .md-button--resource target="\_blank" }

	[:fontawesome-solid-file-zipper: Get the ZIP](https://github.com/CoaguCo-Industries/GodotSteam/zipball/multiplayer-peer){ .md-button .md-button--resource target="\_blank" }

### Godot 3.x Branches

=== ":fontawesome-solid-gamepad: Godot Engine 3.x"

	Fully working module to compile into any Godot Engine 3.x versions

	[:fontawesome-solid-code-branch: See the Source](https://github.com/CoaguCo-Industries/GodotSteam/tree/godot3){ .md-button .md-button--resource target="\_blank" }

	[:fontawesome-solid-file-zipper: Get the TAR](https://github.com/CoaguCo-Industries/GodotSteam/tarball/godot3){ .md-button .md-button--resource target="\_blank" }

	[:fontawesome-solid-file-zipper: Get the ZIP](https://github.com/CoaguCo-Industries/GodotSteam/zipball/godot3){ .md-button .md-button--resource target="\_blank" }

=== ":fontawesome-solid-gamepad: GDNative"

	Want to alter the code for the GDNative plug-in or roll your own?

	[:fontawesome-solid-code-branch: See the Source](https://github.com/CoaguCo-Industries/GodotSteam/tree/gdnative){ .md-button .md-button--resource target="\_blank" }

	[:fontawesome-solid-file-zipper: Get the TAR](https://github.com/CoaguCo-Industries/GodotSteam/tarball/gdnative){ .md-button .md-button--resource target="\_blank" }

	[:fontawesome-solid-file-zipper: Get the ZIP](https://github.com/CoaguCo-Industries/GodotSteam/zipball/gdnative){ .md-button .md-button--resource target="\_blank" }

### Godot 2.x Branches

=== ":fontawesome-solid-gamepad: Godot Engine 2.x" 

	Fully working module to compile into any Godot Engine 2.x versions

	[:fontawesome-solid-code-branch: See the Source](https://github.com/CoaguCo-Industries/GodotSteam/tree/godot2){ .md-button .md-button--resource target="\_blank" }

	[:fontawesome-solid-file-zipper: Get the TAR](https://github.com/CoaguCo-Industries/GodotSteam/tarball/godot2){ .md-button .md-button--resource target="\_blank" }

	[:fontawesome-solid-file-zipper: Get the ZIP](https://github.com/CoaguCo-Industries/GodotSteam/zipball/godot2){ .md-button .md-button--resource target="\_blank" }

### Server Branches

=== ":fontawesome-solid-gamepad: Godot 4.x Server"

	A Steamworks-enabled dedicated server with any Godot Engine 4.x versions

	[:fontawesome-solid-code-branch: See the Source](https://github.com/CoaguCo-Industries/GodotSteam-Server/tree/godot4){ .md-button .md-button--resource target="\_blank" }

	[:fontawesome-solid-file-zipper: Get the TAR](https://github.com/CoaguCo-Industries/GodotSteam-Server/tarball/godot4){ .md-button .md-button--resource target="\_blank" }

	[:fontawesome-solid-file-zipper: Get the ZIP](https://github.com/CoaguCo-Industries/GodotSteam-Server/zipball/godot4){ .md-button .md-button--resource target="\_blank" }

=== ":fontawesome-solid-gamepad: Godot 3.x Server"

	A Steamworks-enabled dedicated server with any Godot Engine 3.x versions

	[:fontawesome-solid-code-branch: See the Source](https://github.com/CoaguCo-Industries/GodotSteam-Server/tree/godot3){ .md-button .md-button--resource target="\_blank" }

	[:fontawesome-solid-file-zipper: Get the TAR](https://github.com/CoaguCo-Industries/GodotSteam-Server/tarball/godot3){ .md-button .md-button--resource target="\_blank" }

	[:fontawesome-solid-file-zipper: Get the ZIP](https://github.com/CoaguCo-Industries/GodotSteam-Server/zipball/godot3){ .md-button .md-button--resource target="\_blank" }

=== ":fontawesome-solid-gamepad: GDExtension Server"

	A Steamworks-enabled dedicated server with any Godot Engine 4.x versions

	[:fontawesome-solid-code-branch: See the Source](https://github.com/CoaguCo-Industries/GodotSteam-Server/tree/gdextension){ .md-button .md-button--resource target="\_blank" }

	[:fontawesome-solid-file-zipper: Get the TAR](https://github.com/CoaguCo-Industries/GodotSteam-Server/tarball/gdextension){ .md-button .md-button--resource target="\_blank" }

	[:fontawesome-solid-file-zipper: Get the ZIP](https://github.com/CoaguCo-Industries/GodotSteam-Server/zipball/gdextension){ .md-button .md-button--resource target="\_blank" }

=== ":fontawesome-solid-gamepad: GDNative Server"

	A Steamworks-enabled dedicated server with any Godot Engine 3.x versions

	[:fontawesome-solid-code-branch: See the Source](https://github.com/CoaguCo-Industries/GodotSteam-Server/tree/gdnative){ .md-button .md-button--resource target="\_blank" }

	[:fontawesome-solid-file-zipper: Get the TAR](https://github.com/CoaguCo-Industries/GodotSteam-Server/tarball/gdnative){ .md-button .md-button--resource target="\_blank" }

	[:fontawesome-solid-file-zipper: Get the ZIP](https://github.com/CoaguCo-Industries/GodotSteam-Server/zipball/gdnative){ .md-button .md-button--resource target="\_blank" }

### Requirements

If you are compiling the module, GDNative, or GDExtension version yourself, there are a few things you'll need to start working regardless of which flavor you decide to try out.

<div class="link-grid" markdown>

[:simple-steam: Steamworks SDK](https://partner.steamgames.com/){ .md-button .md-button--primary target="\_blank" }
[:simple-godotengine: Godot Engine Source](https://github.com/godotengine/godot){ .md-button .md-button--primary target="\_blank" }

</div>

While we suggest the latest and greatest version of Valve's Steamworks SDK 1.58 or newer, the older versions work well too.  Just make sure there are no compatibility breaks between the SDK and GodotSteam; usually noted in the readme's.

{==
## Quick Start
==}

If you are downloading our pre-compiles or using the GDNative plugin, or have finished fresh compiling, you can move on to the how-to sections or just start experimenting.

### :fontawesome-solid-book: How-To Guides

Based on what you want to work with, use one of these how-to guides to continue on.

[:fontawesome-solid-book: Module How-To](howto/modules.md){ .md-button .md-button--resource }

[:fontawesome-solid-book: Multiplayer Peer How-To](howto/multiplayer_peer.md){ .md-button .md-button--resource }

[:fontawesome-solid-book: GDNative How-To](howto/gdnative.md){ .md-button .md-button--resource }

[:fontawesome-solid-book: GDExtension How-To](howto/gdextension.md){ .md-button .md-button--resource }

[:fontawesome-solid-book: Server How-To](howto/server.md){ .md-button .md-button--resource }

### :material-folder-open: GodotSteam Example Project

A working example of some GodotSteam features based on current tutorials.

=== "Godot 3.x"
		
	[:fontawesome-solid-code-branch: Example 3.x Project Source](https://github.com/CoaguCo-Industries/GodotSteam-Example-Project/tree/godot3){ .md-button .md-button--resource target="\_blank" }

	[:simple-godotengine: Godot Asset Library](https://godotengine.org/asset-library/asset/1956){ .md-button .md-button--resource target="\_blank" }

	[:fontawesome-solid-file-zipper: GitHub Drop-in ZIP](https://github.com/CoaguCo-Industries/GodotSteam-Example-Project/zipball/godot3){ .md-button .md-button--resource target="\_blank" }

=== "Godot 4.x"
	
	[:fontawesome-solid-code-branch: Example 4.x Project Source](https://github.com/CoaguCo-Industries/GodotSteam-Example-Project/tree/godot4){ .md-button .md-button--resource target="\_blank" }
	
	[:simple-godotengine: Godot Asset Library](https://godotengine.org/asset-library/asset/1959){ .md-button .md-button--resource target="\_blank" }
	
	[:fontawesome-solid-file-zipper: GitHub Drop-in ZIP](https://github.com/CoaguCo-Industries/GodotSteam-Example-Project/zipball/godot4){ .md-button .md-button--resource target="\_blank" }

Last, but absolutely not least, make sure you are logged into your Steam client if testing your game or any scenes. Otherwise you will experience some pretty brutal crashing.

Have fun!

{==
## Have A Game Using GodotSteam?
==}

Finally got your Steam store page up? Whether you are about to release your game, already did, or are just tinkering away at it, you can send me the details and I will post it in [the Games Using GodotSteam section](games/games.md).

You can use the button below to submit your game to the list or submit a pull-request to our Docs repository. Please remember to include your game's Steam store page URL. Additionally you can include up to four additional links like your Mastodon or Twitter account, Discord invite link, development website, devlog, or anything relevant to your game or studio.

<div class="link-grid" markdown>

[:fontawesome-solid-gamepad: E-Mail Your Game](mailto:games@godotsteam.com){ .md-button .md-button--primary target="\_blank" }
[:fontawesome-brands-github: PR Submit Your Game](https://github.com/CoaguCo-Industries/GodotSteam-Docs/pulls){ .md-button .md-button--primary target="\_blank" }

</div>

{==
## Need Support?
==}

Need some help? Get support for the project through the [GodotSteam GitHub issues page](https://github.com/CoaguCo-Industries/GodotSteam/issues){ target="\_blank" }, by e-mail, or discussion in our Discord server.

<div class="link-grid" markdown>

[:fontawesome-brands-github: Create An Issue](https://github.com/CoaguCo-Industries/GodotSteam/issues){ .md-button .md-button--primary target="\_blank" }
[:fontawesome-solid-paper-plane: Send A Support E-Mail](mailto:support@godotsteam.com){ .md-button .md-button--primary target="\_blank" }
[:fontawesome-brands-discord: Chat With Us On Discord](https://discord.gg/SJRSq6K){ .md-button .md-button--primary target="\_blank" }

</div>

{==
## Donating And Contributing
==}

Want to help out? The best way is to contribute fixes or additions through pull-requests on GitHub. We also accept donations through these places:

<div class="link-grid" markdown>

[:fontawesome-brands-github: GitHub Sponsors](https://github.com/sponsors/Gramps){ .md-button .md-button--primary target="\_blank" }
[:simple-kofi: Ko-Fi](https://ko-fi.com/grampsgarcia){ .md-button .md-button--primary target="\_blank" }
[:fontawesome-brands-paypal: Paypal](https://www.paypal.me/sithlordkyle){ .md-button .md-button--primary target="\_blank" }

</div>
