### Calibration Tools
---

#### About

Calibration Tools is a Windows application which manages your monitor calibration.  It was created to provide more control over monitor calibration.

#### Features

* Create and edit monitor calibration files: adjust backlight, white balance, overall gamma, shadow detail gamma, 10-band gamma, s-curve, highlights.
* Enforce separate day/night files with automatic dawn/dusk times and gradual transition during twilight.
* Test for calibration hijacking in games, and solve with ReShade or borderless full screen windowed mode.
* Enforce per-game calibration files.
* Enable dithering on Nvidia GPUs for smoother gradients.
* Portable, malware-free, ad-free, nag-free (VirusTotal.com no detections: [v1.0](https://www.virustotal.com/gui/file/5a99eebcfee40aa4630ac70bca0082c110b814851f92000a79511f30f469e874/detection); [v1.0b](https://www.virustotal.com/gui/file/32ecbcef96ecadd331349b234041ea2b167fe97ce4ea4bcdf95a0bac0c865244/detection))

#### System Requirements

* 64-bit Windows, Vista or later.
* Logged in as a Windows administrator.
* Windows display scaling set to a multiple of 25.
* Video card supporting gamma tables for monitor calibration.
* [DirectX June 2010 update](https://www.microsoft.com/en-us/download/details.aspx?id=8109) (not included with Windows or subsequent DirectX updates).

#### Current Issues
* **Windows 10 version 1903 (May 2019) contains bugs in its colour management system which affect Calibration Tools.  For possible solutions, see [here](https://hub.displaycal.net/forums/topic/windows-10-1903-please-read/).**
* **api.sunrise-sunset.org sometimes breaks due to an expired certificate on their server, causing the "twilight transition" feature (if enabled) to throw an error message when it tries to update your dawn & dusk times.  You may workaround this by setting HTTPS=0 in Config.ini.  An update to Calibration Tools may be forthcoming to fix this issue permanently as it is a reoccurring problem with the sunrise-sunset server.**
* **For a long time CalibrationTools.exe showed no detections at VirusTotal.com, however vendors are constantly updating their virus signatures and must continually be chased to remove false positives.  Some of them do not respond to emails, eg. Trapmine.**

#### Changelog

* [2021-06-15] v1.0b: fixed missing icons error message if Windows display scaling is not multiple of 25.
* [2020-03-18] v1.0: initial release.

#### Screenshots

![Alt text](https://bitbucket.org/CalibrationTools/images/downloads/screenshots.png)

#### Donate
Bitcoin: 1CALTLSdHctke7hryfMuG43EqVv7gSP88z

![Alt text](https://bitbucket.org/CalibrationTools/images/downloads/qr178bl.png)

Thank you!