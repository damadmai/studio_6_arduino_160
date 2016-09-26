# Atmel Studio 6.2 solution for AVR projects using Arduino Library 1.6.x

## Prequesites
* Download and install [Arduino IDE 1.6.x](http://arduino.cc/en/Main/Software) into suggested path.
* Add the template [`studio_6_arduino_160_template`](https://github.com/damadmai/studio_6_arduino_160_template)
as described.

## Instructions

1. Fork this repository and clone it to desktop.
* Rename [`studio_arduino.atsln`](./studio_arduino.atsln) to `<your-repository>.atsln`.
* Open the Solution `<your-repository>.atsln` with 
  [Atmel Studio 6.2 Build 1563](https://www.mikrocontroller.net/articles/Atmel_Studio).
* Click `File` &rarr;	`New` &rarr; `Project` in menu bar.
* Select `studio_arduino`, name it `<your-repository>` and select `Solution` &rarr; `Add` then `OK`.
* Right click `<your-repository>` in Solution Explorer and then `Set as StartUp Project`.
* Collapse `arduinocore` in Solution Explorer as you won't need it.
* Rename `studio_arduino.cpp` to `<your-repository>.cpp` in Solution Explorer.
* Build your solution by pressing F7 or using the menu bar.
* Add your code and repeat the step above.
* Do a commit and publish your project. :octocat:

## Links

German Discussion Forum Thread:
https://www.mikrocontroller.net/topic/344073

[http://www.engblaze.com/tutorial-using-atmel-studio-6-with-arduino-projects/] (https://web.archive.org/web/20150812213502/http://www.engblaze.com/tutorial-using-atmel-studio-6-with-arduino-projects/)

https://code-clarity.blogspot.co.at/2013/01/atmel-studio-for-arduino-guys-part1.html

## License

[MIT](./LICENSE)
