# msinttypes
Automatically exported from code.google.com/p/msinttypes

# Overview
This project fills the absence of stdint.h and inttypes.h in Microsoft Visual Studio. This files were standartized by ISO/IEC as a part of C99 standard library. If you want to compile or use C99 compliant project with Microsoft Visual Studio, you will likely find that you're missing these headers. Note though, that just adding these header does not make Visual Studio compiler fully C99 compliant.

FFMpeg is a good example of library that requires inttypes.h even if you just want to link your program with it.

More portable version of stdint.h can be find here but it does not implement inttypes.h features, such as printf and scanf format specifiers.
