# python3-tar-copy-failure
A test case for the Python TarFile library

This tests the TarFile library ability to write what it reads.
It turns out that the resulting .tar file is not properly formatted, and a number of files are not seen by bsdtar, GNU tar or emacs tar-mode.
