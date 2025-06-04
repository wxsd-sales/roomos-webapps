# Video Signage

This is an example Web App which plays a YouTube playlist or video on loop and is usefull for displaying content on Cisco Collaboration Devices in Signage or Kiosk Modes.


## Overview

This Web App makes it easier to display a YouTube playlist or video on loop. You can load the Web App as is and display the latest Webex YouTube content or set your own playlist or video to play via the Web Apps URL parameters


## Setup

### Prerequisites & Dependencies: 

- RoomOS 10.x or above Cisco Collaboration Device
- Control Hub Device Admin or Local Web Admin access to your Collaboration Device
- (optional) Web Server - Used for hosting your own copy of this Web App


### Installation Steps (Signage):
1.  Log into your devices local web admin interface
2.  Click ``Settings`` then ``Standby``
3.  Set the ``Signage URL`` field to the example live link below
    ```
    https://wxsd-sales.github.io/roomos-webapps/video-signage
    ```

    (optional) Set the playlist or video id is the video/s you would like to play instead of the default
    
    Playlist Id Example:
    ```
    https://wxsd-sales.github.io/roomos-webapps/video-signage#list=<YouTube Playlist Id>
    ```

    Video Id Example
    ```
    https://wxsd-sales.github.io/roomos-webapps/video-signage#videoId=<YouTube Video Id>
    ```
4.  Set the ``Signage Mode`` field to ``On``
    
    
    
## Demo

Check out our live demo, available [here](https://wxsd-sales.github.io/roomos-webapps/video-signage)!


*For more demos & PoCs like this, check out our [Webex Labs site](https://collabtoolbox.cisco.com/webex-labs).


## License

All contents are licensed under the MIT license. Please see [license](LICENSE) for details.


## Disclaimer

Everything included is for demo and Proof of Concept purposes only. Use of the site is solely at your own risk. This site may contain links to third party content, which we do not warrant, endorse, or assume liability for. These demos are for Cisco Webex use cases, but are not Official Cisco Webex Branded demos.


## Questions
Please contact the WXSD team at [wxsd@external.cisco.com](mailto:wxsd@external.cisco.com?subject=RepoName) for questions. Or, if you're a Cisco internal employee, reach out to us on the Webex App via our bot (globalexpert@webex.bot). In the "Engagement Type" field, choose the "API/SDK Proof of Concept Integration Development" option to make sure you reach our team. 
