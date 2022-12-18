# samples/flixel_zip_sys

This sample demonstrates the use of Polymod with the Flixel framework.

It includes several sprites and text files, and demonstrates file loading using the SysZipFileSystem, which is the ZipFileSystem provided on native platforms. Note that SysZipFileSystem is a hybrid file system; it also allows reading mods from unarchived folders as well.

This sample is dependant on native-specific features, and will not work on other platforms. Please see the `flixel_zip_html5` sample for a web version.