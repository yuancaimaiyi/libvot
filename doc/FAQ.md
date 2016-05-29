## Frequently Asked Questions

#### Why OpenCV is imported as a build option in 0.2 release?

The goal of *libvot* is to provide cutting-edged algorithms in image retrieval at the production level. 
OpenCV provides a set of useful utility functions that can free vision developers from the nasty details of low-level programming, thus accelerating the developement for advanced algorithms. Though it would be a better choice for software performance to manually import these low-level libraries, such as *ffmpeg*, *libjpeg*, *libpng*, etc. Anyway, currently we provide OpenCV as a building option. You can disable it by configuring cmake options.