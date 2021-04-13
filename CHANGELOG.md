Unpublished
- Added tor mirror into HTML header for discoverability

v0.9.0
- Various layout, spelling, and grammar fixes
- Added new discussion channel on matrix ```#online-anonymity:matrix.org```
- Fixed connectivity methods table recommendations (VPN over Tor over VPN)
- Removed the shark meme because it was a bit much
- Added reference to the recent Spotify AI voice recognition patent <https://patents.justia.com/patent/10891948>
- Added more information and illustration about Tor Bridges and especially Meek bridges for users in hostile environments
- Added some more information about hash collisions
- Moved Requirements section up before Introduction
- Fixed DNS privacy illustration DoHoT that was spelled wrong
- Fixed Appendixes names that were out of order
- Added guidance to create a Proxy VPS in addition to a VPN VPS in the case of the VPN over Tor route
- Added more guidance to getting and using Tor bridges in censored/blocked/unsafe environments
- Added more guidance to the "No Tor/VPN" option in a hostile environment

v0.8.9a
- Moved the donations section to the bottom of the guide

v0.8.9
- Added reference to <https://www.freehaven.net/anonbib/date.html> in the bonus resources section
- Many small fixes in the README
- Various small layout and grammar fixes
- Removed some parts about unblockable telemetry on MacOS Big Sur since this issue is no longer relevant it seems (and the telemetry can be blocked)
- Erratum: removed a quote from a user on his request

v0.8.8
- Fixed QR codes pointing to old addresses (but still valid)
- Added Keyoxide proofs to the README
- Various small fixes
- Huge thanks to the generous donator of 1 XMR
- Added proper native Tor mirror on <http://thgtoa7imksbg7rit4grgijl2ef6kc7b56bp56pmtta4g354lydlzkqd.onion>

v0.8.7
- Added reference to <https://www.scss.tcd.ie/doug.leith/apple_google.pdf> in the Smart Devices section and the OS Telemetry section.
- Moved/rephrased small introduction paragraph about Apple being among the best choices for Privacy in the OS and Telemetry section.
- Changed recommendation for Android VM to Androix-x86 CyanogenMod releases (14.1 r5 at the time of this writing)
- Several small spelling/grammar/layout fixes 
- Added more explanation and illustration to the basic concept of Virtualization through a new Appendix 
- Fixed illustration to mention Tor Stream Isolation possibilities
- Added a couple easter eggs because why not

