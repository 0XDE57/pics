# Basics of computing

Hexadecimal <a href="basics/hexadecimal.pdf"><img src="basics/hexadecimal.png" width="300" alt="hexadecimal"></a>


Colors <a href="basics/colors.pdf"><img src="basics/colors.png" width="300" alt="colors"></a>

Image <a href="basics/image.pdf"><img src="basics/image.png" width="300" alt="Image"></a>


- Portable PixMap (1988-)
  - [Examples](basics/examples)
  - <a href="basics/ppm1.pdf"><img src="basics/ppm1.png" width="300" alt="Portable PixMap 1/2"></a>
  - <a href="basics/ppm2.pdf"><img src="basics/ppm2.png" width="300" alt="Portable PixMap 2/2"></a>


---

# Charsets and encodings

- ASCII American Standard Code for Information Interchange (1967)
  - <a href="charsets/ASCIIprintable.png"><img src="charsets/ASCIIprintable.png" alt="printable ASCII" width=200></a>printable
  - <a href="charsets/ASCII.png"><img src="charsets/ASCII.png" alt="complete ASCII" width=200></a>complete

- Code Pages
  - <a href="charsets/ASCII-DOS.png"><img src="charsets/ASCII-DOS.png" alt="DOS characters in DOS" width=200></a>IBM PC cp437
  - <a href="charsets/codepages2.png"><img src="charsets/codepages2.png" alt="Icelandic, Nordic, Greek and Windows 1252" width=200></a>Icelandic cp861, Denmark/Norway cp865, Greek cp737 Windows-1252
  - <a href="charsets/codepages1.png"><img src="charsets/codepages1.png" alt="Central European and KOI8-R pages" width=200></a>Central European cp852, KOI8-R

- <a href="charsets/EBCDIC.png"><img src="charsets/EBCDIC.png" alt="Extended Binary Coded Decimal Interchange Code" width=200></a>
EBCDIC: Extended Binary Coded Decimal Interchange Code (1964)

- <a href="charsets/apl0293.png"><img src="charsets/apl0293.png" alt="A Programming Language - EBCDIC cp 293" width=200></a>
APL: A Programming Language - EBCDIC CodePage 293 (1966)

- <a href="charsets/PETSCII.png"><img src="charsets/PETSCII.png" alt="PETSCII" width=200></a>
PETSCII - PET Standard Code of Information Interchange / CBM ASCII (1977-)


---

# File formats

Containers:
- IFF: EA Interchange File Format (1985)
- RIFF: Resource Interchange File Format (1991)
- CFBF/CDFv2: Compound file binary format / Composite Document file v2 (DOCFILE / D0CF11E) (1997-2004)
- EBML: Extensible Binary Meta Language (2002)
- ISOBMFF: ISO Base Media File Format (2004?)


## Executables
- <a href="ELF.png"><img src="ELF.png" width="200"></a>ELF - Executable and linkable format

### Microsoft
- <a href="COM.png"><img src="COM.png" width="200"></a>Com (Dos [transient] commands)

- Exe - MZ executable [DOS] (1981-)
  - <a href="exe.png"><img src="exe.png" width="200"></a>
  - <a href="exestub.png"><img src="exestub.png" width="200"></a>EXE (PE Dos Stub)

- <a href="pifdos.png"><img src="pifdos.png" width="200"></a>Pif - Program information File (Windows 1-, 1985-)
- <a href="ne.png"><img src="ne.png" width="200"></a>NE - New Executable (Windows 1-2000, 1985-2000)
- <a href="le.png"><img src="le.png" width="200"></a>LE - Linear Executable (DOS, 1992)
- <a href="PE.png"><img src="PE.png" width="200"></a>PE - Portable executable (Windows NT 3.1-, 1993-)

### Apple
- <a href="rfrk.png"><img src="rfrk.png" width="200"></a>Rsrc - Resource fork (Mac System 1-, 1984)
- <a href="pef.png"><img src="pef.png" width="200"></a>Pef - Preferred Executable Format (Mac System 7-9 , 1991-1999)

