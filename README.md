# Universal Metadata Reader
<p align="center">
  <img src="https://cdn.discordapp.com/attachments/1396563817235742820/1396563830754119690/image.png?ex=687e8aec&is=687d396c&hm=0a10ade649df0a440feb47e0f11ceef04548108e2f3ab63b54f1a09e31dbe13b&" alt="File Metadata Reader" width="800"/>
</p>
The application handles a wide variety of file types including:

Images (JPEG, PNG, GIF, TIFF, BMP)
Videos (MP4, AVI, MOV, MKV)
Audio (MP3, FLAC, WAV, OGG)
Documents (PDF, DOCX, XLSX)
Archives (ZIP, RAR, 7Z)
Gaming files (PKG, ISO, ROM)
Executables (EXE, ELF, DMG)

The code actually parses file structures to extract genuine metadata:

JPEG: Reads SOF markers for dimensions, analyzes EXIF data structure
PNG: Parses IHDR chunks for image properties, lists all chunks
MP4: Reads atom structure, extracts brand/version from ftyp atom
ELF: Parses ELF headers for architecture, entry points, OS ABI
ZIP: Enumerates archive entries with compression info

Modern, responsive design with:

Drag-and-drop functionality
Progress indicators
Export capabilities (JSON, CSV, XML)
Animated visual effects

Can extract basic metadata from the files <b> CANNOT </b> open files like .zip does
