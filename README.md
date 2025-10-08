
## Programs and Documentation

by: Keith Fenske
<br>https://kwfenske.github.io/
<br>February 2019

Copyright &copy; 2011-2025 by Keith Fenske. Send e-mail
to [this address](email-address.gif "github dot kwfenske at gmail dot com").
Project page: https://github.com/kwfenske

(These files host a web site on GitHub Pages and are better if you view them at
https://kwfenske.github.io/ as HTML in your web browser. This "README.md" file
is a reduced version of the "index.html" file, and downloads are less direct.)

### Documentation

Most documentation here is in Adobe Acrobat PDF format. See
the [Adobe download page](https://get.adobe.com/reader/) for a free copy of
Adobe Reader, or
this [Wikipedia page](https://en.wikipedia.org/wiki/List_of_PDF_software) for a
list of alternative PDF software. Many computer systems have their own PDF
readers. ZIP links below have source and a license.

- [Character Maps For Windows](character-maps-for-windows.pdf) (PDF, 242 KB;
or [ZIP](character-maps-for-windows.zip)): Text fonts have more characters than
you see on your keyboard: special symbols and accented letters for French,
German, Italian, Spanish, etc.

- [Running Java Programs](running-java-programs.pdf) (PDF, 60 KB;
or [ZIP](running-java-programs.zip)): How to run Java programs on Windows
XP/Vista/7. Windows 8 and 10 are similar, once you find the elusive Command
Prompt, as are Linux and MacOS in a Terminal window.

- [Socket and Wrench Sizes](socket-wrench-sizes.pdf) (PDF, 31 KB;
or [ZIP](socket-wrench-sizes.zip)): Metric tools are normally for metric
fasteners and SAE tools for SAE fasteners. Some metric sizes (millimeter, mm)
are almost the same as SAE sizes (fractional, imperial, inch, standard). You
may also try a [program](metric-sae-sizes-java.zip) that did the numbers for
this chart.

### Icons

The following icons are for Windows. Each icon has multiple sizes in a single
ICO file, which is downloaded inside a ZIP file. The icons themselves are not
compressed and should open in any icon editor, including "IconEdit" listed in
the next Java section.

- [Alphabet Web Icons](alphabet-web-icons.zip) (ICO in ZIP, 1548 KB): Outline
letters and digits as program icons for Microsoft Windows or as "favicon.ico"
files on web pages (bookmark icons).

- [Generic Icon](generic-program-icon.zip) (ICO in ZIP, 24 KB): A placeholder
for when you need an icon but don't have time yet to design a new one.

- [Happy Face Icon](happy-face-icon.zip) (ICO in ZIP, 23 KB): Brighten up the
day with this classic "happy face" icon. Available in a range of sizes from
16x16 to 256x256 pixels. Or make your own from the Microsoft "Wingdings" font
(in the same character position as the capital letter "J").

- [Size Test Icon](size-test-icon.zip) (ICO in ZIP, 30 KB): Way back when in
Windows XP (2001), a big icon was 64x64 pixels. Now you need 256x256 plus
16x16, 32x32, 48x48, and several more depending upon a system's DPI display
setting (usually 100% for 96 DPI, 125% for 120 DPI, or 150%). There is no
guarantee that Windows will use any given size, even if defined in an icon
file. Many will be scaled down from 256x256. Others will sometimes be used and
sometimes won't. This test icon has each size labelled with the number of
pixels, with sharp edges and an outline so you can see if Windows is resizing
from another size. Defined sizes are from 8x8 to 32x32 in steps of 2, from
32x32 to 64x64 in steps of 4, from 64x64 to 128x128 in steps of 8, and from
128x128 to 256x256 in steps of 16.

### Java Programs

Java software on this web site is free and has been released under
the [Apache License](https://www.apache.org/licenses/LICENSE-2.0) or
the [GNU General Public License](https://www.gnu.org/licenses/gpl.html) (GPL).
The same Java programs will run on Linux, MacOS, Windows, etc. You may need to
download the Java "[run-time environment](https://www.java.com/download/)"
first. All packages are
in [ZIP format](https://en.wikipedia.org/wiki/ZIP_%28file_format%29) and
include brief installation instructions.

- [Character Map](character-map-java.zip) (Java, ZIP, 1177 KB): CharMap is a
Java 5.0 graphical (GUI) application to display Unicode characters or glyphs in
text fonts, and copy those characters to the system clipboard. Its major
purpose is as a visual accessory for word processors such as Microsoft Word.
This Java application can be resized, for text and the program window, which is
important in many languages. Features are limited to make the application
faster and simpler to use. A single click adds a character to the sample text,
and the sample text is automatically copied to the system clipboard on each
click. The most recent [data file](character-map-data.zip) is for Unicode
17.0.0 (September 2025).

- [Compare Folders](compare-folders-java.zip) (Java, ZIP, 322 KB):
CompareFolders is a Java 1.4 application to compare two folders to determine if
all files and subfolders are identical. The folders may be on the same
computer, on the local network, or they may be represented by checksum files.
Files or subfolders that are not the same are reported to the user. Checksum
files are used when the original files or folders are not available. You may
generate checksums for files and folders, and save those checksums in a text
file. You may compare two checksum files. You may compare a checksum file and a
folder of files. After you back up files to external media, and later restore
them, how will you know they are correct unless you have checksums from the
original files?

- [Drive Speed](drive-speed-java.zip) (Java, ZIP, 229 KB): DriveSpeed is a Java
1.4 graphical (GUI) application to test the speed of disk drives or flash
drives. Large temporary files are written with all zero bytes, then read back.
To get accurate results, files must be bigger than the amount of physical
memory on your computer (RAM), and should be several times bigger, because your
computer uses some of its memory as a "disk cache" to increase the apparent
speed of drives.

- [Erase Disk](erase-disk-java.zip) (Java, ZIP, 273 KB): EraseDisk is a Java
1.4 graphical (GUI) application to erase and test disk drives or flash drives.
Large temporary files are created and filled with zeros, ones, or pseudo-random
data. Previously deleted files are overwritten. Existing files are not
affected. This cleans up an old disk before it goes in a new location. Don't
trust a new disk until you write data, then read to confirm. One complete test
is usually enough. (Repeated testing may degrade flash drives.)

- [File Checksum](file-checksum-java.zip) (Java, ZIP, 241 KB): FileChecksum is
a Java 1.4 application to compute common checksums for files: CRC32, MD5, SHA1,
and optional SHA256 or SHA512. Checksums are small hexadecimal "signatures" for
testing whether or not files have been copied correctly, such as over a
network. One person sends a file along with the checksum computed on the
original computer. A second person calculates a similar checksum for the
received file, and if the two checksums agree, then the received file is
assumed to be correct. Many web sites provide MD5 signatures for their
downloads; use this program to verify files that you download. The MD5 for this
ZIP file is 20f3cf21a3e1a88222f4e2477d3980e5.

- [File Redate Rename](file-redate-rename-java.zip) (Java, ZIP, 249 KB):
FileDateName is a Java 1.4 graphical (GUI) application to rename multiple files
or to change their directory dates. The contents of the files are not changed.
Folders and subfolders may be searched recursively. Changes may be applied to
files only, both files and folders, or only the folders.

- [Find Duplicate Files](find-duplicate-files-java.zip) (Java, ZIP, 218 KB):
FindDupFiles is a Java 1.4 application to find duplicate files by searching for
files that have the same size and the same MD5 checksum. It won't find files
that are merely similar, such as two consecutive photos of the same subject, or
two MP3 songs encoded at different times. Possible duplicates are reported to
the user, who can then verify that the files are identical, either by
inspection or by doing a byte-by-byte comparison with the "comp" command on
DOS/Windows or the "cmp" command on Linux. What to do with files is the user's
choice; the program does nothing except report the duplicates. The probability
of two different files having the same size and MD5 checksum is extremely
small. (Slower and stronger SHA256 version
is [here](find-duplicate-files-sha256-java.zip).)

- [Font Rename](font-rename-java.zip) (Java, ZIP, 282 KB): FontRename is a Java
1.4 application to rename OpenType and TrueType font files with their internal
"font full name" using only plain text characters (ASCII) plus an extension for
the type (OTF, TTC, TTF), or using the full Unicode character set in languages
like Arabic, Chinese, Japanese, Korean, and Russian. This gives consistent
names to font files, no matter what their source. The contents of the files are
not changed, only the names in the file directory. Don't use this program on
system folders with installed fonts. See also:
[Font Checksum](font-checksum-java.zip),
[Font Names](font-names-java.zip),
[Font Redate](font-redate-java.zip).

- [Hex File Viewer](hex-file-viewer-java.zip) (Java, ZIP, 242 KB): HexView is a
Java 1.4 graphical (GUI) application to display the contents of a file in
hexadecimal and as plain text (7-bit ASCII). Files may be very large. Editing
and searching are not supported. See also: [Dump File](dump-file-java.zip),
[Hex File Editor](hex-file-editor-java.zip).

- [Icon Editor](icon-editor-java.zip) (Java, ZIP, 301 KB): IconEdit is a Java
1.4 graphical (GUI) application to edit icon files for Windows. An icon file
has several images in sizes like 16x16, 24x24, 32x32, 48x48, and 64x64 pixels.
Icons are square from 8x8 to 256x256 pixels. Colors may be 4-bit (16 colors),
8-bit (256 colors), or 24-bit (millions). Pixels may be transparent and let
the background show through. Please note that IconEdit is an old program and
does not support alpha channels, compressed data (PNG images), or icons larger
than 256 pixels.

- [Maze Fog Game](maze-fog-game-java.zip) (Java, ZIP, 242 KB): MazeFog is an
old Java 1.1 AWT (GUI) applet to play a maze game. Your view is limited by a
"fog" that shows nearby positions and those you have already visited. Web page
applets are obsolete and may run as stand-alone applications with the help of a
wrapper (included), although this becomes less likely after Java 9 (2017).
Rewriting for Java Swing or newer JavaFX is not an easy job. See also:
[Dots and Boxes](dots-and-boxes-game-java.zip),
John Conway's Game of [Life](life-game-java.zip),
[Reversi](reversi-game-java.zip),
[Tic-Tac-Toe](tic-tac-toe-game-java.zip).

- [Plain Text](plain-text-java.zip) (Java, ZIP, 244 KB): PlainText is a Java
1.4 graphical (GUI) application to convert Unicode characters to plain text
characters, for example, to convert left and right quotation marks into plain
quotes for web pages. Since everyone has a different idea about what "plain
text" means, the conversion is controlled by a configuration file that can be
easily edited. The typical sequence of actions is to copy text from a
Unicode-aware application such as Microsoft Word, switch to this Java
application, click the "Paste" and "Convert" buttons, then copy the converted
text to another application that expects a more limited character set. Or
create a [data file](plain-text-data.zip) that replaces non-ASCII text with
Unicode character numbers and descriptions. See also: Character Map (above),
Check Plain Trim (below).

GNU General Public License (GPL) programs are free to use, and free to
redistribute as-is without changes. Use of these programs is entirely at your
own risk. Please read
the [license](https://www.gnu.org/licenses/gpl.html) (long and boring) or
the [frequently asked questions](https://www.gnu.org/licenses/gpl-faq.html) (FAQ).
You must agree to the GPL if you change a program or its accessory files, or
use any part elsewhere. The conditions of the GPL are actually quite generous
and ensure that you are equally generous.

### Java Utilities

Small Java utility programs, also released under Apache License or GNU GPL. If
these aren't what you want, edit and recompile. See program comments and/or
command-line help for information.

- [Check Plain Trim](check-plain-trim-java.zip) (Java, ZIP, 229 KB):
CheckPlainTrim is a Java 1.4 application to check if files are in plain text
and do not have trailing spaces or tabs (white space) at the end of lines. How
clean are your source, text files, and XML documents? See also: Plain Text
(above), Trim File (below).

- [Create Dummy File](create-dummy-file-java.zip) (Java, ZIP, 159 KB):
CreateDummyFile is a Java 1.4 console application to create a file with a given
size, and to fill the file with a repeating pattern or pseudo-random data.

- [Echo Args](echo-args-java.zip) (Java, ZIP, 148 KB): EchoArgs is a trivial
Java 1.4 console application to print all command-line parameters on standard
error, when debugging scripts or what MS-DOS calls "batch" files.

- [File Search](file-search-java.zip) (Java, ZIP, 251 KB): FileSearch is a Java
1.4 application to find files that contain (or don't contain) a given string.
The string may be in plain text or it may be a Java regular expression.

- [Hex Byte Char](hex-byte-char-java.zip) (Java, ZIP, 267 KB): HexByteChar is a
Java 1.4 graphical (GUI) application to convert between binary data bytes and
text characters, in different character sets or encodings. Good for learning
about Java Swing. See also: [Blue Red White](blue-red-white-java.zip).

- [Largest Files](largest-files-java.zip) (Java, ZIP, 155 KB): LargestFiles is
a Java 1.4 console application to find the biggest files in a list of file or
folder names given on the command line. The code is a template for simple
applications that process files, folders, and subfolders. See also:
[Line Count](line-count-java.zip),
[Same File Size](same-file-size-java.zip),
[Show File Info](show-file-info-java.zip),
[Show File Size](show-file-size-java.zip),
[Show Folder Size](show-folder-size-java.zip).

- [Random Password](random-password-java.zip) (Java, ZIP, 211 KB):
RandomPassword is a Java 1.4 application to generate random passwords given an
alphabet (list of available characters), the length of each password (in
characters), and the number of passwords required.

- [Redate Photo File](redate-photo-file-java.zip) (Java, ZIP, 253 KB):
RedatePhotoFile is a Java 1.4 application to change file names or the "last
modified" date in the system file directory for JPEG photo files, using an
embedded date and time found within most JPEG files. The oldest date in a JPEG
file is usually the original image creation date. A newer date is often from
editing.

- [Show Date Time](show-date-time-java.zip) (Java, ZIP, 190 KB): ShowDateTime
is a Java 1.4 graphical (GUI) application to display the current date and/or
time in a format and location of the user's choice.

- [Sort FAT Folder](sort-fat-folder-java.zip) (Java, ZIP, 223 KB):
SortFatFolder is a Java 1.4 application to sort the directory entries for a
FAT16 or FAT32 file folder.

- [Trim File](trim-file-java.zip) (Java, ZIP, 175 KB): TrimFile is a Java 1.4
console application to remove trailing white space (blanks or tabs) from the
end of each line in a plain text file. Extra spaces commonly accumulate while
editing source programs in a graphical compiler (IDE). They aren't a problem,
but they do waste file space and occasionally affect the appearance of
programs. Many character sets (encodings) are supported, and you may convert
between character sets or newline styles. See also: Check Plain Trim (above).

### Link Farm

We farm only the best links! (Joke.) The following URLs encourage search
engines to index the project folders. ZIP downloads (above) are not indexed,
other than HTML anchor text and their file names.

- GitHub (project folders):
[Alphabet Web Icons](https://github.com/kwfenske/alphabet-web-icons),
[Beta Releases](https://github.com/kwfenske/beta-releases),
[Blue Red White](https://github.com/kwfenske/blue-red-white-java),
[Character Map](https://github.com/kwfenske/character-map-java),
[Check Plain Trim](https://github.com/kwfenske/check-plain-trim-java),
[Compare Folders](https://github.com/kwfenske/compare-folders-java),
[Create Dummy File](https://github.com/kwfenske/create-dummy-file-java),
[Delete Duplicate Files](https://github.com/kwfenske/delete-duplicate-files-java),
[Dots and Boxes Game](https://github.com/kwfenske/dots-and-boxes-game-java),
[Drive Speed](https://github.com/kwfenske/drive-speed-java),
[Dump File](https://github.com/kwfenske/dump-file-java),
[Echo Args](https://github.com/kwfenske/echo-args-java),
[Erase Disk](https://github.com/kwfenske/erase-disk-java),
[File Checksum](https://github.com/kwfenske/file-checksum-java),
[File Redate Rename](https://github.com/kwfenske/file-redate-rename-java),
[File Search](https://github.com/kwfenske/file-search-java),
[Find Duplicate Files](https://github.com/kwfenske/find-duplicate-files-java),
[Font Checksum](https://github.com/kwfenske/font-checksum-java),
[Font Names](https://github.com/kwfenske/font-names-java),
[Font Redate](https://github.com/kwfenske/font-redate-java),
[Font Rename](https://github.com/kwfenske/font-rename-java),
[GitHub.io](https://github.com/kwfenske/kwfenske.github.io),
[Hex Byte Char](https://github.com/kwfenske/hex-byte-char-java),
[Hex File Editor](https://github.com/kwfenske/hex-file-editor-java),
[Hex File Viewer](https://github.com/kwfenske/hex-file-viewer-java),
[Icon Editor](https://github.com/kwfenske/icon-editor-java),
[Largest Files](https://github.com/kwfenske/largest-files-java),
[Life Game](https://github.com/kwfenske/life-game-java),
[Line Count](https://github.com/kwfenske/line-count-java),
[Maze Fog Game](https://github.com/kwfenske/maze-fog-game-java),
[Metric SAE Sizes](https://github.com/kwfenske/metric-sae-sizes-java) (program),
[Plain Text](https://github.com/kwfenske/plain-text-java),
[Random Password](https://github.com/kwfenske/random-password-java),
[Redate Photo File](https://github.com/kwfenske/redate-photo-file-java),
[Reversi Game](https://github.com/kwfenske/reversi-game-java),
[Same File Size](https://github.com/kwfenske/same-file-size-java),
[Show Date Time](https://github.com/kwfenske/show-date-time-java),
[Show File Info](https://github.com/kwfenske/show-file-info-java),
[Show File Size](https://github.com/kwfenske/show-file-size-java),
[Show Folder Size](https://github.com/kwfenske/show-folder-size-java),
[Socket and Wrench Sizes](https://github.com/kwfenske/socket-wrench-sizes) (chart),
[Sort FAT Folder](https://github.com/kwfenske/sort-fat-folder-java),
[Tic-Tac-Toe Game](https://github.com/kwfenske/tic-tac-toe-game-java),
[Trim File](https://github.com/kwfenske/trim-file-java).

Most search engines scan known web pages about once a month, and new links
found there will appear in search results after two or three months. This page
was last revised on Wednesday, 17 September 2025. Frequently asked questions
([FAQ](https://kwfenske.github.io/faq.html)). Copyright &copy; 2011-2025 by
Keith Fenske. All rights reserved. Anything you post on the internet will get
stolen and used for something that you don't approve of.
