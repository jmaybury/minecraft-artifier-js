# minecraft-artifier-js

This is an unauthorized, unmaintained, and somewhat incomplete fork of [Explodey54/minecraft-artifier-js](https://github.com/Explodey54/minecraft-artifier-js), a JavaScript/Node.js Web Converter from image to Minecraft blocks. It adds support for blocks from newer versions of Minecraft (up to 1.16).

If you are a developer toying with making your own fork for the same purpose and wondering if anyone else has made a start at it you can build off, well, look no further.

If you just want to build some Minecraft pixel art using 1.16 blocks, please carefully read the caveats below to see if this project might be useful to you.

### There is no public web interface

You'll need to clone the repository, build the project with Node.js / NPM, and run it locally. If you don't know how to do all that, probably best to stick with the [original converter](https://minecraftart.netlify.com/). It only uses blocks from version <=1.12, but honestly, it doesn't really make that much difference.

### .schematic files are not supported

At least, I assume not. There's a note in the original project about the format changing with version 1.13, or something. I don't know anything about that. This tool can, however, create command block output that works with 1.16.

### This fork is not being actively developed, maintained, or supported

I've pretty much done what I set out to do with this thing, and I don't anticipate putting much more time or effort into it. That said, if you actually use it and find any issues, feel free to [report](https://github.com/jmaybury/minecraft-artifier-js/issues) them; if nothing else it'll document it for anyone else who stumbles in here.
