Welcome.

This is a maintained technical guide that aims to provide introduction to various online tracking techniques, online id verification techniques and guidance to creating and maintaining (truly) anonymous online identities including social media accounts safely and legally. No pre-requisites besides English reading are required.

This guide is an open-source non-profit initiative, [licensed] <sup>[[Mirror]][8]</sup> <sup>[[Archive.org]][9]</sup> under Creative Commons Attribution 4.0 International ([cc-by-4.0]) and is not sponsored/endorsed by any commercial/governmental entity.

The latest version is **0.8.7**, See the CHANGELOG at <https://anonymousplanet.org/CHANGELOG.html> <sup>[[Mirror]][10]</sup>

- Latest Online HTML versions at:
	- Main: <https://anonymousplanet.org/guide.html> <sup>[[Mirror]][5]</sup> <sup>[[Archive.org]][6]</sup> <sup>[[Archive.today]][7]</sup> 
	- Main over Tor via Archive.today: <http://archivecaslytosk.onion/anonymousplanet.org/guide.html>

The PDF files in this guide have been checked by VirusTotal and Hybrid-Analysis, see the links (**Note that this guide does not endorse VirusTotal/Hybrid-Analysis at all and it should be used with extreme caution and never with any sensitive files due to their "privacy policy".**)

- Latests PDF versions at:
	- (Light) <https://anonymousplanet.org/guide.pdf> <sup>[[Mirror]][1]</sup> <sup>[[Archive.org]][2]</sup> <sup>[[VirusTotal]][light_virustotal]</sup> <sup>[[Hybrid-Analysis]][light_hybrid_analysis]</sup>
	- (Dark) <https://anonymousplanet.org/guide-dark.pdf> <sup>[[Mirror]][3]</sup> <sup>[[Archive.org]][4]</sup> <sup>[[VirusTotal]][dark_virustotal]</sup> <sup>[[Hybrid-Analysis]][dark_hybrid_analysis]</sup>
	- All latest PDFs are also available on CryptPad at <https://cryptpad.fr/drive/#/2/drive/view/Ughm9CjQJCwB8BIppdtvj5zy4PyE-8Gxn11x9zaqJLI/>

In addition, you can always double check them using PDFID which you can download at <https://blog.didierstevens.com/programs/pdf-tools/>

- Install latest 3.9.x version of Python, Download PDFID and run:

```python pdfid.py file-to-check.pdf```

And you should see these at 0:

```
/JS                    0 #This indicates the presence of Javascript
/JavaScript            0 #This indicates the presence of Javascript
/AA                    0 #This indicates the presence of automatic action on opening
/OpenAction            0 #This indicates the presence of automatic action on opening
/AcroForm              0 #This indicates the presence of AcroForm which could contain JavaScript
/JBIG2Decode           0 #This indicates the PDF uses JBIG2 compression which could be used for obfuscating malicious content
/RichMedia             0 #This indicates the presence rich media within the PDF such as Flash
/Launch                0 #This counts the launch actions
/EmbeddedFile          0 #This indicates there are embedded files within the PDF
/XFA                   0 #This indicates the presence of XML Forms within the PDF
```

SHA256 Checksums of all the PDFs are available within <https://anonymousplanet.org/sha256sum.txt> <sup>[[Mirror]][11]</sup>
SHA256 Checksums of the release files are available within the checksum file at <https://github.com/AnonymousPlanet/thgtoa/releases/latest>

To check the SHA256 Checksums please do the following:

Windows:
- From a command prompt, run ```certutil -hashfile filename.txt sha256```
- Compare the result with the hash in the checksum files.
^
MacOS:
- From a terminal, run ```shasum -a 256 /full/path/to/your/file```
- Compare the result with the hash in the checksum files.

Linux: 
- From a terminal, run ```sha256sum /full/path/to/your/file```
- Compare the result with the hash in the checksum files.

All commits and releases on this repository are signed and verified using the same key. Check for the "Verified" tags.

PDFs, Images and release files are also signed separately using GPG (see the .asc files on the release page and within the repository).

If you don't know how to verify files with GGP signatures, you should first install gpg on your system:
- Windows: Install gpg4win from <https://www.gpg4win.org/download.html>
- MacOS: Install GPG Tools from <https://gpgtools.org/>
- Linux: gpg should be installed by default

