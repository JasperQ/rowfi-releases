# RowFi for Windows and macOS

RowFi turns your Concept2 RowErg into a row on real water: connect your PM5 over Bluetooth, and a sculler on the course rows at your pace, stroke for stroke. More at [rowfi.app](https://www.rowfi.app).

These are test builds. On Android, RowFi is on the Google Play Store.

## Download

| | |
|---|---|
| **Windows** 10 or 11, 64-bit | [RowFi-windows.zip](https://github.com/JasperQ/rowfi-releases/releases/latest/download/RowFi-windows.zip) |
| **macOS** 13 or later on Apple Silicon, 11 or later on Intel | [RowFi-macos.zip](https://github.com/JasperQ/rowfi-releases/releases/latest/download/RowFi-macos.zip) |

Older versions and what changed are under [Releases](https://github.com/JasperQ/rowfi-releases/releases).

You need a computer with Bluetooth (4.0 or later) to connect the PM5. Without one, you can still try RowFi with **Row with the simulator** on the Connect screen: Space starts and stops the rowing, and the arrow keys set the pace and the stroke rate.

## Install on Windows

1. Unzip the download. Keep `RowFi.exe` and `libgdble.windows.x86_64.dll` together in the `RowFi` folder: the DLL is the Bluetooth connection.
2. Double-click `RowFi.exe`.
3. These builds aren't code-signed yet, so Windows may show **"Windows protected your PC"**. Click **More info**, then **Run anyway**. Your browser may also warn that the file isn't commonly downloaded; choose **Keep**.

## Install on macOS

1. Unzip the download and drag **RowFi** into **Applications**.
2. These builds aren't notarised by Apple yet, so macOS blocks the first launch. Open RowFi once, close the warning, then go to **System Settings → Privacy & Security**, scroll down, and click **Open Anyway** next to RowFi.
3. If macOS says RowFi **"is damaged and can't be opened"**, it isn't: that's how macOS treats an unnotarised download. Open **Terminal** and run:

   ```
   xattr -cr /Applications/RowFi.app
   ```

   Then open RowFi again.
4. When RowFi asks to use Bluetooth, click **Allow**: it needs Bluetooth to find your PM5.

## Connect your PM5

Wake your PM5 (press any button) and set it to connect. RowFi finds it on the Connect screen. Take a stroke to leave the landing stage.

## Graphics

RowFi picks High quality on a computer. If it stutters, for example on a laptop without a separate graphics card, choose **Quality: Medium** or **Quality: Low** in Settings.

## Feedback

Found a bug, or something that doesn't feel right on the water? Mail [hello@rowfi.app](mailto:hello@rowfi.app) with your computer, your operating system and what happened.
