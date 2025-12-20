# Minimlesser - iPod Mini 2G theme

<table align="center">
    <tr>
        <td align="center">
            <img src="screenshots/wps.png" alt="WPS" width="274"><br>
            <em>WPS</em>
        </td>
        <td align="center">
            <img src="screenshots/mainmenu.png" alt="Main Menu" width="274"><br>
            <em>Main Menu</em>
        </td>
        <td align="center">
            <img src="screenshots/wps_noart.png" alt="WPS with cover placeholder" width="274"><br>
            <em>WPS with cover placeholder</em>
        </td>
    </tr>
    <tr>
        <td align="center">
            <img src="screenshots/lockscreen_art.png" alt="Lock Screen with music playing" width="274"><br>
            <em>Lock Screen with music playing</em>
        </td>
        <td align="center">
            <img src="screenshots/lockscreen.png" alt="Lock Screen" width="274"><br>
            <em>Lock Screen</em>
        </td>
        <td align="center">
            <img src="screenshots/lockscreen_noart.png" alt="Lock Screen with cover placeholder" width="274"><br>
            <em>Lock Screen with cover placeholder</em>
        </td>
    </tr>
    <tr>
        <td colspan="3" align="center">
            <img src="screenshots/usbmode.png" alt="USB Mode" width="274"><br>
            <em>USB Mode</em>
        </td>
    </tr>
</table>

This is an iPod Mini theme based on the fantastic [Minimless](https://github.com/Olsro/rockbox-mini2g-themes) theme by OlsroFR.
I made small changes on the WPS and SBS to fit my personal taste:
- Added album art placeholder instead of the realtime volume viewer. It also shows on the lock screen
- Replaced the info about the next song with the album title of the currently playing song
- Removed the audio format from appearing while changing the volume
- In the bottom-right corner it is now displayed only the clock and the playlist status as alternating text
- Now the album art is cut even less by the rest of the interface. It is displayed 14px smaller than the original Minimless
- Sleep timer is no longer shown

## How to install

1. Install "Fonts file" from the latest Rockbox [daily build](https://www.rockbox.org/daily.shtml)
2. Copy the contents of `rockbox` folder into your player `/.rockbox` folder, replacing older files/folders if needed
3. Head to the theme settings of your player and select the `minimlesser.cfg` theme.
