# nwL's CS:GO Scripts

## Installation

### Manual (for inexperienced users)

1. Download this repository by choosing "Code" -> "Download ZIP" above the file listing.
2. Extract the ZIP file and copy the folder
   into `<Steam folder>/steamapps/common/Counter-Strike Global Offensive/csgo/cfg`.
3. Rename the folder to `nwL`.
4. Open (or create) `autoexec.cfg` in the `cfg` folder and add `exec nwL/main` as a separate line.

### Git (for experienced users)

1. Open a command line and go to `<Steam folder>/steamapps/common/Counter-Strike Global Offensive/csgo/cfg`.
2. Run `git clone https://github.com/nwLSteam/csgo-scripts nwL`. Make sure you don't forget the `nwL` argument after the URL.
3. Open (or create) `autoexec.cfg` in the `cfg` folder and add `exec nwL/main` as a separate line.

## Running

The scripts will get loaded automatically on game load. **Since the scripts are based on VScript, they will not work
until a map is loaded!**

The currently available scripts are:

<table>
<thead><tr><th>Command</th><th>Description</th><th>Usage</th></tr></thead>
<tbody>
<tr>
<td valign="top"><p><code><b>nwL_wingman_unlock</b></code></p></td>
<td valign="top">
    <p>Unlocks the amount of players on Wingman modes.</p>
    <p>This means, in practice, that each map that has a different layout based on the gamemode (for example 
    <code>de_inferno</code>) can now be played in the Wingman layout with more than 2 players per team.</p>
    <ul>
    <li><i>Note: Many Wingman maps have a hard limit on spawns and players will get stuck with more players per team.
        For example, it is not possible to play with more than 4 players per team on <code>de_overpass</code> without
        a complete recompile of the map.</i>
    <li><i>Note: To play Nuke this way, you do not need this script. Simply run <code>de_shortnuke</code>.</i>
    <li><i>Note: This does not work on <code>de_vertigo</code>. Vertigo includes custom VScript that cannot be
        emulated.</i>
    </ul>
</td>
<td valign="top">
    <p><code>nwL_wingman_unlock</code> while in a map with a separate Wingman layout. These maps include:</p>
    <ul>
        <li><code>de_inferno</code></li>
        <li><code>de_overpass</code></li>
        <li><code>de_train</code></li>
    </ul>
   and Workshop maps with Wingman logic.
</td>
</tr>
</tbody>
</table>