Import the GPG key using the following command from a command prompt or terminal:

```gpg --auto-key-locate nodefault,wkd --locate-keys 0xEB16B6AB4AB7BA61F33E2DFD0051E9A589DAB601```

If it doesn't work, you can also download/view it directly from here: <https://anonymousplanet.org/AnonymousPlanet_0x89DAB601_public.asc> <sup>[[Mirror]][12]</sup>

And then import it manually by issuing the following command:

```gpg --import AnonymousPlanet_0x89DAB601_public.asc```

Finally verify the files by issuing the following commands: 

```gpg --verify guide.pdf.asc guide.pdf"```

```gpg --verify guide-p.pdf.asc guide-p.pdf"```

```gpg --verify guide-dark.pdf.asc guide-dark.pdf"```

You can also verify the authenticity of this GPG signature using my Keybase.io profile <https://keybase.io/anonymousplanet> and the PGP key is also published on <http://keys.gnupg.net/>, <https://pgp.mit.edu/>, <https://keys.openpgp.org> and <https://keyserver.ubuntu.com/> using the following PGP fingerprint: ```0xEB16B6AB4AB7BA61F33E2DFD0051E9A589DAB601```

Feel free to submit issues using Github Issues or discuss using Github Discussions.

If you'd like to make a donation to this project, you can do so from <https://anonymousplanet.org/donations.html> <sup>[[Mirror]][13]</sup>.

Follow or contact me on: 
- Twitter: <https://twitter.com/AnonyPla> (cannot guarantee this account will stay up for long tho)
- Mastodon: <https://mastodon.online/@anonypla> 
- Element/Matrix.org: ```@anonypla:privacytools.io```
- Reddit: <https://old.reddit.com/message/compose/?to=AnonyPla>
- E-Mail: <contact@anonymousplanet.org> (**this is one-way only for now, I won't answer back through this channel**)

Discussion Channels (**be careful as none of those are actively moderated**):
- Reddit: <https://old.reddit.com/r/thgtoa/>
- Discord Server: <https://discord.gg/XGFfGtJmXd>
- Github Discussions: <https://github.com/AnonymousPlanet/thgtoa/discussions>

Have a good read and feel free to share it!

[cc-by-4.0]: https://creativecommons.org/licenses/by/4.0/
[licensed]: https://anonymousplanet.org/LICENSE.html
[light_virustotal]: https://www.virustotal.com/gui/file/75fbfef8ecc75a7d1e7599512454665814e63b23cdcb663aba895549c9622ecf/detection
[light_hybrid_analysis]: https://hybrid-analysis.com/sample/75fbfef8ecc75a7d1e7599512454665814e63b23cdcb663aba895549c9622ecf
[dark_virustotal]: https://www.virustotal.com/gui/file/3050e33a1f43d62a616b05cfac27914a347b09253fe5962aa3897c9c8e28ec94/detection
[dark_hybrid_analysis]: https://hybrid-analysis.com/sample/3050e33a1f43d62a616b05cfac27914a347b09253fe5962aa3897c9c8e28ec94
[1]: https://mirror.anonymousplanet.org/guide.pdf 
[2]: https://web.archive.org/web/https://anonymousplanet.org/guide.pdf
[3]: https://mirror.anonymousplanet.org/guide-dark.pdf 
[4]: https://web.archive.org/web/https://anonymousplanet.org/guide-dark.pdf
[5]: https://mirror.anonymousplanet.org/guide.pdf 
[6]: https://web.archive.org/web/https://anonymousplanet.org/guide.pdf
[7]: https://archive.fo/anonymousplanet.org/guide.html
[8]: https://mirror.anonymousplanet.org/LICENSE.html
[9]: https://web.archive.org/web/https://anonymousplanet.org/LICENSE.html
[10]: https://mirror.anonymousplanet.org/CHANGELOG.html
[11]: https://mirror.anonymousplanet.org/sha256sum.txt
[12]: https://mirror.anonymousplanet.org/AnonymousPlanet_0x89DAB601_public.asc
[13]: https://mirror.anonymousplanet.org/donations.html
