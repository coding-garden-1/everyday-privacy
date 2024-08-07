### [everyday-privacy](#)

**How to have privacy these days :)**

### [Why privacy?](#)

Privacy is important because advertisers' sole job is to learn how to manipulate your behavior. They want you to spend more on stuff you don't need, and will do anything to get you spending. When you use apps that sell your data, you provide advertisers with the information they need to make advertisement algorithms that specifically work on you. It's creepy and wrong!!

It only takes installing an app to stop them, so why not reclaim your privacy, freedom, & general right to not be treated as a product?

## [Everyday Internet Usage:](#)

  **Android**
  
- **[F-Droid:](https://f-droid.org/en/)**
  - An open-source, privacy-loving Play Store.
  - Use this exclusively so your app installation data isn't tracked and sold by Google.

- **[Clipious:](https://f-droid.org/en/packages/com.github.lamarios.clipious/)**
  - YouTube client that doesn't track you.
  - Removes ads, clickbait titles & thumbnails, sponsors, filler sections
  - <details> <summary>Instructions</summary>Once you're in the app, go to settings > add server > click + on any of the servers listed. Then search for videos and start watching. </details>

- **[VLC](https://f-droid.org/en/packages/org.videolan.vlc/)** or **[NOVA Player](https://f-droid.org/en/packages/org.courville.nova/)**
  - Really good MP3/MP4 players.

- **[ProtonVPN:](https://f-droid.org/en/packages/ch.protonvpn.android/)**
  - Hide your internet traffic from your creepy, data-selling ISP.

- **[Privacy Browser](https://f-droid.org/en/packages/com.stoutner.privacybrowser.standard/)**

- **[Proton Mail](https://account.proton.me/mail)**
    - Swiss privacy law protected emails
- **[Proton Drive](https://proton.me/drive)**
    - Swiss privacy law protected file storage

 - **[OsMand](https://f-droid.org/en/packages/net.osmand.plus/)**
    - Private, offline Google Maps
 
- **Degoogle Script:**
  - Removes most Google bloatware from your devices.
    <details> 
      <summary>Reasons to remove Google bloatware </summary>
      
      
      Google is known for being really privacy-invasive.
      
      Google wastes most of your device's storage.
      
      Almost all Google apps can be easily replaced with F-Droid alternatives.
      
      Bonus: this makes old phones run much faster!
      
    </details>
   <details>
   
   <summary>Degoogling Instructions</summary>
     
      
  1. <a href="https://www.xda-developers.com/install-adb-windows-macos-linux/">Install ADB on your laptop</a>
  2. <a href="https://developer.android.com/studio/debug/dev-options">Enable USB Debugging</a>
  3. Plug your phone into your laptop and hit "allow usb debugging"
  4. Make sure you have F-Droid, AnySoftKeyboard, Clipious, and Privacy Browser installed before you do this
  5. Paste this into a terminal
  
    
      ```
      adb uninstall --user 0 com.google.android.apps.accessibility.auditor
      adb uninstall --user 0 com.google.android.apps.accessibility.maui.actionblocks
      adb uninstall --user 0 com.google.android.marvin.talkback
      adb uninstall --user 0 com.google.android.projection.gearhead
      adb uninstall --user 0 com.google.android.apps.work.clouddpc
      adb uninstall --user 0 com.google.android.tvrecommendations
      adb uninstall --user 0 com.google.android.tvlauncher
      adb uninstall --user 0 com.google.android.leanbacklauncher
      adb uninstall --user 0 com.google.android.tv.remote.service
      adb uninstall --user 0 com.google.android.wearable.assistant
      adb uninstall --user 0 com.google.android.backdrop
      adb uninstall --user 0 com.google.android.apps.blogger
      adb uninstall --user 0 com.google.android.calculator
      adb uninstall --user 0 com.google.samples.apps.cardboarddemo
      adb uninstall --user 0 com.chrome.beta
      adb uninstall --user 0 com.chrome.canary
      adb uninstall --user 0 com.chrome.dev
      adb uninstall --user 0 com.google.chromeremotedesktop
      adb uninstall --user 0 com.google.android.apps.mediashell
      adb uninstall --user 0 com.androidx.compose.material.catalog
      adb uninstall --user 0 com.google.android.apps.audition
      adb uninstall --user 0 com.google.android.apps.village.boond
      adb uninstall --user 0 com.google.android.apps.restore
      adb uninstall --user 0 com.google.android.apps.pixelmigrate
      adb uninstall --user 0 com.google.android.apps.wellbeing
      adb uninstall --user 0 com.google.android.apps.camera.poseidon
      adb uninstall --user 0 com.google.android.apps.kids.familylinkhelper
      adb uninstall --user 0 com.google.location.nearby.apps.fastpair.validator
      adb uninstall --user 0 com.google.android.apps.nbu.files
      adb uninstall --user 0 com.google.android.apps.photosgo
      adb uninstall --user 0 com.google.android.apps.automotive.gamesnacks
      adb uninstall --user 0 com.google.android.inputmethod.latin
      adb uninstall --user 0 com.google.android.gm
      adb uninstall --user 0 com.google.android.gm.lite
      adb uninstall --user 0 com.google.android.googlequicksearchbox
      adb uninstall --user 0 com.google.android.apps.enterprise.cpanel
      adb uninstall --user 0 com.google.android.apps.aiy
      adb uninstall --user 0 com.google.android.apps.giant
      adb uninstall --user 0 com.google.android.katniss
      adb uninstall --user 0 com.google.android.apps.cultural
      adb uninstall --user 0 com.google.android.apps.googleassistant
      adb uninstall --user 0 com.google.android.apps.assistant
      adb uninstall --user 0 com.google.android.apps.authenticator2
      adb uninstall --user 0 com.google.android.apps.automotive.templates.host
      adb uninstall --user 0 com.google.android.apps.automotive.inputmethod
      adb uninstall --user 0 com.google.android.calendar
      adb uninstall --user 0 com.google.android.apps.dynamite
      adb uninstall --user 0 com.android.chrome
      adb uninstall --user 0 com.google.android.apps.classroom
      adb uninstall --user 0 com.google.android.apps.cloudconsole
      adb uninstall --user 0 com.google.enterprise.topaz.mobile.android
      adb uninstall --user 0 com.google.android.apps.docs.editors.docs
      adb uninstall --user 0 com.google.android.apps.docs
      adb uninstall --user 0 com.google.earth
      adb uninstall --user 0 com.google.android.apps.kids.familylink
      adb uninstall --user 0 com.google.android.apps.tycho
      adb uninstall --user 0 com.google.android.apps.adm
      adb uninstall --user 0 com.google.android.apps.fitness
      adb uninstall --user 0 com.google.android.apps.searchlite
      adb uninstall --user 0 com.google.android.apps.health.research.studies
      adb uninstall --user 0 com.google.android.apps.chromecast.app
      adb uninstall --user 0 com.google.samples.apps.iosched
      adb uninstall --user 0 com.google.android.keep
      adb uninstall --user 0 com.google.ar.lens
      adb uninstall --user 0 com.google.android.apps.ads.homeservices
      adb uninstall --user 0 com.google.android.apps.maps
      adb uninstall --user 0 com.google.android.apps.mapslite
      adb uninstall --user 0 com.google.android.apps.tachyon
      adb uninstall --user 0 com.google.android.apps.meetings
      adb uninstall --user 0 com.google.android.apps.messaging
      adb uninstall --user 0 com.google.android.apps.magazines
      adb uninstall --user 0 com.google.android.apps.subscriptions.red
      adb uninstall --user 0 com.google.android.apps.paidtasks
      adb uninstall --user 0 com.google.android.apps.nbu.paisa.user
      adb uninstall --user 0 com.google.android.apps.photos
      adb uninstall --user 0 com.google.android.apps.wearables.maestro.companion
      adb uninstall --user 0 com.google.android.apps.wear.companion
      adb uninstall --user 0 com.google.android.wearable.watchface.rwf
      adb uninstall --user 0 com.google.android.wearable.fitbit.mcu.data
      adb uninstall --user 0 com.google.android.apps.books
      adb uninstall --user 0 com.google.android.play.games
      adb uninstall --user 0 com.google.ar.core
      adb uninstall --user 0 com.google.android.apps.podcasts
      adb uninstall --user 0 com.google.android.apps.docs.editors.sheets
      adb uninstall --user 0 com.google.android.apps.docs.editors.slides
      adb uninstall --user 0 com.google.android.apps.helprtc
      adb uninstall --user 0 com.google.android.apps.tasks
      adb uninstall --user 0 com.google.android.apps.translate
      adb uninstall --user 0 com.google.android.videos
      adb uninstall --user 0 com.google.android.apps.googlevoice
      adb uninstall --user 0 com.google.android.apps.walletnfcrel
      adb uninstall --user 0 com.google.android.apps.healthdata
      adb uninstall --user 0 com.google.android.wearable.healthservices
      adb uninstall --user 0 com.google.android.apps.jam
      adb uninstall --user 0 com.google.android.tv
      adb uninstall --user 0 com.google.android.apps.cloud.cloudbi
      adb uninstall --user 0 com.google.android.apps.accessibility.reveal
      adb uninstall --user 0 com.google.android.apps.accessibility.magnifier
      adb uninstall --user 0 com.google.android.apps.motionsense.bridge
      adb uninstall --user 0 com.google.android.apps.navlite
      adb uninstall --user 0 com.google.android.apps.onlineinsightspanel
      adb uninstall --user 0 com.google.android.apps.safetyhub
      adb uninstall --user 0 com.google.android.apps.photos.scanner
      adb uninstall --user 0 com.google.android.apps.pixel.health
      adb uninstall --user 0 com.google.android.wearable.pixel.pdms
      adb uninstall --user 0 com.google.android.apps.baselinestudy
      adb uninstall --user 0 com.google.research.projectrelate
      adb uninstall --user 0 com.google.android.wearable.protolayout.renderer
      adb uninstall --user 0 com.google.android.apps.seekh
      adb uninstall --user 0 com.google.android.accessibility.reader
      adb uninstall --user 0 com.google.android.apps.recorder
      adb uninstall --user 0 com.google.android.apps.userpanel
      adb uninstall --user 0 com.google.android.apps.security.securityhub
      adb uninstall --user 0 com.niksoftware.snapseed
      adb uninstall --user 0 com.google.socratic
      adb uninstall --user 0 com.google.android.accessibility.soundamplifier
      adb uninstall --user 0 com.google.android.tts
      adb uninstall --user 0 com.google.android.accessibility.switchaccess
      adb uninstall --user 0 com.google.toontastic
      adb uninstall --user 0 com.google.android.tv
      adb uninstall --user 0 com.google.android.youtube
      adb uninstall --user 0 com.google.android.apps.youtube.producer
      adb uninstall --user 0 com.google.android.youtube.tv
      adb uninstall --user 0 com.google.android.apps.youtube.kids
      adb uninstall --user 0 com.google.android.youtube.tvkids
      adb uninstall --user 0 com.google.android.apps.youtube.music
      adb uninstall --user 0 com.google.android.youtube.tvmusic
      adb uninstall --user 0 com.google.android.apps.youtube.music.pwa
      adb uninstall --user 0 com.google.android.apps.youtube.creator
      adb uninstall --user 0 com.google.android.apps.youtube.unplugged
      adb uninstall --user 0 com.google.android.youtube.tvunplugged
      ```
     
  </details>

  **Computer**
  
  - [**Debian**](https://www.wikihow.com/Install-Debian)
    - Open source Linux. So much faster than Windows. 

  - [**VSCodium**](https://vscodium.com/#install)
     - Code editor that doesn't track your data
   
  - [**UBlock Origin**](https://ublockorigin.com/)
      - No ads or trackers!

  -  [**LibreWolf**](https://librewolf.net/)
       - Open source Firefox

 ## [Advanced](#)

- For people who care even more about privacy
  
  - [**Random User Agent Switcher**](https://random-user-agent.com/)
    - Pretend to swap devices each time you visit a website
  
  - [ICE Single Site Browsers](https://mxrepo.com/mx/testrepo/pool/test/i/ice/)
    - Privacy through website isolation
    - <details>
      <summary>Installation instructions</summary>
      Download the .deb and paste the following command into a terminal: sudo dpkg -i filename.deb
    </details>
  
  - NoFingerprint
  - CanvasJS Blocker
  
      
  