- Macho - Mach Object (NeXTSTEP, MacOS, iOS)
  - <a href="MachO.png"><img src="MachO.png" width="200"></a>(Little 32b)
  - <a href="macho64.png"><img src="macho64.png" width="200"></a>(Little 64b)
  - <a href="machoppc.png"><img src="machoppc.png" width="200"></a>(Big 32b PowerPC)
  - <a href="machoppc64.png"><img src="machoppc64.png" width="200"></a>(Big 64b PowerPC)

- <a href="fatmacho.png"><img src="fatmacho.png" width="200"></a>Fat/Universal Mach-o

### Others
- <a href="CLASS.png"><img src="CLASS.png" width="200"></a>Class - Java / JVM (1994)
- <a href="DalvikEXecutable.pdf"><img src="DEX.png" width="200"></a>DEX - Dalvik Executable [Android] (2008?)
- <a href="pyc.png"><img src="pyc.png" width="200"></a>PYC - Compiled python (1998-)
- <a href="SWF.png"><img src="SWF.png" width="200"></a>Swf - ShockWave Flash / Small web file (1995?)

- Dol - Nintendo Dolphin (Gamecube, Wii, 2001-2017)
  - <a href="dol.png"><img src="dol.png" width="200"></a>executable
  - <a href="dolhdr.png"><img src="dolhdr.png" width="200"></a>complete header
- <a href="nro.png"><img src="nro.png" width="200"></a>NRO - NX (Nintendo Switch) Relocatable Object

- <a href="off.png"><img src="off.png" width="200"></a>OFF - OS/360 Object File format [EBCDIC] (1966?)
- <a href="tos.png"><img src="tos.png" width="200"></a>Tos - GEMDOS Program format [Atari ST] (1985)
- <a href="hunk.png"><img src="hunk.png" width="200"></a>Hunk - Amiga Hunk [Commodore AmigaOS] (1985)

- <a href="te.png"><img src="te.png" width="200"></a>TE - Terse Executable [UEFI] (2017?)
- <a href="wasm.png"><img src="wasm.png" width="200"></a>Wasm - WebAssembly (2017)

## Images
- <a href="bpg.png"><img src="bpg.png" width="200"></a>Bpg - Better/Bellard Portable Graphics (2014)
- <a href="PNG.png"><img src="PNG.png" width="200"></a>Png - Portable Network graphics (1996)
  - <a href="pngplus.png"><img src="pngplus.png" width="200"></a>Png Plus: a PNG with OLE chunks, by Microsoft Picture It!
- <a href="JPG.png"><img src="JPG.png" width="200"></a>Jpeg (JFIF) - Joint Photographic Experts Group - File Interchange Format (1992)
- <a href="dicom.png"><img src="dicom.png" width="200"></a>Dicom - Digital Imaging and Communications in Medicine (1985)
- <a href="psd.png"><img src="psd.png" width="200"></a>Psd - PhotoShop Document (1990)

- <a href="XBM.png"><img src="XBM.png" width="200"></a>Xbm - X BitMap (X11 1989)

- Netpbm (1988)
  - <a href="PGM.png"><img src="PGM.png" width="200"></a>Pgm - Portable Graymap
  - <a href="PPM.png"><img src="PPM.png" width="200"></a>Ppm - Portable Pixmap

- <a href="lbm.png"><img src="lbm.png" width="200"></a>[I]Lbm - Interleaved Bitmap [IFF] (1985)

- BMP - Bitmap [Windows 2 (1987)]
  - <a href="bmp1.png"><img src="bmp1.png" width="200"></a>v1
  - <a href="bmp3.png"><img src="bmp3.png" width="200"></a>v3 (1991)
  - <a href="bmp5.png"><img src="bmp5.png" width="200"></a>v5 (1998)

Gif - Graphics Interchange Format (1987)
- <a href="gif87.png"><img src="gif87.png" width="200"></a>
- <a href="gif89.png"><img src="gif89.png" width="200"></a>v89, with a comment

