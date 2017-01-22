# Automation Director

## This SmartApp will allow you to choose any number of triggers:
* Button Controllers(You choose the actions per button press/hold),
* Acceleration sensors,
* Contact sensors,
* Motion sensors,
* Tamper sensors,
* Shock sensors,
* Sleep sensors,
* Sound sensors,
* Touch sensors,
* Step sensors,
* Beacon sensors,
* Presence sensors,
* CO2 measurement levels,
* CO detectors,
* Smoke detectors,
* Sound pressure levels,
* Water sensors,
* Energy levels,
* Power levels,
* Voltage levels,
* Battery levels,
* Switch state changes,
* Illumination levels,
* Door controller state changes,
* Temperature levels,
* Humidity levels,
* UV levels,
* ph levels,
* Valve state changes,
* Shade state changes,
  
## To change any number of the following:
* Set alarm modes,
* Activate sirens(siren/strobe/both/off),
* Send custom Push notification messages,
* Send custom SMS notification messages,
* Send a specific sound to a doorbell,
* Control Garage doors(open/close),
* Control Locks(lock/unlock),
* Control Door openers(open/close),
* Take Still Images(and photo bursts),
* Control Bulbs(on/off/toggle/dim/brighter/favorite/full/color<Bulbs only>),
* Control Dimmers(on/off/toggle/dim/brighter/favorite/full),
* Control Switches(on/off/toggle),
* Control Outlets(on/off),
* Control Relays(on/off),
* Control Valves(open/close),
* Control Shades(open/close),
* Control Speakers(play/pause/toggle/mute/unmute/next/previous/volume up/volume down),
  
## Known issues:
* After you setup an instance, if you want to change the custom Push or SMS notifications you should deselect them from the "Assign the actions to the triggers" page and save then go back in to change them and re-assign them otherwise actions that are no longer valid will not show up in the menus and will not do anything but if you watch the live logging you will see it still tries processing them.

## Version History:
* 1.3 Added the ability to disable the instance of the SmartApp
* 1.2 Added additional requirement options
* 1.1 The smartapp now only asks for the numberofbuttons and if it supports holdableButton if the information isn't provided by the DTH
* 1.0 Initial release
