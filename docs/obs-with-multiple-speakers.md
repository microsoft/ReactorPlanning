# Setting Up OBS with Multiple Speakers
So you want to be able to have two (or more) people, not in the same physical space, present together? It takes a bit to ensure you have the proper setup, but
works on both Windows and MacOS. 

## Installing Software
You will need to download and install four software:
- [OBS](https://obsproject.com/)
- [NDI Plugin for OBS](https://obsproject.com/forum/resources/obs-ndi-newtek-ndi%E2%84%A2-integration-into-obs-studio.528/)
- [NDI Runtime](https://github.com/Palakis/obs-ndi/releases) which is usually linked to from NDI OBS plugin release notes
- [Skype](https://www.skype.com/en/get-skype/)
  - Make sure that the Skype you have was downloaded from the web *not* installed from the Windows Store.
  - If you have a version that wasn't downloaded from the web, uninstall, restart your machine, and re-install from the web.

## Perparing OBS and Skype
To make sure OBS has the NDI plugin properly installed:
- In OBS, under "Tools" click on `NDI Output Settings` anf choose OBS as your main output.

To make sure Skype is giving access to video and audio feeds through NDI:
- Open Skype, open Settings (you can find this by clicking on the three dots next to your name)
- Open the Calling settings
- Open Advanced
- Toggle `Allow NDI usage`

## Creating the OBS Scene and Testing
To make sure you have access to the Skype video feeds in OBS:
- In Skype, start a video call with another person
- Ensure that Skype has NDI enabled - there will be a notification at the top of the screen
- In OBS, create a new `NDI Source` 
- When creating the new `NDI Source`, choose the specific user as the `Source name`. It will likely be something like `RANDOM_CHARACTERS (Skype - [live] cid RANDOM_CHARACTERS)`
- If you want to include you as well, you can create an `NDI Source` where the `Source name` is `RANDOM_CHARACTESR (Skype - (Local))`

To test the setup:
We recommend actually doing a test stream on your personal Twitch channel. 
- Make sure the `Stream Key` in OBS is pointing to your personal channel and not one of Microsoft's professional channels
- Start streaming and start recording
- Make sure you can hear yourself, the other person, any computer audio you might have setup, and that there is no echo on both the live stream and the recording
