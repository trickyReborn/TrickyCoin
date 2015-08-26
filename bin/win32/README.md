## TrickyCoin-Qt & TrickyCoind v.1.0.2.0 binaries for Windows.

#BEFORE DOWLOADING AND EXECUTING

Please **be absolutely sure to FULLY backup your TrickyCoin directory (not only wallet.dat), because Berkeley DB is only forward compatible, which means you NEVER can use newly created data using TrickyCoin-Qt compiled with any previous Berkeley DB library anymore.**
Default location of TrickyCoin data directory for windows is %APPDATA%\TrickyCoin

Here you can download [**TrickyCoin-Qt v.1.0.2.0**](http://www.trickycoin.com/dl/1.0.2.0/TrickyCoin-Qt.zip) build using:
* Qt 5.5 (static, which means no .dll files needed) with mingw32-i686 gcc v.4.92 (included to Qt 5.5).

Libs used:
* boost v.1.59
* Berkeley DB v.6.1.26
* openssl v.1.0.2d
* miniupnpc v.1.9.

Added an [**UPX-compressed TrickyCoin-Qt binary**](http://www.trickycoin.com/dl/1.0.2.0/TrickyCoin-Qt-UPX.zip) (UPX v.3.91w).

    TrickyCoin-Qt.exe MD5: 3f2186026270b8f9e5ebfce90863d014 
    TrickyCoin-Qt.zip MD5: 7b0d65baed336df54199631695e5f785
    TrickyCoin-Qt-UPX.exe MD5: 9d3e04ffaf3c7332edf3243562b669a6
    TrickyCoin-Qt-UPX.zip MD5: 3a845a1c3cde130663247324521d27bf

All other hashes included in repository.

[**TrickyCoind v.1.0.2.0**](http://www.trickycoin.com/dl/1.0.2.0/TrickyCoind.zip) (static) build using:
* MSYS2 with mingw32-i686 gcc v.5.2 (thanks to pacman package manager).

Libs used:
* Boost v.1.59
* Berkeley DB v.6.1.26
* openssl v.1.0.2d
* miniupnpc v.1.9

Added an [**UPX-compressed TrickyCoind binary**](http://www.trickycoin.com/dl/1.0.2.0/TrickyCoind-UPX.zip) (UPX v.3.91w).

You can build 'em by yourself. All process will be posted on forum and github repository ASAP.