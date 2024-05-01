![51Degrees](https://51degrees.com/DesktopModules/FiftyOne/Distributor/Logo.ashx?utm_source=github&utm_medium=repository&utm_content=home&utm_campaign=c-open-source "Data rewards the curious") **Device Detection Data Files**

# Introduction

This repository contains the freely available 'lite' version of the 51Degrees device detection data file.

The properties available in this file are: 
- IsMobile
- ScreenPixelsHeight
- ScreenPixelsWidth
- PlatformName
- PlatformVersion
- PlatformVendor
- BrowserName
- BrowserVersion
- BrowserVendor
- SetHeaderBrowserAccept-CH
- SetHeaderHardwareAccept-CH
- SetHeaderPlatformAccept-CH
- JavascriptGetHighEntropyValues
- JavascriptHardwareProfile
- More properties are available for free in our [cloud service](https://configure.51degrees.com/), or on a commercial basis on [our website](https://51degrees.com/pricing).

This 'lite' file is built from a subsection of all devices and is updated less frequently than the paid-for data files.

This repository uses [Git LFS](https://git-lfs.github.com/) rather than storing these large binary files directly.

# Files

- 51Degrees-LiteV4.1.hash - The 'lite' on-premise device detection data file.
- 20000 User Agents.csv - A test file containing 20,000 of the most commonly observed User-Agent values. Each line contains a single User-Agent.
- 20000 Evidence Records.yml - A test file containing 20,000 of the most commonly observed sets of headers that are useful for device detection. This is a replacement for the 20000 User Agents file that includes values for [User-Agent Client Hints](https://learnclienthints.com/). This is a multi-record yaml file where each line contains the HTTP header name and value as the key/value pair. Values may be wrapped in single quotes.
