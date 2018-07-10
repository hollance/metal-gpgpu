# Metal GPGPU

This is a collection of notes on how to use Apple's **Metal** API for **compute** tasks. 🤘

Metal is a low-level graphics programming API for iOS and macOS but it can also be used for general-purpose compute on these devices. Unfortunately, Metal is not extensively documented. And the existing docs assume that you already know other graphics or compute APIs such as OpenGL, OpenCL, or CUDA. 

Hopefully these notes will help you understand Metal a little better. Mostly I collected this information because my poor brain can't possibly remember all this stuff, and I thought it would be useful to turn it into a community thing.

> **NOTE:** This is a work-in-progress. Use these notes at your own risk -- there may be mistakes. Pull requests for corrections and enhancements are welcome!

## Table of contents

(coming soon)

## See also

There is a lot of useful documentation inside the Metal header files. You can find these at the following locations:

1. First, go to `/Applications/Xcode.app/Contents/Developer/Platforms/`
2. Pick your platform: `iPhoneOS.platform/`, `AppleTVOS.platform/`, or `MacOSX.platform/`
3. For the Metal standard library, go to: `usr/lib/clang/<version>/include/metal`
4. For Metal.framework, MetalKit.framework, MetalPerformanceShaders.framework, go to:   
`Developer/SDKs/<your SDK>/System/Library/Frameworks`

Web pages from Apple:

- [developer.apple.com/metal](https://developer.apple.com/metal/) -- links to the official documentation, WWDC videos, and sample code
- [Metal Shading Language Specification](https://developer.apple.com/metal/Metal-Shading-Language-Specification.pdf)
- [Apple Developer Forums: Metal](https://forums.developer.apple.com/community/graphics-and-games/metal)

Other useful websites about using Metal (mostly graphics, not so much compute):

- [Metal questions on Stack Overflow](https://stackoverflow.com/questions/tagged/metal)
- [Metal tutorials at raywenderlich.com](https://www.raywenderlich.com/tag/metal)
- [metalkit.org](http://metalkit.org)
- [Metal by Example](http://metalbyexample.com)

Websites and courses about GPGPU programming:

- [Udacity cs344, Intro to Parallel Programming](https://udacity.com/course/intro-to-parallel-programming--cs344)

## Change log

#### 10 July 2018

First version.

## License

The content is licensed under the Creative Commons [Attribution-NonCommercial-ShareAlike 4.0](http://creativecommons.org/licenses/by-nc-sa/4.0/) license.
