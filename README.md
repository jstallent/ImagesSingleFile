# ImagesSingleFile
Single file solution for full-screen images with captions

This EPUB 3 file offers a not-too-complex solution for keeping a large image and a caption on the same screen.

Essentially, all major reading systems support either using percentages on image tags to scale the image to less than the height of the screen, or using viewport sizes (vh) to do the same thing. This solution allows you to effectively apply both to any large image, giving you the ability to have large images with captions that stay on the same screen. 

A few assumptions: 
1. The image must start at the top of a page/screen. If necessary, place it at the top of an HTML file.
2. The viewport height units only work on newer devices. It is applied using a CSS 3 pseudo-class, :only-of-type. The assumption is that if a reading system supports the pseudo-class it will also support the viewport unit. This has proven to be true in all systems tested.

It has been tested and works in all of the following reading systems:
- ADE 3.0.86137 on PC running Windows 7
- ADE 4.0.3.110333 on PC running Windows 7
- Bluefire Reader 2.4 on iPad Air running iOS 8.1.3 (12B466)
- Bluefire Reader 2.0.3 on Nexus 7 running Android 5.0.1
- Google Play 2.2.12859 on iPad Air running iOS 8.1.3 (12B466)
- Google Play 3.3.15 on Nexus 7 running Android 5.0.1
- iBooks 3.1.3 (1929) on iPad 1 running iOS 5.1.1 (9B206)
- iBooks 4.1.1 (2618) on iPad Air running iOS 8.1.3 (12B466)
- Kindle Paperwhite 1st Gen 5.4.4.2
- Kindle Keyboard (Kindle 3) 3.4.1
- Kindle Fire HDX running Fire OS 4.5.3
- Kindle iOS 4.7.1 on iPad Air running iOS 8.1.3 (12B466)
- Kindle Android 4.10.0 on Nexus 7 running Android 5.0.1
- Kobo iOS 7.5 on iPad Air running iOS 8.1.3 (12B466)
- Kobo Touch 3.11.0
- Kobo Android 6.1.13023 on Nexus 7 running Android 5.0.1

Screenshots of some devices are included.