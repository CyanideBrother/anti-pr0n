# **How to permanently block porn (Windows & Android)**  
# VIDEO: [YOUTUBE](https://www.youtube.com/watch?v=PcfmGIh7lYU) | [VIMEO](https://vimeo.com/171017589) | [DAILYMOTION](http://www.dailymotion.com/video/x4gwtuj)
# **[WINDOWS]** *administrator required  
  
**I-** Download and install Acrylic DNS Proxy (because it's faster than system HOSTS) (https://sourceforge.net/projects/acrylic/files/Acrylic/0.9.32/Acrylic.exe/download)  
  
**II-** Edit Acrylic Configuration File  
  
- PrimaryServerAddress=208.67.222.123  
- SecondaryServerAddress=208.67.220.123  
  
**III-** Add new hosts to Acrylic Hosts File (https://raw.githubusercontent.com/CyanideBrother/anti-pr0n/master/hosts)  
  
**IV-** Change DNS to 127.0.0.1 on:  
- Ethernet  
- Wi-Fi (if available)  
- Ethernet 2 / TAP-Windows-Adapter (VPN) (if available)  
  
**V-** Install Adguard COMSS Version (6 months premium for free) (http://download.adguard.com/d/18694/adguardStandaloneInstaller.exe)  
- Enable Parental Control  
- Change Sensitivity level to "Teen (~13 years)"  
- Protect Adguard with random password and forget about it.  
  
**VI-** Set DuckDuckGo as default search engine in all your browsers. (less porn)  
  
**VII-** Restart Windows & Enjoy!  
  
# **[ANDROID]** *root required  

**I-** Download and install AdAway (https://f-droid.org/repo/org.adaway_57.apk) then  
- add new Hosts source (https://raw.githubusercontent.com/CyanideBrother/anti-pr0n/master/hosts)  
- change redirection IP to 0.0.0.0  
- click "Download Files and apply ad blocking"  
  
**II-** Reboot Android  
  
**III-** Download and install Override DNS (http://www7.zippyshare.com/v/B8jF0YCJ/file.html) then  
- set OpenDNS-FamilyShield and Apply  
- untick "DNS change notifications"  
- set random PIN and forget about it.  
  

# **How to block the nsfw subreddits?**  
# **# for Firefox based browsers**  
**I-** Go to https://raw.githubusercontent.com/CyanideBrother/anti-pr0n/master/NSFW/contentblock-regex.txt  
- Click File -> Save Page As... --> contentblock-regex.txt

**II-** Add to browser this addon --> https://addons.mozilla.org/en-US/firefox/addon/silentblock/  
- Move contentblock-regex.txt to FF profile folder. (Where is profile folder? In address bar enter "about:support" and click "Show Folder" button)  
- Restart browser.
 
  
# **# for Chromium based browsers** (if you use Opera browser 1st install [Download Chrome Extension](https://addons.opera.com/extensions/details/app_id/kipjbhgniklcnglfaldilecjomjaddfi))  
**I-** Go to https://raw.githubusercontent.com/CyanideBrother/anti-pr0n/master/NSFW/chromium_based.csv  
- Click File -> Save Page As... --> chromium_based.csv  
  
**II-** Add to browser this addon --> https://chrome.google.com/webstore/detail/block-site/eiimnmioipafcokbfikbljfdeojpcgbh  
- Go to 'Block site Preferences' and click 'Import list from CSV' --> select chromium_based.csv  --> then click 'Import'  
- Go to 'Other' Tab and Disable 'Allow sending anonymous statistics?'

  # **Enjoy!**
