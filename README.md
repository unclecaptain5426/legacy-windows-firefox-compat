# COMPATIBILITY

Firefox 2.0.0.20 - last unofficial working version for Windows 95

Firefox 3.0.19 - last unofficial working version for Windows 2000 Interim Developer's Release Build 1814 - Windows 2000 Beta 3 Build 1946

Firefox 10.0.12 ESR (8.0.1 is recommended for stability) - last unofficial working version for Windows 98/ME with KernelEx, 

Firefox 26.0a1 (20130816) / Firefox 25.0.1 / Firefox 24.8.1 ESR - last unofficial working version for Windows 2000 Beta 3 Build 1969 - Windows Whistler Beta 2 Build 2469

Firefox 35.0.1 / 31.8.0 ESR - last unofficial working version for Windows 2000 SP4 + Update Rollup 1 (without Extended Kernel)
 
 For Windows 2000 without Extended Kernel:
 advapixp.dll. kernelxp.dll, userxp.dll, and shellxp.dll by blackwingcat
 wtsapi32.dll, winsta.dll, ws2_32.dll, and iphlpapi.dll from Windows 2000 Extended Kernel. 
 
Firefox 48.0.2 / 45.9.0 ESR - last unofficial working version for Windows XP Release Candidate 1 build 2474 - Windows XP Release Candidate 1 build 2509 with kernelxp.dll by roytam1with kernelxp.dll by roytam1

Firefox 52.9.0 ESR - last unofficial working version for Windows 98/ME with KernelEx + Core, Windows 2000 with Extended Kernel (up to 53.0.3 unofficially), and Windows XP Release Candidate 2 build 2517 - Windows XP SP2 build 2600.1213 with kernelxp.dll by roytam1

 For starting with Windows XP build 2600.2055+, it does not need kernelxp.dll wrappers by roytam1 and thus can run since DecodePointer/EncodePointer functions were added.
 
 Firefox 53 on Windows XP/2003 without One-Core API is not impossible but it can be unstable.
 
# DISCLAIMER

This guide is an unofficial, community-made compatibility guide. It is NOT affiliated with, endorsed, or supported by Mozilla or Microsoft. All product names, trademarks, and copyrights belong to their respective owners. This repository does not contain any proprietary Mozilla binaries. It only documents compatibility behavior on legacy Windows systems.

All binaries must be obtained by the user from official sources only. This guide does not provide or link to any downloads.

# WORD OF CAUTION

Please do not use an older version of Mozilla Firefox as a daily driver. It must be for testing purposes only.

# BUGS

 Compatibility:
 
 Windows 2000 Beta 3 Build 1964 & Windows 2000 Beta 3 Build 1965:
 
Firefox 13+ is not known to work on Windows 2000 Beta 3 Build 1964 & Windows 2000 Beta 3 Build 1965, due to enforced ADVAPI32 functions after 13.0a1 (20120201) / 12.0 / 10.0.12 ESR, even with wrappers.

 Windows 2000 SP4 + Update Rollup 1 (without Extended Kernel):

Firefox 36+ is not known to work on Windows 2000 SP4 + Update Rollup 1 (without Extended Kernel), due to BWC's wrappers have not been updated since 2012 after 35.0.1 / 31.8.0 ESR, even with wrappers.

 Windows XP Service Pack 2 pre-release builds:

Firefox 36 - 48.0.2 / 45.9.0 ESR 

# NOTES

Make sure you have 7-Zip & CFF Explorer installed.
