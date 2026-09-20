SNIPER GOLD UNIVERSAL ANDROID ICON SET

Use:
- res/icon/mipmap-*/ic_launcher.png = legacy launcher icons
- res/icon/mipmap-anydpi-v26/ic_launcher.xml = Android adaptive icon
- res/drawable/icon_foreground.png = adaptive foreground
- res/drawable/icon_background.png = adaptive background

For Cordova, point config.xml to:
<icon src="res/icon/ic_launcher_512.png" />

For Android 8+ adaptive icon, use the generated mipmap-anydpi-v26/ic_launcher.xml
in the Android resource merge/build setup.

Do not put API keys or secrets in these image files.
