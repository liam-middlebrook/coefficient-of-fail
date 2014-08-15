How to tell if a FLOSS project is doomed to FAIL
================================================

## Size:

* The source code is more than 100 MB **+5 points of FAIL**

* If the source code also exceeds 100 MB when compressed **+5 points of FAIL**

## Source Control:

* There is no publicly available source control (e.g. cvs, svn, bzr, git, hg)
  **+10 points of FAIL**

* There is publicly available source control but:

  * There is no web viewer for it **+5 points of FAIL**

  * There is no documentation on how to use it for new users **+5 points of FAIL**

  * You've written your own source control for this code **+25 points of FAIL**

  * You don't actually use the existing source control (e.g. you share zip files
    for weeks at a time to pass code around instead of using a git repo) **+50 points of FAIL**

## Building from Source:

* There is no documentation on how to build from source **+20 points of FAIL**

* If documentation exists on how to build from source, but it doesn't work
  **+15 points of FAIL**

* Your source is configured with a handwritten shell script **+5 points of FAIL**

* Your source is configured by editing flat text config files **+20 points of FAIL**

* Your source is configured by editing code manually **+30 points of FAIL**

* Your source isn't configurable **+20 points of FAIL**

* Your source builds using something that isn't Make or CMake **+5 points of FAIL**

* Your source only builds with third-party proprietary build tools **+30 points of FAIL**

* You've written your own build tool for this code **+75 points of FAIL**

## Libraries

* Your code only builds static libraries **+15 points of FAIL**

* Your code can build shared libraries but only unversioned ones **+15 points of FAIL**

* Your source does not try to use system libraries if present 
  (reinventing the wheel) **+5 points of FAIL**

## System Install

* Your code has no "make install" or equivalent **+20 points of FAIL**

* Your code doesn't work outside of the source directory (no install) **+30 points of FAIL**

## Code Oddities

* Your code has inconsisent line breaks (e.g. "\r\n" vs "\n") **+10 points of FAIL**

* Your code depends on specific compiler feature functionality **+20 points of FAIL**

* Your code depends on specific compiler bugs **+25 points of FAIL**

* Your code depends on functionalities of Microsoft Visual C++ (.NET support for C++)
  **+40 points of FAIL**

## Communication

* Your project doesnt not announce releases publically (e.g. mailing list, GitHub)
  **+10 points of FAIL**

* Your project does not have a bug tracker **+20 points of FAIL**

* Your project does not have a website **+50 points of FAIL**

## Releases

* Your project does not do sanely versioned releases (Major, Minor) **+10 points of FAIL**

* Your project does not do versioned releases **+20 points of FAIL**

* Your project does not do releases **+50 points of FAIL**

* Your releases are only in .zip format **+5 points of FAIL**

* Your releases are only in OSX .zip format **+10 points of FAIL**

* Your releases are only in .rar format **+15 points of FAIL**

* Your releases are only in .arj format **+50 points of FAIL**

* Your releases are only in an encapsulation format that you invented
  **+100 points of FAIL**

* Your release does not unpack into a versioned top-level directory
  (e.g. glibc-2.4.2/) **+10 points of FAIL**

* Your release does not unpack into a top-level directory
  (e.g. glibc/) **+25 points of FAIL**

* Your release unpacks into a completely illogical directory
  structure (e.g. home/user123/programming/new_folder/sources/glibc/new_folder2)
  **+50 points of FAIL**

## History

* Until opening the source your code was proprietary for:

  * 1-2 years **+10 points of FAIL**

  * 3-5 years **+20 points of FAIL**

  * 6-10 years **+30 points of FAIL**

  * 10+ years **+50 points of FAIL**

* Your code doesn't have a license **+100 points of FAIL**

## Documentation

* Your code doesn't have a changelog **+5 points of FAIL**

* Your code doesn't have any documentation **+20 points of FAIL**

* Your website doesn't have any documentation **+50 points of FAIL**

# FAIL Meter

* 0 points of FAIL: Perfect All signs point to success!

* 5-25 points of FAIL: You're doing great!

* 30-60 points of FAIL: You're probably doing okay, but you
  definitely could do better.

* 65-90 points of FAIL: Babies cry when your code is downloaded.

* 95-130 points of FAIL: Richard Stallman eats from his foot
  out of boredomm every time your code is downloaded.

* 130-150 points of FAIL: Kittens die when your code is downloaded.

* 150+ points of FAIL: So much fail it hurts.
