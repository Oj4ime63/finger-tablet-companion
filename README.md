# Finger Tablet companion for Windows

Finger Tablet turns your Android phone into a pen display for your Windows PC: you see your drawing program on the phone and draw on it with your finger or a stylus. It has two parts, both free:

- the **Finger Tablet** app on your phone, from Google Play
- this **companion** on your PC

This page is for testers of the Google Play test (version 2.1.4).

## What you need

- A Windows 10 (version 1809 or newer) or Windows 11 PC, 64-bit
- An Android phone with Android 11 or newer
- A USB cable that carries data. Some cables only charge.

## 1. Get the phone app

1. Open the test invitation on your phone: https://play.google.com/apps/testing/com.fingertablet
   Use the Google account you gave for the test, then tap **Become a tester**.
2. Install **Finger Tablet** from the Play Store: https://play.google.com/store/apps/details?id=com.fingertablet

Do you have an older Finger Tablet that didn't come from Google Play? Uninstall it first, or Play can't install this one. Uninstalling deletes its settings.

## 2. Get the companion

1. Under **Releases** on this page, open the newest one and download `FingerTablet-Companion-2.1.4-win-x64.zip`.
2. Unzip it anywhere, for example into your Documents folder.
3. Open the `FingerTablet-Companion` folder and run `FingerTablet.Companion.exe`. Nothing to install.

The first time, Windows may say **"Windows protected your PC"**. That's because the program isn't signed by a known publisher. Click **More info**, then **Run anyway**. Your browser may also warn that the zip "isn't commonly downloaded": choose **Keep**.

On its first start, the companion lists the drawing programs it found (Blender, Krita, GIMP, Clip Studio Paint, PhotoCraft) and asks before linking them. Linking adds a small script or a few keyboard shortcuts to each, so the phone's brush sliders can work. **Linked programs…** in its window shows every change and undoes it.

## 3. Connect

1. Plug the phone into the PC with the USB cable.
2. **Turn on USB tethering on the phone:** Settings › Network & internet › Hotspot & tethering › **USB tethering** (on Samsung: Settings › Connections › Mobile Hotspot and Tethering › **USB tethering**). Finger Tablet's own settings, under CONNECTION, open this screen for you. No Developer options needed.
3. Open Finger Tablet on the phone. The first time, it asks **"Allow ‹your PC› to connect?"**: tap **Allow**. It connects within a few seconds.

While USB tethering is on, Windows may use the phone's mobile data for the internet. To keep that in check, set the phone's connection as metered: Windows Settings › Network & Internet › the phone's connection (Ethernet) › **Metered connection**.

**Or use USB debugging, the fallback:** Settings › Developer options › USB debugging (no Developer options? Settings › About phone, on Samsung About phone › Software information, and tap **Build number** 7 times). When the phone asks **"Allow USB debugging?"**, tick **Always allow from this computer** and tap **Allow**.

USB tethering is the main way: whenever it is on, the companion connects over it, even if USB debugging is on too (no need to turn USB debugging off). USB debugging is only used when USB tethering is off or can't be used. With both on, the phone may still ask "Allow USB debugging?": allowing it is fine and keeps the fallback ready.

Stuck? **How do I connect?** in the companion's window walks through it, including the USB driver some phones need for USB debugging.

## Updating and removing

- **To update:** right-click the Finger Tablet icon in the system tray and choose **Quit**, then unzip the new version over the old folder.
- **To remove:** in the companion's window, open **Linked programs…**, tick **Unlink all also removes Finger Tablet's own files**, and press **Unlink all**. Then delete the folder.

## Feedback

Please use **Send feedback…**, in the phone app's settings or at the bottom of the companion's window. With "Include phone and app details" on, the form shows exactly what it sends.

## Privacy

See the [privacy policy](PRIVACY.md). In short: nothing you draw leaves your PC and phone, and only feedback you choose to send reaches us.

## Checking the download (optional)

`SHA256SUMS.txt` holds the zip's checksum. In PowerShell: `Get-FileHash FingerTablet-Companion-2.1.4-win-x64.zip` should print the same value, in capitals.

---

Finger Tablet is not affiliated with Adobe, CELSYS, the Blender Foundation, KDE, the GIMP team or PhotoCraft's makers.
