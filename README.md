# termux-bits
Various bits relating to Termux on Android and its packages

At the moment this just contains a version of wget
for Termux on Android that is essentially the
standard source code but which has been rebuilt
by myself for Android 10.

This was to overcome a problem encountered with
the standard wget package which failed when wget
was executed with the error:
`
CANNOT LINK EXECUTABLE "wget": cannot locate symbol
"__aeabi_idiv0" referenced by
"/data/data/com.termux/files/usr/bin/wget"...
`

