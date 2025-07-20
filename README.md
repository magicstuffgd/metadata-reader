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

Can extract basic metadata from the files CANNOT open files like .zip does
