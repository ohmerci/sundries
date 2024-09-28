>> MooSFV 1.84 Readme

Table of Contents
1) Introduction
2) Goals
3) Version History
4) How to Use
5) WinSFV Compatability?
6) Contact
7) End User License Agreement


>> 1 Introduction

MooSFV is a standalone CRC and MD5 creation/verification program for
Windows 9x/NT/2000/ME/XP. Written in C/C++.  MooSFV currently can verify
and create SFV files (CRC/32), MD5 files (Message-Digest 5), and a new
format which I have dubbed 'MD5M3U' (Combination MD5 and M3U Playlist).
This program was built primarily because I didn't like the WinSFV verify
interface - I would spend way too many clicks / keystrokes just to
verify my files.  Since the initial MooSFV release, you just select
the SFV file, and it verifies all of the files in it.


>> 2 Goals

My primary goals of MooSFV's initial release was to:
  1) Reduce the amount of clicks to verify my damn RAR/MP3s :O
  2) 1-file program.  No Directories full of garbage, just 1 exe file
  3) Make sure it creates and verifies SFV files properly

My future goals for MooSFV:
  1) Recursive Creation/Verification
  2) Fix bugs, implement ideas sent in by form/e-mail
  3) Improve SFV/MD5 file creation interface

>> 3 Version History

v1.0 - Original (crappy) Release
v1.1 - Changed file results/progress from text to small icons
       Fixed crash from creating sfv from root directory
v1.2 - Added drag and drop SFV verify
       Improved SFV file detection
v1.3 - Threaded the verify/creation process
       Replaced "Delete Bad Files" with "Rename Bad Files"
       Tightened up the GUI a bit
v1.4 - Fixed crash from verifying bad files
       Comment files can be added when creating files
v1.5 - Changed form layout, fixed resizing with different 'Schemes'
       Fixed being able to add a sfv file into the same sfv file
v1.6 - Added MD5 Creation/Verification
       Added ability to add one line comments to sfv files
       Fixed crash from trying to create file on read-only media
       Changed Hot Keys to allow Cut, Copy, & Paste into text boxes
       Added ability to verify selected files in a sfv file
v1.61- Fixed problem with reading in MD5 files with spaces in the filename
       Made a few aesthetic changes
v1.7 - Auto register of .sfv files
       Saves and reloads program size and position on open
       Reduced 'moosfv'-pimping in comments when creating files
       Hitting enter after sfv/md5 name will start create process
       Fixed SFV file display when opening from start
v1.8 - .sfv registration now an option instead of automatic
       Added new MD5M3U filetype
       Select verify now available for all verification types
       New 'scene-like' file info commenting available
       Fixed auto-verify sfvname display
       Fixed XP titlebars
       Some code/routine cleanup
v1.81- Fixed/Added new hot keys
v1.82- Improved SFV file detection
       Added drag and drop functionality for SFV verify
v1.83- New icons
       Fixed drag and drop bug
       Fixed sfv command-line directory bug
       Fixed sfv command-line file-id problem
v1.84- SFV file detection fix
     - New Email/Website at ubercow dot com
     
       

>> 4 How to Use

Verifying Files: From the menubar, go to File->Verify.  Select the CRC
File that you want to verify and hit the Open Button.  The files will be
loaded into the main listbox and verified.  A "Green O" next to the file
means it passed verification.  A "Red X" next to the file means it did not
pass verification.  A "Blue ?" next to the file means that the file does
not exist.

Creating Files: From the menubar, go to File->Create.  Go to the directory
that you want to create an SFV/MD5/M3U file for, select all of the files,
and hit the Open Button.  A default SFV/MD5/M3U filename will appear in the
textbox, this can be changed to whatever you want.  If you want your SFV
file to be compatible with WinSFV, make sure you check the WinSFV Compatible
checkbox. If you want to add comments to your SFV file, Select the type of
comment you want to add in the comment combobox. Hit the go! button and it
will create your SFV/MD5 file.  If 'Add Comment File' is selected it will
bring up a dialog box where you select the comment file you want added. If
'Add One Line Comment' is selected, it will bring up an empty textbox where
you should type in your one line comment. If 'Add File Info Comment' is
selected then it will add filesize and last modify date for each file to the
top of the comment area

Select Verification: From the menubar, go to File->Select_Verify. Select the
CRC File that you want to verify and hit the Open Button. Highlight all of
the files that you want to verify then press the go! button.   A "Green O"
next to the file means it passed verification.  A "Red X" next to the file
means it did not pass verification.  A "Blue ?" next to the file means that
the file does not exist.

Drag and Drop Verify: Grab a SFV file and drop it on either the MooSFV
executable icon or on a shortcut to MooSFV.  It will then verify the SFV.


>> 5 WinSFV Compatability?

WinSFV (along with sfv32nix) requires that the first line of the SFV file
have one of that particular programmer's headers in the first line or it
will not work.


>> 6 Contact

If you find any bugs, or have any improvement ideas, you can get in touch
with me by going to MooSFV's homepage http://www.ubercow.com/moosfv
or you can contact me via email: moosfv at ubercow d0t com


>> 7 EULA

I'm not sure what kind of person would sue over FREEWARE, but just in case
someone like that is out there, I'm slapping this End User License Agreement
onto the end of my README.

DISCLAIMER OF WARRANTY. THE SOFTWARE IS PROVIDED FREE OF CHARGE AND,
THEREFORE, ON AN AS-IS BASIS, WITHOUT WARRANTY OF ANY KIND, INCLUDING
WITHOUT LIMITATION THE WARRANTIES THAT IT IS FREE OF DEFECTS,
MERCHANTABLE, FIT FOR A PARTICULAR PURPOSE, OR NONINFRINGING. THE ENTIRE
RISK AS TO THE QUALITY AND PERFORMANCE OF THE SOFTWARE IS BORNE BY LICENSEE.
SHOULD THE SOFTWARE PROVE DEFECTIVE IN ANY RESPECT, LICENSEE AND NOT
LICENSOR OR ITS SUPPLIERS OR RESELLERS ASSUMES THE ENTIRE COST OF ANY
SERVICE AND REPAIR. IN ADDITION, THE SECURITY MECHANISMS IMPLEMENTED BY
THE SOFTWARE HAVE INHERENT LIMITATIONS, AND LICENSEE MUST DETERMINE THAT
THE SOFTWARE SUFFICIENTLY MEETS ITS REQUIREMENTS. THIS DISCLAIMER OF
WARRANTY CONSTITUTES AN ESSENTIAL PART OF THIS AGREEMENT. TO THE MAXIMUM
EXTENT PERMITTED BY APPLICABLE LAW, IN NO EVENT WILL LICENSOR OR ITS
SUPPLIERS OR RESELLERS BE LIABLE FOR ANY INDIRECT, SPECIAL, INCIDENTAL,
OR CONSEQUENTIAL DAMAGES ARISING OUT OF THE USE OF OR INABILITY TO USE THE
SOFTWARE.