v0.8.6
- Small layout fixes due to regex errors in pandoc conversion
- Small re-write of the instant messaging section that should make more sense now
- Changed the Briar information to reflect that they do now provide a Desktop option (with limited features) in addition to the Android client (emulator no longer strictly required)
- Updated the messaging table to include qTox (Tox) and Gajim (XMPP)
- Added reference to IDF famous tweet <https://twitter.com/idf/status/1125066395010699264>
- Added some references to Zero-Trust security models
- Added some references to Bad Opsec resources (<https://www.youtube.com/watch?v=eQ2OZKitRwc> and <https://www.youtube.com/watch?v=eQ2OZKitRwc>)
- Added several tools to check an IP or your own IP for various things in the "Your IP Address" section
- Added references to Hybrid Analysis for PDFs in addition to VirusTotal
- Added small additional illustration about threat models in the Introduction
- Added small additional illustration about Privacy vs Anonymity in the Introduction
- Removed the password protected PDF file from the project because it was never used and creaitng more compatibilities issues than necessary on my side
- Replaced donations QR codes with better ones

v0.8.5
- Changed donations QR codes with better ones with logos
- Many small fixes in grammar/spelling/layout
- Fixed many unnecessary escaping backslashes in front of special characters because pandoc does that
- Changed all lines containing code lines into inline code for better readability on the online version
- Migrated my Mastodon account to <https://mastodon.online/@anonypla> (old one redirected automatically)
- Fixed Tor over VPN section that was clearly missing emphasis on it being a viable option with good use cases
- Added more information in the Pick your Connectivity conclusions for a better overview 
- Added section about Online file Syncing in the Online Backup section
- Added more information about messaging apps and a rather detailed table comparing their privacy/security/anonymity features 
- Added disclaimer on reddit/discord to not discuss sensitive topics on those platforms

v0.8.4
- Added more information regarding Tor stream isolation and VPNs
- Added reference to <https://clickclickclick.click> in the Behavior analysis section
- Added project website mirror at <https://mirror.anonymousplanet.org> (hosted at GitLab)
- Added PDFs mirror at CryptPad.from
- Added reference to recently released list of data collected by Google Chrome
- Added reference to <https://www.bbc.com/news/technology-55573802> about Facial recognition defeating Face Masks in the biometrics section
- Added reference to Microsoft Azure Facial Cognitive Services Demo <https://azure.microsoft.com/en-us/services/cognitive-services/face/#demo> in the biometrics section
- Added reference to <https://www.bellingcat.com/news/2021/03/19/berlin-assassination-new-evidence-on-suspected-fsb-hitman-passed-to-german-investigators/> in the biometrics section

v0.8.3
- Added reference to <https://www.reflectacles.com/> glasses to interfere with CCTV surveillance.
- Added "enhance" example to the deblurring section
- Thanks to the anonymous donators. Their donations were spent to renew the domain for 3 more years (4 years total).
- Added information about risks/drawbacks related to Tor Stream Isolation when using VPN over Tor and for which use cases this method is recommended
- Added QR code for BTC legacy address in the donations section

v0.8.2
- Brighter fonts on some headers for better readability in dark mode
- Added reference to Sci-Hub in the introduction
- Added reference to deniable encryption on Linux and why it is not (yet) in the current routes
- Added reference to EncroChat and Sky ECC and warning against using such commercial devices/services for anonymity
- Small fixes in some URLs that were not properly changed after domain switch to anonymousplanet.org
- Added Bitcoin legacy address in addition to Segwit for donations
- Various spelling/grammar issues

v0.8.1
- Fixed many various small layout/spelling/grammar issues
- Fixed 2 shortened URLs (t.me and bit.ly) from the guide with correct destination URLs
- Added some references to "roll your own crypto" cases (Telegram, Zoom)
- Added reference to <https://www.vice.com/en/article/y3g97x/location-data-apps-drone-strikes-iowa-national-guard> in the Metadata/Geolocation section
- Removed archive.today PDF links to replace them with Archive.org links (because archive.today doesn't actually save PDFs)
- Added reference to a MAC tracking device <https://amsignalinc.com/data-sheets/Acyclica/Acyclica-RoadTrend-Product-Sheet.pdf> in the MAC address section
- Added disclaimer about not endorsing Cloudflare in the DNS section by mentioning them several times for technical reasons.
- Added references to Ungoogled-Chromium as an alternative to Tor Browser, Firefox and Brave.
- Added some results of Browser fingerprinting testing by the EFF coveryourtracks project.
- Added reference to Tor Browser security levels which I realized are not known by most people.
- Added Archive.org links to all documents/pages hyperlinks for people willing to avoid direct links to various websites
- Added Invidious (through yewtu.be invidious instance hosted in the NL) links to all YouTube videos hyperlinks for people wanting more privacy on Youtube videos
- Added reference to AMD PSP security analysis (and how it is not as bad as IME) in the "Your CPU" section <https://www.youtube.com/watch?v=bKH5nGLgi08&t=2834s> and the laptop recommendation section.
- Moved the Safe Browser part of Guest OSes into an Appendix to avoid duplication
- Added domain for project <https://anonymousplanet.org/> with donation funds

v0.8.0
- Changed mat2 VM appendix to debian testing (instead of stable) to get latest version of mat2
- Fixed mat2 VM appendix as the network was not working properly with the previous guidance
- Added reference to <https://en.wikipedia.org/wiki/Stylometry>
- Added references to various threat modeling methodologies (LUNDDUN, STRIFE, DREAD, PASTA) and some more in-depth resources for those willing to go further
- Added reference to <https://geekfeminism.wikia.org/wiki/Who_is_harmed_by_a_%22Real_Names%22_policy%3F> in the introduction
- Added reference to <https://gendersec.tacticaltech.org/wiki/index.php/Complete_manual#.22Real.22_names> in the creating identities section
- Multiple spelling/grammar fixes (including email into e-mail, and wifi into wi-fi)
- Added reference to <https://www.whonix.org/wiki/Data_Collection_Techniques> as bonus resources in de-anonymization methods
- Added reference to <https://www.whonix.org/wiki/DoNot> in the OPSEC section because it should be there
- Added reference to <https://www.whonix.org/wiki/Printing_and_Scanning> in the Printing Watermarking section
- Added reference to MIT project SeeingYellow <http://seeingyellow.com/> in the Printing Watermarking section
- Re-Wrote the malware section in the de-anonymization methods for better readability
- Added a specific Anti-Virus section in the Malware checks section with various references and arguments for some selective/limited use.
- Added reference to EFF security scenarios (<https://ssd.eff.org/en/module-categories/security-scenarios>) in the Introduction as examples of threat models for various people.
- Added new section with guidance for safe document publishing including various tool recommendations.
- Added a bit more guidance on malware removal for Pictures and Documents (PDFs, Office Documents...)
- Added Bad Cryptography in the de-anonymization threats with some examples
- Added several Behavior Analysis references in the renamed "Your Digital Fingerprint, Footprint, and Online Behavior" section

v0.7.9
- Updated GitHub Transparency report
- Added information to make animated online identities pictures for increased plausibility
- Added references to the list of services blocking Tor (<https://gitlab.torproject.org/legacy/trac/-/wikis/org/doc/ListOfServicesBlockingTor>)
- Added reference to <https://haveibeenpwned.com/> in the Identities maintenance section
- Added automatic archival and links of the project to Archive.today (through Archive.fo)

v0.7.8
- Various small layout/spelling/grammar fixes
- Added reference to Financial transactions and KYC in the real-name system section
- Added guidance to bypass some local restrictions on supervised computers safely (Appendix Q)
- Added guidance to run TAILS without using Tor in a hostile environment
- Updated UML diagram of various routes to include a non-dedicated laptop
- Changed the whole document to a more formal/cleared grammar for better readability and compatibility with translation engines
- Changed table colors for better readability in dark modes (PDF and Online)

v0.7.7
- Added some acknowledgements to various added Projects
- Changed and improved the "Picking your route" section with the new option (TAILS+Whonix)
- Added basic threat model illustration in the Introduction
- Added basic UML diagram to pick your route
- Added basic UML diagrams for picking your connectivity methods
- Added illustration of the TAILS with HiddenVM option
- Rescaled some images that were way too big 
- Added a whole bunch of platforms to the Online Identities section
- Added more references to German law in the Online Identities section
- Added a legend to the Online Identities overview table

v0.7.6
- Added reference to video visually explaining DNS
- Added some information related to the anonymous use of Bitcoin (vs Monero).
- Added reference to risks of using Crypto Tumblers and Mixers.
- Added reference to the Go Incognito project (<https://github.com/techlore-official/go-incognito>) and their informative YouTube videos for optional introduction before reading this guide.
- Added reference to ExifTool and ExifCleaner to Metadata removal sections for documents (because they also work on those formats)
- Added reference to picture recognition cloaking tools (Fawkes, Adverserial.io, LowKey) for preventing picture recognition algorithms from various platforms.
- Added detailed guidance to create Android guest VMs in the Whonix Route
- Added detailed guidance to create Android Qubes in the Qubes Route
- Added detailed guidance to use Persistent Plausible Deniability with Whonix within TAILS (using HiddenVM project)
- Added Briar, GitLab to the online identities sections
- Added recommended Apps for sharing and communicating anonymously
- Added some acknowledgements to various added Projects

v0.7.5
- Added reference to <https://github.com/rshipp/awesome-malware-analysis> in the Malware analysis appendix
- Many small fixes in layout/spelling/grammar
- Added quotes around VirusTotal "privacy policy" 
- Changed "Exploits in your Apps" to "Malware and Exploits in your Apps"
- Added references to State surveillance using "mandatory" apps such as WeChat.
- Added Wikipedia reference to <https://en.wikipedia.org/wiki/List_of_government_mass_surveillance_projects> 
- Added guidance and references to check files for integrity and authenticity in the "Checking files for malware" section.
- Added emphasis on recommendation of using Tor Browser on the Host OS if Tor is available.
- Removed GPG signatures from markdown and text files to instead sign the whole release for convenience in Contribution workflow.
- Adapted the README to the new signatures
- Added Bitcoin donation option

v0.7.4
- Added reference to Whonix Live mode if you don't want persistence when shutting down the VMs as an added possible safety measure
- Added reference to harden Linux from <https://madaidans-insecurities.github.io/guides/linux-hardening.html>
- Added reference to Linux security issues from <https://madaidans-insecurities.github.io/linux.html>
- Added reference to PDF listing malware analysis tools <https://www.winitor.com/pdf/Malware-Analysis-Fundamentals-Files-Tools.pdf>
- Added reference to SANS Malware Analysis cheat sheet <https://digital-forensics.sans.org/media/analyzing-malicious-document-files.pdf>
- Added reference to the DoHoT project in the DNS section <https://github.com/alecmuffett/dohot> and updated the DNS illustration with this possibility
- Various spelling/grammar fixes
- Started adding some proper code blocks in the online Markdown version and will slowly adopt this in the whole guide in the future
- Fixed the Title missing a T
- Fixed a an hyperlink issue causing PDFID to detect an Automatic Action on guide.pdf 
- Added warning in README concerning VirusTotal "privacy policy"
- Changed the PDFID warnings in the README to better explain their meaning for checking the PDFs published here	
- Started fixing some accessibility issues in the guide (bad indents, empty spaces...)
- Fixed some bad links in cross-references
- Changed link from <https://panopticlick.eff.org/> to <https://coveryourtracks.eff.org/>

v0.7.3
- Added extra-security measures and references for sending cash to a VPN provider safely
- Added reference to sim-swapping in TOTP recommendation (and why SMS 2FA is bad)
- Added VirusTotal scans to all PDFs in the repository (while not endorsing/recommending VirusTotal at all for anything sensitive)
- Added Disclaimer about VirusTotal and their privacy policy in the guide and README
- Added QR code for Monero donations within the guide itself
- Added references in the Phishing section
- Added reference to <https://archive.flossmanuals.net/bypassing-censorship/index.html> in the Safe Access without Tor/VPN appendix
- Added guidance to communicate sensitive information safely to various organization (such as the press)
- Various grammar/spelling/layout fixes

v0.7.2
- Small layout/spelling/grammar fixes
- Added methods to check your surveillance and censorship levels on your Network using various resources.
- Changed site font to Helvetica
- Changed paragraph spacing on PDFs for better readability

v0.7.1
- Switched Github Pages Jekyll theme to Hacker because I prefer dark themes and this one doesn't rely on external fonts (Google).
- Added some references to voice deepfake tech in the Biometrics section
- Slightly changed the styles/colors of the PDFs

v0.7.0
- Added recommendations to consider leaving your smartphone at home online instead of just leaving it powered off or within a faraday bag.
- Added disclaimer stating that this guide is not sponsored by any commercial entity such as VPN providers
- Added specific sections and guidance about the various connectivity schemes (Tor, VPN over Tor, Tor Over VPN, VPN only, VPN over VPN and No Tor/VPN) with various references.
- Added guidance for using Tor Bridges with Tor Browser, TAILS, Whonix and Qubes OS.
- Added last resort guidance for situations where Tor and/or VPN might not be possible options.
- Added guidance to use Long Range Antennas (Yagi type) for connecting to Public Wi-Fis from a safe distance
- Added new face recognition reference and gait recognition reference 
- Added dark themed PDF
- Fixed error in Windows VM installation behind Whonix (missing Network setting)
- Various grammar/spelling fixes

v0.6.9
- Fixes/Adds to the online phone numbers sections. Recommendations based on identification requirements. 
- Grammar/Spelling fixes.

v0.6.8
- Added security disclaimer concerning online phone providers using Monero.

v0.6.7
- Added guidance to possibly get online phone numbers using Monero (less recommended than a Physical Burner Phone with a Pre-paid SIM paid by cash).
- Adapted the various sections of the guide to reflect the above change.

v0.6.6
- Added reference to PornHub biometrics identification statement
- Small various spelling/layout fixes
- Added reference to Project Snowflake from Tor at the end of the guide if you wish you help others evade censorship
- Removed bad link to <https://www.blackbagtech.com/blog/2017/01/13/windows-10-jump-list-forensics/> (no archive available)
- Fixed bad inline reference
- As from now on, all new references in this guide will also be saved to the Internet Archive in case of article removal
- Added privacy vs anonymity in the Introduction
- Added more references to legitimate use of Anonymity from the Whonix and Tor projects

v0.6.5
- Passive automated mirror setup at GitLab <https://gitlab.com/AnonymousPlanet/thgtoa>
- Added Donation Monero address within the guide
- Added README/Guide mention to the GitLab mirror
- Changed CHANGELOG/LICENSE to CHANGELOG.md/LICENSE.md for GitHub Pages integration
- Updated GPG key with GitLab noreply e-mail for commit verification
- Added sitemap on GitHub Pages for SEO
- Added latest version, changelog and alternative pdf download links on Github Pages
- Verified site on Keybase

v0.6.4
- Improved HTML layouts for better readability and SEO
- Added redirect from <https://anonymousplanet.github.io> to the guide page
- Fixed README to to include hyperlinks

v0.6.3
- Added Table of Contents to PDF formats for better readability
- Fixed Appendixes/Sections references in the Markdown/HTML format
- Moved target-audience disclaimer from introduction to start of document
- Small layout fixes

v0.6.2
- Various little kramdown glitches fixed in HTML format
- Small fixes in spelling/grammar
- Added a small disclaimer in the introduction to let people know they can just read the first 26 pages to learn about the various threats without the need for practical applications

v0.6.1
- Various endnotes layout fixes
- Added OSINT YouTube Playlist reference
- Added reference to Whonix Live Host OS documentation (Similar to HiddenVM project)
- Added Twitter account (If it lasts, it was already suspended three times) <https://twitter.com/AnonyPla>. I'd be grateful if you share/like my tweet about this guide.

v0.6.0
- Various small spelling/grammar/layout fixes
- Added various references to Whonix Documentation (Hardening, Anti-Forensics, Anti-Evil Maid...)
- Added one Bellingcat reference to a recent case
- Added some Qubes OS references (Anti-Evil Maid and Hardening)
- Added new sub-route to the TAILS route using the HiddenVM project <https://github.com/aforensics/HiddenVM> for providing Plausible Deniability within TAILS

v0.5.9
- Added Monero accepting VPS providers as options for self-hosting cloud services and self-hosting VPN services

v0.5.8
- Added various references to Whonix documentation (anti-forensics, cold boot attack defenses, full disk encryption)
- Small various fixes
- Added reasoning for not supporting M1 Macs
- Added Acknowledgements at the end of the guide
- Added some resources to cold-boot, evil-maid defenses

v0.5.7
- Added methods to check Trim/ATA/NVMe operations on external SSDs
- Added methods to securely delete data on Qubes OS

v0.5.6
- Added donations/sponsorship support to this project using Monero
- Added reference to Law Enforcement surveillance capabilities (CCC video)
- Added guidance to remove some forensic traces from MacOS 
- Added guidance to remove some forensic traces from Linux (log deletion and trim)
- Added variants for securely erasing SSD drives (only ATA drives were mentioned, added specific info for NVMe drives).
- Added lists of laptop brands supporting Secure Erase (SSD) from BIOS/UEFI.
- Changed recommendation from GParted to System Rescue instead due to GParted not providing nvme-cli by default. 
- Fix: Multiple fixes in SDD/HDD sections (layout, duplicate data...)
- Fix: Multiple fixes in SDD secure erasing section and added various warnings for various methods
- Fix: Removed blkdiscard from wrong section and from MacOS as it's not supported on MacOS by Homebrew
- Various spelling/grammar fixes

v0.5.5
- Added passphrase recommendations (xkcd.com) in the OPSEC section and other sections.

v0.5.4
- Added more information and mitigation possibilities for CPU exploits on Virtual Machines (Spectre, Meltdown...)

v0.5.3
- Added guidance to hidden containers with plausible deniability in the backup section
- Added guidance for online backups
- Added information for VPN kill switches for Whonix, MacOS and Linux

v0.5.2
- Update of GPG key (added no-reply e-mail) to get verified commits

v0.5.1
- Small various fixes

v0.5.0
- Added Watermarking section in threats with pictures/videos/audios watermarks and printer watermarks within

v0.4.9
- Various small spelling/grammar/layout fixes
- Added some Laptop recommendations and more info about Libreboot and Coreboot
- Added various references to key disclosure laws 
- Added guidance to create a mat2-web guest Debian VM for removing metadata from files conveniently
- Changed CHANGELOG to markdown for integrating into GitHub Pages

v0.4.8
- Various fixes on spelling/grammar and layout
- Various fixes on KeepassXC sections for Linux/MacOS
- Added hardening recommendations for Virtualbox
- Added VPN installation tutorials for Linux/MacOS

v0.4.7
- added Virtualbox workaround for Spectre/Meltdown issue mitigation
- added section and guidance to remove metadata from various files and tools
- added reference to Haven app for physical security in OPSEC section
- added recommendation to use systematic TOTP 2FA for online identities when possible
- added references to Deepfakes, facial recognition and fingerprint recognition in biometric threats

v0.4.6 Added link to Shodan to Smart Devices Section, Full rewrite of data wipe sections (especially SSDs)

v0.4.5 Improved SSD/HDD erasure section and some spelling fixes.

v0.4.x Added Backup methods, OPSec tricks, Malicious USB, Printers and various fixes

v0.3.x Added MacOS information and various fixes

v0.2.x Added Qubes OS information and various fixes

v0.1.x Initial Release (missing Qubes OS details and MacOS support)