![17309853170228635658176172692341](https://github.com/user-attachments/assets/29444b1f-2342-40ba-b06e-e548dcc53643)

##

`Mobox` is a project designed to run windows x86 applications in [Termux](https://github.com/termux/termux-app) using [Box64](https://github.com/ptitSeb/box64) and [Wine](https://www.winehq.org/).

# Installation 

1. Install
[Termux](https://f-droid.org/repo/com.termux_118.apk),
[Termux-X11](https://raw.githubusercontent.com/olegos2/mobox/main/components/termux-x11.apk),
[Input Bridge](https://raw.githubusercontent.com/olegos2/mobox/main/components/inputbridge.apk)and[Xinput Bridge](https://github.com/Ilan12346-maya/XinputBridge/releases/download/1.35/XinputBridge_1.35.apk)

2. Download mobox_patched_1.0.tar.gz

3. Back up your termux data or it will be replaced .

Open termux terminal and execute this command. 
```bash
termux-setup-storage
```
```bash
tar -zxf /sdcard/Download/mobox_patched_1.0.tar.gz -C /data/data/com.termux/files --recursive-unlink --preserve-permissions
```
4. Type `mobox` in termux.

Done.

*Enable permission access to files and documents in termux app info if you encountered permission error*

*If you encountered some error messages when you first started mobox just ignore it*

Credits to olegos2

## Third party applications

[Mobox](https://github.com/olegos2/mobox)

[Xinput Bridge](https://github.com/Ilan12346-maya/XinputBridge)

[airidosas252 wine builds](https://github.com/airidosas252/Wine-Builds)

[K11MCH1 DRIVERS](https://github.com/K11MCH1/WinlatorTurnipDrivers)

[glibc-packages](https://github.com/termux-pacman/glibc-packages)

[Box64](https://github.com/ptitSeb/box64)

[Box86](https://github.com/ptitSeb/box86)

[DXVK](https://github.com/doitsujin/dxvk)

[DXVK-ASYNC](https://github.com/Sporif/dxvk-async)

[DXVK-GPLASYNC](https://gitlab.com/Ph42oN/dxvk-gplasync)

[VKD3D](https://github.com/lutris/vkd3d)

[D8VK](https://github.com/AlpyneDreams/d8vk)

[Termux-app](https://github.com/termux/termux-app)

[Termux-x11](https://github.com/termux/termux-x11)

[Wine](https://wiki.winehq.org/Licensing)

[wine-ge-custom](https://github.com/GloriousEggroll/wine-ge-custom)

[Mesa](https://docs.mesa3d.org/license.html)

[mesa-zink-11.06.22](https://github.com/alexvorxx/mesa-zink-11.06.22)

[Mesa-VirGL](https://github.com/alexvorxx/Mesa-VirGL)


