This is a simple macOS Universal binary of the classic Amiga compression/decompression tool `LhA`, which is very useful when building [AmigaVision](https://amiga.vision).

While there are multiple tools that will *unpack* LhA archives available on macOS (and Windows), there is a distinct lack of tools that can *create* archives in this format, as well as perform utility functions on the archive — like listing the contents without unpacking it. That's why this exists.

It's a pain to compile these things from source — and no obvious macOS Universal binary that runs on Apple Silicon and Intel was available — we decided to publish one. It may not work on slightly older OS versions, currently tested on macOS 15 and 26.

This is just a straight macOS Universal binary compile of https://github.com/jca02266/lha, so please see that repository for copyrights, license, etc.
