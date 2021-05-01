Smarphone Model : Xiomie Mi 9T (k20)

1. ## Lien utils
- [Adb-mini](https://forum.xda-developers.com/t/tool-minimal-adb-and-fastboot-2-9-18.2317790/)
- [Rom officiel](https://xiaomifirmwareupdater.com/miui/davinci/)
- [Xiomie.eu](https://xiaomi.eu/community/threads/miui-12-0-12-1-12-2-12-5-stable-release.56191/)
- [Twrp](https://twrp.me/xiaomi/xiaomimi9t.html)
- [Twrp-patch](https://drive.google.com/file/d/1JQRB-JcYJBVIEgcL-QzMXHlV1doZA2ft/view?usp=sharing)
- [Magisk](https://topjohnwu.github.io/Magisk/install.html)

 
2. ## Instalation complete 
- Flash la rom officiel
- Boot sur la Rom officielle (Suivre toutes les instructions au démarrage)
- Flash le recovery, le patch & reboot*
- Boot sur le recovery, wipe, reboot & flash la ROM Custom
- Pendant le boot de la ROM, (Histoire d'optimiser du temps) récupère dans le .zip le fichier "recovery Image"

2.1 Commande pour patch le recovery :
fastboot --disable-verity --disable-verification flash vbmeta vbmeta.img

Application utiliser:

- [AdAway](https://adaway.org/)
- [Agenda](https://play.google.com/store/apps/details?id=com.google.android.calendar&hl=fr&gl=US)
- [AntiCovid](https://play.google.com/store/apps/details?id=fr.gouv.android.stopcovid)
- [Banque]
- [BusyBox](https://play.google.com/store/apps/details?id=stericson.busybox)
- [Calculatrice](https://play.google.com/store/apps/details?id=com.simplemobiletools.calculator&hl=fr&gl=US)
- [Dashlane](https://play.google.com/store/apps/details?id=com.dashlane)
- [Discord](https://play.google.com/store/apps/details?id=com.discord)
- [Docs](https://play.google.com/store/apps/details?id=com.google.android.apps.docs.editors.docs)
- [Drive](https://play.google.com/store/apps/details?id=com.google.android.apps.docs)
- [F-Droid](https://f-droid.org/)
- [Firefox](https://play.google.com/store/apps/details?id=org.mozilla.firefox&hl=fr&gl=US)
- [Freebox](https://play.google.com/store/apps/details?id=fr.freebox.android.compagnon)
- [GadgetBridge](https://f-droid.org/en/packages/nodomain.freeyourgadget.gadgetbridge/)
- [Gmail](https://play.google.com/store/apps/details?id=com.google.android.gm)
- [Keep](https://play.google.com/store/apps/details?id=com.google.android.keep)
- [Lens](https://play.google.com/store/apps/details?id=com.microsoft.office.officelens&hl=fr&gl=US)
- [Magisk](https://www.xda-developers.com/how-to-install-magisk/)
- [Map](https://play.google.com/store/apps/details?id=com.google.android.apps.maps)
- [Material Files](https://f-droid.org/fr/packages/me.zhanghai.android.files)
- [MeteoCiel](https://play.google.com/store/apps/details?id=com.meteociel.fr)
- [Moovizy](https://play.google.com/store/apps/details?id=fr.cityway.android_v2.stas&hl=fr&gl=US)
- [Nasa](https://play.google.com/store/apps/details?id=gov.nasa&hl=fr&gl=US)
- [NetFlix](https://help.netflix.com/fr/node/57688)
- [NovaLauncher](https://play.google.com/store/apps/details?id=com.teslacoilsw.launcher)
- [PDF VIEWER](https://f-droid.org/fr/packages/com.gsnathan.pdfviewer/)
- [PhotoGoogle](https://play.google.com/store/apps/details?id=com.google.android.apps.photos)
- [ProtonMail](https://play.google.com/store/apps/details?id=ch.protonmail.android)
- [Reddit](https://play.google.com/store/apps/details?id=com.reddit.frontpage&hl=fr&gl=US)
- [Snap](https://play.google.com/store/apps/details?id=com.snapchat.android)
- [Spotify]
- [SwiftKey](https://play.google.com/store/apps/details?id=com.touchtype.swiftkey&hl=fr&gl=US)
- [Telegram](https://play.google.com/store/apps/details?id=org.telegram.messenger&hl=fr&gl=US)
- [Terminal](https://play.google.com/store/apps/details?id=com.termux&hl=fr&gl=US)
- [Twitch](https://play.google.com/store/apps/details?id=tv.twitch.android.app)
- [Twitter](https://play.google.com/store/apps/details?id=com.twitter.android)
- [Whatapp](https://play.google.com/store/apps/details?id=com.whatsapp&hl=fr&gl=US)
- [YoutubeVanced](https://vancedapp.com)

2.3. ## liste des modules
- Hide root
- xmlpak

5. ## Commande Adb pour désinstaller des applications android :
- adb shell
- pm list packages -f (non de l'appe a desinstallé)
- pm uninstall --user 0 (non de l'app)

5.1. Commande pour supprimer tous les bloatwares :
(GoogleApp)
- pm uninstall -k --user 0 com.google.android.apps.cloudprint
- pm uninstall -k --user 0 com.google.android.apps.docs.editors.docs
- pm uninstall -k --user 0 com.google.android.apps.photos
- pm uninstall -k --user 0 com.google.android.googlequicksearchbox
- pm uninstall -k --user 0 com.google.android.inputmethod.latin
- pm uninstall -k --user 0 com.google.android.music
- pm uninstall -k --user 0 com.google.android.projection.gearhead
- pm uninstall -k --user 0 com.google.android.videos
- pm uninstall -k --user 0 com.google.android.youtube
- pm uninstall -k --user 0 com.google.ar.lens
- pm uninstall -k --user 0 com.android.chrome
- pm uninstall -k --user 0 com.android.quicksearchbox

#(XiomieApp)
- pm uninstall -k --user 0 cn.wps.xiaomi.abroad.lite
- pm uninstall -k --user 0 com.android.browser
- pm uninstall -k --user 0 com.android.calendar
- pm uninstall -k --user 0 com.android.chrome
- pm uninstall -k --user 0 com.android.email
- pm uninstall -k --user 0 com.android.fileexplorer
- pm uninstall -k --user 0 com.android.mms
- pm uninstall -k --user 0 com.mi.health
- pm uninstall -k --user 0 com.miui.calculator
- pm uninstall -k --user 0 com.miui.compass
- pm uninstall -k --user 0 com.miui.fm
- pm uninstall -k --user 0 com.miui.huanji
- pm uninstall -k --user 0 com.miui.miservice
- pm uninstall -k --user 0 com.miui.miwallpaper.earth
- pm uninstall -k --user 0 com.miui.miwallpaper.mars
- pm uninstall -k --user 0 com.miui.notes
- pm uninstall -k --user 0 com.miui.weather2
- pm uninstall -k --user 0 com.xiaomi.midrop
- pm uninstall -k --user 0 com.xiaomi.payment
- pm uninstall -k --user 0 com.miui.newmidrive
- pm uninstall -k --user 0 com.miui.cloudbackup
- pm uninstall -k --user 0 cn.wps.moffice_eng.xiaomi.lite
-  
- 
