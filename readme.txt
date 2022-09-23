Custom VR Device Driver with OpenVR.

This code can be used to fake a null SteamVR driver. Such a driver can be used
to develop games for SteamVR without an actual headset or VR controllers. The
code is easy to read and modify.

This is the source code of an article by wqaxs36 that used to be hosted in
CodeProject. The original source code is in CustomHMD.zip. I claim no authorship
of this code, but since I found it very useful, I decided to upload it to
github.

The original article went into detail about how to install this custom driver,
but I used an alternate method that uses scripts under InstallScripts. Open
InstallScripts\SteamVR-Custom.bat and look at the source paths. You just need
to copy the relevant files from InstallScripts to the proper paths.