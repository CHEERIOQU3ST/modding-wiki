# AutPI

<fieldset>
<legend>AutPI:</legend>

<table><tbody>

<tr><td>Creator(s):</td><td>Autumn, ilikebreadtoomuch</td></tr>
<tr><td>Year:</td><td>2024</td></tr>
<tr><td>Platform:</td><td>Windows (Mac/Linux with Wine)</td></tr>
<tr><td>Status:</td><td>
<p style="color:#00B000;">Active Development</p>
</td></tr>
<tr><td>Website:</td><td><a href="https://autpi.github.io/">autpi.github.io</a></td></tr>
<tr><td>Info:</td><td><a href="https://autumn-mnya.github.io/dllmods/index.html">Autumn's dll mods page</a></td></tr>
</tbody></table>
</fieldset>



AutPI is an enhanced [freeware](freeware) [dll mod](modloader) version of the original [ModCS](modcs) lua API made by user **Autumn**. 
AutPI is meant to be a simplier and easier to use framework for code-heavy Cave Story modding than editing [CSE2](cse2) or [Doukutsu-rs](drs). It allows NPCs, Map Bosses, Weapons, UI, Custom TSC, and many other componets of the game to be altered through the easy to understand [Lua script language](https://en.wikipedia.org/wiki/Lua_(programming_language)).

One of AutPI's signature features is the addition of code injection during specific parts of runtime (Such as Game.Act() and Game.Draw()). As well as game mode recreations. This allows many features of the engine to be modified to the user's content such as custom UI, controls, character animations, etc. without extensive or obtrusive modifications to be made to the game's vanillia code.

The API's documentation [can be found here.](https://autpi.github.io/)

AutPI also has special compatability with [Autumn's Various Additions](ava) that adds functions pretaining to it's unique features like mimiga mask offsets, collectibles, money, etc. A list of all of the functions is included in the [AVA Documentation](https://github.com/autumn-mnya/autumns-various-additions/releases/download/1.2.2/Documentation.zip). This requires the [AVA dll mod](ava) to be installed.




[^1]: There is also a custom [CSE2](cse2) fork called CSE2LE which includes AutPI, AVA, layers, and some other built in mods with a focus on allowing support for Nintendo Switch and PlayStation Vita homebrew ports. It is currently private and is planned to be released at a later date.