- TIFF - Tag Image File Format (1986)
  - <a href="TIFF_LE.png"><img src="TIFF_LE.png" width="200"></a>little endian
  - <a href="TIFF_BE.png"><img src="TIFF_BE.png" width="200"></a>big endian

- PCX - Zsoft Picture exchange [DOS] (1982)
  - <a href="pcx16.png"><img src="pcx16.png" width="200"></a>16 colors
  - <a href="pcx256.png"><img src="pcx256.png" width="200"></a>256 colors

- <a href="tga.png"><img src="tga.png" width="200"></a>TGA/TARGA - TrueVision [Advanced Raster] Graphics Adapter (1984)

- ICO - Windows icon (1985)
  - <a href="ico_bmp.png"><img src="ico_bmp.png" width="200"></a> w/ BMP (1995?)
  - <a href="ico_png.png"><img src="ico_png.png" width="200"></a> w/ PNG (2006)

- <a href="pifimg.png"><img src="pifimg.png" width="200"></a>Pif - Portable Image Format (2022)
- <a href="qoi.png"><img src="qoi.png" width="200"></a>Qoi - Quite Ok Image (2021)
- <a href="1ba.png"><img src="1ba.png" width="200"></a>1ba - 1-bit animation (2023)


## Videos
- <a href="mp4.png"><img src="mp4.png" width="200"></a>Mp4 [ISOBMFF] (2001)
- <a href="mkv.png"><img src="mkv.png" width="200"></a>Mkv - Matroska video [EBML] (2002)

- Y4M - Yuv4mpeg (2001)
  - <a href="y4m_mono.png"><img src="y4m_mono.png" width="200"></a>(mono)
  - <a href="y4m_yuv.png"><img src="y4m_yuv.png" width="200"></a>(yuv)


## Archives

