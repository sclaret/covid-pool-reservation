# Install Chrome Plugin 

[UI.Vision RPA](https://github.com/A9T9/RPA) from [Chrome Webstore](https://chrome.google.com/webstore/detail/uivision-rpa/gcbalfbdmfieckjlnblleoemohcganoc)


# Import Macros

Create folder reservepoolslot

Import waitloop.json, pool.json
 
Substitute CodeUtilisateur, motPasse


# Settings

Replay -> TIMEOUT_WAIT 2


# Error level

echo & status


# Execute

Verify last run

Clear logs

Clear screenshots

Play macro waitloop

Turn on workstation sleep disabler


# TODO

- Rolling switch to new timeslots (map?)
- Externalize auth credentials
- Trigger from external scheduler
- Move to dedicated box


# IDEAS

- Push confirmation to widget 
- Push last run summary to morning briefing
- Alert on failure


# Failures

- media queries modify elements = xpath evaluation failure
- captcha.. random clicks, mt?
- plugin loses handle on browser tab?
- = browser crash?
- ~~expired session~~
- ~~not logged out~~
- ~~t&c popup~~

