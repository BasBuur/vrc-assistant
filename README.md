# VRC Assistant BETA

VRC Assistant is a helper tool for VRC. Upon selecting an aircraft on the scope, VRC Assistant loads and shows you a variety of information regarding the plane.

*This application is currently in BETA. Please expect and report any issues you may experience*

Currently the following information is displayed:

* Callsign
* Airline phonetic name (if available)
* Aircraft info (type, engine configuration) (if available)
* Direction of flight (calculated based on the origin & destination airport)
* Color-coded flightplan route (hovering over VOR's shows the full VOR name)
* Origin & desination airports (ICAO, city & full airport name)
* Preferred routes for the filed origin & destination airport)

# Installation
* Download the installer from the releases section on this page
* Run the installer. The application will install & open automatically

# Using
* Start VRC first **Important!**
* Start the application (if not already started)
* The application will check for updates and download them if available
* You'll now get asked to select an aircraft on the scope in VRC and to copy and paste **all** information shown at the bottom of the *Departures & arrivals* screen within VRC. Click [here](https://imgur.com/a/gCKUQ8l) for a screenshot of what text to copy.
* You will probably have to do this twice or possibly 3 times. **Make sure to copy all lines**.
* When the scan is complete the main window will open and you're ready to go
* To move the window, click & drag the move icon on the top-right of the window (second icon from the right)
* To reset the memory scanner, click the reset icon on the top-right of the window (third icon from the right)

NOTES:
* Currently the preferred routes are loaded from the BVA (ZBW) IDS system. Therefore it shows all FAA routes and the BVA ARTCC routes. If demand is high enough I'd be happy to integrate other ARTCC API's to show those as well
* VRC does not offer an official way to get the information that this application needs. Therefore this application basically combs through the VRC memory space to find the information it needs. This ain't a perfect way of doing things but currently the only way and works quite well.
* For unknown reasons VRC or the Windows kernel sometimes decides it'd be fun to move around the memory that's used by this tool. If this happens the tool tries to recover automatically and find the new memory location. If it's unable to do so you'll notice that selecting a new aircraft no longer loads the new data. If this happens try clicking on the arrow between the 2 airport input boxes. Then, select another aircraft. Still not working? Click the arrow again and select another aircraft. Still no good? Click the reset icon on the top-right of the window to restart the memory scanner.
