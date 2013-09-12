Volatility profiles
===================

A collection of profiles for [Volatility][1] - a completely open collection of tools, implemented in Python under the GNU General Public License, for the extraction of digital artifacts from volatile memory (RAM) samples.

This a public repository containing Volatility profiles that were either found on the Internet or contributed by Volatility users. Feel free to push your own profile if it's not in the repo yet. Though there's no certain naming rule or scheme, it's nice to mention the following in the profile (.zip) name:

- Platform (e.g. "Linux")
- OS (e.g. "Ubuntu")
- Kernel or OS version (e.g. "3.2.0-23-generic" in case of Linux or "10.7.3" in case of Mac OS X)
- Bitness (x86/x64/what_not)
- Other important characteristics like [PAE][10], if the Linux kernel was compiled with _Physical Address Extension_ support. You should append "-pae" to the name of the profile then (see those already in the repo).

If you wish to help but unsure how to create Volatility profiles, here are some links which are part of the official documentation:

- [How to create profiles for Linux][2]
- [How to create profiles for Mac OS X][3]
- [How to create profiles for Android][4]

Currently there are a few profiles for Ubuntu which were downloaded from [here][5], various Linux and Mac profiles are from Volatility's page [1][6] and [2][7]

PS. If you push a profile you can also tweet about it with hashtag [#volatilityprofile][8] or [#volatility][9]

![][11]

[1]: https://code.google.com/p/volatility/ "Volatility tool's home page @ Google Code"
[2]: https://code.google.com/p/volatility/wiki/LinuxMemoryForensics "How to create profiles for Linux"
[3]: https://code.google.com/p/volatility/wiki/MacMemoryForensics "How to create profiles for Mac"
[4]: https://code.google.com/p/volatility/wiki/AndroidMemoryForensics "How to create profiles for Android"
[5]: http://pleasefeedthegeek.wordpress.com/2012/12/03/ubuntu-profiles-for-volatility/
[6]: https://code.google.com/p/volatility/wiki/LinuxProfiles
[7]: https://code.google.com/p/volatility/downloads/list
[8]: https://twitter.com/#volatilityprofile
[9]: https://twitter.com/#volatility
[10]: https://en.wikipedia.org/wiki/Physical_Address_Extension
[11]: http://nojsstats.appspot.com/UA-43977491-1/github.com
