# OpenCV for iOS

Just Compilled OpenCV framework for iOS. 

**Update**: Pod now uses framework downloaded from [here](http://sourceforge.net/projects/opencvlibrary/files/opencv-ios/2.4.7/opencv2.framework.zip/download), which supports 64 and 32-bit. Compiling for 64-bit didn't work, ran into same problems mentioned [here](http://stackoverflow.com/questions/18976893/how-to-compile-opencv-for-ios7-arm64). 

Have different versions (see tags)


## Usage:

Use `.mm` flies instead of `.m` (Objective-C++)

Add import:

	#import <opencv2/opencv.hpp>


### Installation with Cocoapods 

Just add line in your Podfile: 

	pod 'OpenCV'

### Instalation Manually 

Download and add `opencv2.framework` to your project

Also add following frameworks to your project:

- Accelerate
- AssetsLibrary
- AVFoundation
- CoreGraphics
- CoreImage
- CoreMedia
- CoreVideo
- QuartzCore
- UIKit
- Foundation

Also add following libs :

- libc++.dylib


## OpenCV README

OpenCV: open source computer vision library

Homepage:		http://opencv.org

Online docs:	http://docs.opencv.org

Q&A forum:		http://answers.opencv.org

Dev zone:		http://code.opencv.org

Download:		http://sourceforge.net/projects/opencvlibrary/files/opencv-ios/


