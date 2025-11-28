# COMPATIBILITY

Firefox 2.0.0.20 - last unofficial working version for Windows 95

Firefox 3.0.19 - last unofficial working version for Windows 2000 Interim Developer's Release Build 1814 - Windows 2000 Beta 3 Build 1946

Firefox 10.0.12 ESR (8.0.1 is recommended for stability) - last unofficial working version for Windows 98/ME with KernelEx, 

Firefox 26.0a1 (20130816) / Firefox 25.0.1 / Firefox 24.8.1 ESR - last unofficial working version for Windows 2000 Beta 3 Build 1969 - Windows Whistler Beta 2 Build 2469

Firefox 35.0.1 / 31.8.0 ESR - last unofficial working version for Windows 2000 SP4 + Update Rollup 1 (without Extended Kernel)

Firefox 52.9.0 ESR - last unofficial version for Windows 98/ME with KernelEx + Core, Windows 2000 with Extended Kernel, and Windows XP RTM & SP1 with kernelxp.dll by wrappers

 For Windows 2000 without Extended Kernel:
 advapixp.dll. kernelxp.dll, userxp.dll, and shellxp.dll by blackwingcat
 wtsapi32.dll, winsta.dll, ws2_32.dll, and iphlpapi.dll from Windows 2000 Extended Kernel. 

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

# NOTES

Make sure you have 7-Zip & CFF Explorer installed.
