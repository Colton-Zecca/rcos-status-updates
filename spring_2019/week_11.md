## Last Week's Accomplishments

This week, I found out that XCode only accepts specifically-sized PNG files for images. There are 3 
different kinds: 1x, 2x, and 3x. The 2x version is double the size of the 1x version, and is used for
Retina displays of relatively older iOS devices. The 3x version is used for Apple's latest phones
with the Retina Display HD - like that of the iPhone X. As a result, for the 4 main tab icons, 3 
different images needed to be made. 

After finding out the way XCode's image compatibility works, I converted all of the SVGs into PNGs 
and resized them into their 3 respective sizes for XCode using Photoshop. Then, I implemented
the images into each tab view controller in the storyboard appropriately with proper names.

PNG Files Made:

![PNG Files Made](https://snag.gy/VSz1y0.jpg)


The Imported Icons in XCode:

![Icons in XCode](https://snag.gy/uYy6mH.jpg)


Screenshot of the iOS App After Implementing Images:

![App Screenshot](https://snag.gy/FoGwCZ.jpg)


## This Week's Plan

Next week, I plan to work on implementation of how to pull data for students from LATE using either some
workaround with CAS or another API method.

## Anything Blocking?

Potentially - the way to access students' data through CAS/other.

## Notes

As previously, I will need to take into consideration giving the credit for giving using Font Awesome's images. This will
likely be done in the Terms of Service or something of the like.
