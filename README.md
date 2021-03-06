# VRC Assistant BETA

<a href="https://github.com/BasBuur/vrc-assistant/releases/download/latest/VRC.Assistant.Setup.0.4.0.exe"><img src="https://user-images.githubusercontent.com/7340024/157321916-c2ecd6b9-b9d0-422f-90da-bfd5bb6bc992.png" width="200"/></a>

<img src="https://user-images.githubusercontent.com/7340024/156903274-0d016fd1-f71a-464a-9dc4-079dcddf8113.png" width="350" />

***This application is currently in BETA. Please report any issues you may experience***

VRC Assistant is a helper tool for VRC. Upon selecting an aircraft on the VRC scope, VRC Assistant automatically loads and shows you a variety of information regarding the aircraft.

Currently the following information is displayed:

* Callsign
* Airline phonetic name (if available)
* Aircraft info (type, engine configuration) (if available)
* Direction of flight (calculated based on the origin & destination airport)
* Color-coded flightplan route (*hovering over VOR's shows the full VOR name*)
* Origin & desination airports (ICAO, city & full airport name)
* Preferred routes (FAA + ZBW/BVA) for the filed origin & destination airport. The copy icon behind each route copies the route to your clipboard

## Installation
* Download the installer from the releases section on this page (right-hand side under 'Releases' - download the setup .exe)
* Run the installer. The application will install & open automatically

## Using (it's **really** simple!)
* Start the application (if not already started - after installation you can find it on your desktop & start menu as 'VRC Assistant')
* The application will check for updates and download & install any if available
* Start VRC if you haven't already
* Select an aircraft on the VRC scope. All information should now load in the assistant.
* **Note**: You can also click on an aircraft's data block text to load the information. This will not select the aircraft within VRC but does allow you to peek at the information in the assistant!
* Make sure to check out the Settings screen (cog button on the top-right) to customize your experience

## Notes
* Please report any issues or feedback. You can create an issue here on you can contact me on Discord: BasilBurrito#4468
* Currently the preferred routes are loaded from the BVA (ZBW) IDS system. Therefore it shows all FAA routes and the BVA ARTCC routes. If demand is high enough I'd be happy to integrate other ARTCC API's to show those as well. Please contact me and let me know who I should contact to get the information I need

## Support / feedback
Please [contact me on Discord](https://discordapp.com/users/290912506703118347) for support or feedback

## Source Code?
Unfortunately I'm unable to share the source code of VRC Assistant. This has to do with a proprietary file format and compiler that I used which I'm not allowed to share. Initially I started this project just for myself, hence I didn't see this as a problem. It's an Electron app so the (compiled) JS code is available in the ASAR archive in case you want to make sure it doesn't do anything fishy. If you do not feel comfortable running an executable on your PC (which is fair enough!) please don't.