- [Zlib/Deflate/Zip/GZIP?](https://speakerdeck.com/ange/gzip-equals-zip-equals-zlib-equals-deflate)
- <a href="GZip.png"><img src="GZip.png" width="200"></a>Gzip - GNU zip (1992)

- <a href="ar.png"><img src="ar.png" width="200"></a>Ar - Archive (1971)
- <a href="TAR.png"><img src="TAR.png" width="200"></a>Tar - Tape archive (1979)

- Copy [files] In & out [of archives] (1977)
  - <a href="cpio_bin.png"><img src="cpio_bin.png" width="200"></a>binary
  - <a href="cpio_ascii.png"><img src="cpio_ascii.png" width="200"></a>ASCII

- <a href="ZIP.png"><img src="ZIP.png" width="200"></a>Zip - PkZip (1989)
  - <a href="crx.png"><img src="crx.png" width="200"></a>Crx - Chrome extension (2017)

- Lzma - Lempel-Ziv-Markov chain algorithm (1998)
  - <a href="lzma.png"><img src="lzma.png" width="300"></a>
  - <a href="lzma_eos.png"><img src="lzma_eos.png" width="300"></a>with End of Stream marker

- <a href="7zip.png"><img src="7zip.png" width="200"></a>7zip (1999)
- <a href="xar.png"><img src="xar.png" width="200"></a>Xar (2007)
- <a href="xz.png"><img src="xz.png" width="200"></a>Xz (2009)

- <a href="mscompress.png"><img src="mscompress.png" width="200"></a>Microsoft Compress (1990)
- <a href="cab.png"><img src="cab.png" width="200"></a>Cab - Microsoft Cabinet File (Mscf) (1995?)
- <a href="rpm.png"><img src="rpm.png" width="200"></a>Rpm - Redhat/RPM Package Manager (1997)

- Rar - Roschal Archive (1993)
  - <a href="rar14.png"><img src="rar14.png" width="200"></a>v1.4
  - <a href="rar4.png"><img src="rar4.png" width="200"></a>v4 (1996)
  - <a href="rar5.png"><img src="rar5.png" width="200"></a>v5 (2013)

- <a href="arj.png"><img src="arj.png" width="200"></a>Arj - Archived by Robert Jung (1991?)
- <a href="BZ2.png"><img src="BZ2.png" width="200"></a>bz2 - Bzip2 (1996)

Wad - Where's all the data? (1993)
- <a href="wad_structure.png"><img src="wad_structure.png" width="300"></a>(structure)
- <a href="wad.png"><img src="wad.png" width="300"></a>(in Doom)


Zstd - Zstandard (2015)
- <a href="zstd.png"><img src="zstd.png" width="300"></a>
- <a href="zstd_skip.png"><img src="zstd_skip.png" width="300"></a>w/ Skippable frame

- <a href="lz4.png"><img src="lz4.png" width="300"></a>LZ4 (2011)


## Documents
- <a href="eps.png"><img src="eps.png" width="200"></a>Eps - Encapsulated PostScript (1987)
- <a href="PDF.png"><img src="PDF.png" width="200"></a>Pdf - Portable document format (1992)
- <a href="rtf.png"><img src="rtf.png" width="200"></a>RTF - Rich text format (1987)

- Microsoft Office
  - <a href="cfb.png"><img src="cfb.png" width="200"></a>Msi - Microsoft Installer [CFB]
  - <a href="wordml.png"><img src="wordml.png" width="200"></a>Docm - WordML/WordProcessingML (Microsoft Office XML format) - XML (2002)
  - <a href="activemime.png"><img src="activemime.png" width="200"></a>ActiveMime - MSO XML Bindata
  - <a href="docx.png"><img src="docx.png" width="200"></a>Docx - Doc XML (Office Open XML) - ZIP+XMLs (2006)

Multiplan - Excel:
- <a href="sylk.png"><img src="sylk.png" width="200"></a>Sylk - Symbolic link - Multiplan 1 (1984-), Excel 1 (1986-)

- Biff - Binary Interchange File Format
  - <a href="biff2.png"><img src="biff2.png" width="200"></a>v2: v2, 1989 (raw)
  - <a href="biff8.png"><img src="biff8.png" width="200"></a>v8: 97-2003, 1998-2004 [CFB]

- <a href="winhelp.png"><img src="winhelp.png" width="200"></a>Hlp - WinHelp (1990)
- <a href="chm.png"><img src="chm.png" width="200"></a>Chm - Compiled HTML help - Info-Tech Storage Format (1997)
- <a href="one.png"><img src="one.png" width="200"></a>One - One Note (2014-)

- Wmf - Windows Metafile Format (1992)
  - <a href="wmf2.png"><img src="wmf2.png" width="200"></a>
  - <a href="wmf.png"><img src="wmf.png" width="200"></a> with Placeable header

- <a href="emf.png"><img src="emf.png" width="200"></a>Emf - Enhanced Metafile Format (1993)

## Sound
- <a href="8svx.png"><img src="8svx.png" width="200"></a>8svx - 8-bit sample voice [Amiga][Iff] (1985)

- AIFF - Audio interchange file format [Apple][Iff] (1988)
  - <a href="aiff.png"><img src="aiff.png" width="200"></a>
  - <a href="aiffc.png"><img src="aiffc.png" width="200"></a>AIFC / AIFF-C - Compressed (1991)

- <a href="WAV.png"><img src="WAV.png" width="200"></a>Wav - Waveform [Riff] (1991)
- <a href="rmi.png"><img src="rmi.png" width="200"></a>Rmi - Riff Midi [Riff]

- <a href="midi.png"><img src="midi.png" width="200"></a>Midi - Musical Instrument Digital Interface

## Metadata
- <a href="psd_iptc.png"><img src="psd_iptc.png" width="200"></a>IPTC IIM / International Press Telecommunications Council - Information Interchange Model (1991)
- <a href="tiff_exif.png"><img src="tiff_exif.png" width="200"></a>Exif - Exchangeable Image File Format (1995)
- <a href="xmp.png"><img src="xmp.png" width="200"></a>XMP - Extensible Metadata Platform (2001)

## Serialization
- <a href="asn1.png"><img src="asn1.png" width="200"></a>ASN.1 - Abstract Syntax Notation One (1984)
- <a href="bplist.png"><img src="bplist.png" width="200"></a>Bplist - Binary property list (2000)
- <a href="protobuf.png"><img src="protobuf.png" width="200"></a>Protobuf - Protocol buffers (2001)

## Vector Fonts
- <a href="otf.png"><img src="otf.png" width="200"></a>OTF - OpenType Font Format (1996)
- <a href="ttf.png"><img src="ttf.png" width="200"></a>TTF - TrueType Font (1991)
  - <a href="ttf-loca1.png"><img src="ttf-loca1.png" width="200"></a>with a Location Table v1
  - <a href="ttf-loca2.png"><img src="ttf-loca2.png" width="200"></a>with a Location Table v2
- <a href="woff.png"><img src="woff.png" width="200"></a>Woff - Web Open Font Format (2012)
  - <a href="woff2.png"><img src="woff2.png" width="200"></a>Woff2 - Web Open Font Format 2.0 (2018)

## Others
- <a href="mbr.png"><img src="mbr.png" width="200"></a>Mbr+DPT - Master Boot Record with Disk Partitions Table (1983)

- <a href="lnk.png"><img src="lnk.png" width="200"></a>Lnk - Shell link [Windows] (1995?)
- <a href="cdix.png"><img src="cdix.png" width="200"></a>Cdix - ClangD Index [Riff] (2018)

- <a href="hex.png"><img src="hex.png" width="200"></a> Hex records - Intel[lec] Hexadecimal object (1973)
- <a href="uf2.png"><img src="uf2.png" width="200"></a> Uf2 - USB Flashing format (2016)


## Opcodes
- <a href="x64.png"><img src="x64.png" width="200"></a>
- <a href="x86.png"><img src="x86.png" width="200"></a>

## Weird files

A polymock header: a file with many mock formats signatures.</br>
<a href="polymock.png"><img src="polymock.png" width="200"></a>

Universal Doom by Robert Xiao: functional DOS (Dos4/GW) and Portable Executable.</br>
<a href="unidoom.png"><img src="unidoom.png" width="200"></a>

A ZIP/PNG polyglot (sharing the deflate data) by Gynvael Coldwind.</br>
<a href="zippng.png"><img src="zippng.png" width="200"></a>

## 101

Dissection with more descriptions, and explanations (my initial style of binary posters).

source Inkscape SVGs and PoC with their sources are included

[PE 101](pe101/README.md)

<a href="pe101/README.md">
<img src="pe101/pe101l.png" width="300">
<img src="pe101/pe101-64.png" width="300"></a>

### Others

<a href="elf101/elf101.pdf"><img src="ELF101.png" width="300"></a>
<a href="zip101/zip101.pdf"><img src="ZIP101.png" width="300"></a>
<a href="macho101/macho101.pdf"><img src="Mach-O101.png" width="300"></a>
<a href="class101/class101.pdf"><img src="CLASS101.png" width="300"></a>
<a href="pdf101/pdf101.pdf"><img src="PDF101.png" width="300"></a>
<a href="com101/com101.pdf"><img src="COM101.png" width="300"></a>
<a href="wav101/wav101.pdf"><img src="WAV101.png" width="300"></a>

## Structures

A layout of the various format's structures

<a href="pe102/pe102.pdf"><img src="PE102.png" width="300"></a>

# Opcodes' tables

Available in compact

<a href="opcodes_tables_complete.pdf">
	<img src="DVM.png" width="300">
	<img src="JVM.png" width="300">
	<img src="DotNet.png" width="300">
</a>

or 'with descriptions' formats

<a href="opcodes_tables_compact.pdf">
	<img src="DVMFull.jpg" width="400">
	<img src="JVMFull.png" width="400">
	<img src="DotNetFull.jpg" width="400">
</a>

---
## Cryptography

Jneavat! N qnatrebhf pelcgbtencuvp bowrpg vf urnqvat lbhe jnl....

<a href="CryptoModes.png"><img src="CryptoModes.png" width="200"></a>

<!-- pandoc -s -f gfm -t html pics.md -o pics.html -->
