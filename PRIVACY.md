# Finger Tablet: privacy policy

*Last updated: 21 November 2026*

Finger Tablet is two free programs made by Ojaime: the **Finger Tablet** app for Android phones, and the **Finger Tablet companion** for Windows PCs. Together they let you draw on your PC with your phone. This policy explains what information they handle and where it goes.

## In short

Finger Tablet has no accounts, no ads and no analytics, and it doesn't track you. What you draw goes from your phone to your own PC and nowhere else. The only thing that reaches us is feedback you choose to send.

## Between your phone and your PC

While they're connected, the phone app sends the companion on your PC what it needs to draw for you: where your finger or stylus touches and how hard, the shortcut buttons, brush slider and gesture settings you use, and the size of the picture it can show. The companion sends back pictures of your PC screen and of your drawing program's panels, plus details such as the program's name and its brush settings.

- This goes over the USB cable, through Android's USB debugging. Only a PC you have allowed on the phone ("Allow USB debugging?") can connect.
- If you have set up Android's wireless debugging yourself, it may go over your own Wi-Fi network instead. Finger Tablet never sets that up.
- None of it is sent to us or to anyone else. Apart from the settings described below, none of it is stored. The phone shows the pictures from your PC and doesn't save them.

## On your phone

The app keeps its own settings in its private storage: button sets, where panels and sliders sit, gesture and pressure settings, and an unsent feedback message. If you use Android's backup, Android may include these settings in your backup to your Google account.

## On your PC

The companion keeps its settings and a log of what it did in `%LOCALAPPDATA%\FingerTablet` on your PC. The log can include your phone's model name and the names of your drawing programs. To make the phone's brush sliders, panels and zoom work, the companion:

- reads the screen
- reads the names and values of controls in the drawing program you use, through Windows' accessibility features
- may change some settings and add small link scripts in drawing programs on your PC (Blender, Krita, GIMP, Clip Studio Paint, PhotoCraft)

It lists these changes and can undo them (Linked programs… › Unlink all). None of this leaves your PC.

## Feedback you send

Both apps have a Send feedback form. Nothing is sent until you press Send. Then your message goes over an encrypted connection (HTTPS) to FormSubmit (formsubmit.co), a service that forwards it to us by email.

- **It sends:** the type of message and what you wrote.
- **With "Include phone and app details" on** (the form shows you exactly what will be sent):
  - from the phone: the app's and companion's versions, the phone's maker and model, the Android version, whether the phone is connected to the PC and how fast it answers, the drawing program's name, the screen's refresh rate, and whether the layout is left- or right-handed
  - from the PC: the companion's and phone app's versions, the Windows version, your displays' sizes and scaling, whether the phone is connected, the drawing area in use, and which drawing programs are linked
- Like any website, FormSubmit receives your device's IP address with the message. FormSubmit's own privacy policy covers its part.
- We use feedback only to answer it and to improve Finger Tablet. We keep the emails as long as they're useful for that, and we never sell or share them. To have your feedback deleted, contact us (below).

## Downloads

The phone app comes from Google Play, and the companion from GitHub. Their own privacy policies cover those downloads.

## Children

Finger Tablet is not directed at children under 13.

## Changes

If what the apps send changes, we'll update this page and its date.

## Contact

fingertabletdev@outlook.com
