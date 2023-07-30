# Part - 1: Stream with OBS in 10 minutes
<br>

## Open Broadcaster Software

Open Broadcaster Software (OBS Studio) is a powerful, free live streaming app (and screen recorder) compatible with all the major live stream platforms. It is completely free and open-source, and it has lots of useful features to help you produce professional live streams. OBS Studio also allows you to record your video, connect to any live streaming or video conferencing platform, and use any digital camera for live streaming.

![Screenshot from 2023-07-27 11-18-02](https://github.com/Diya050/OBS_Tutorial/assets/124448340/cfaa359f-fac5-4547-b37f-b4c390620dd0)

## Installing OBS

- For `Windows` and `MacOS` download suitable files from https://obsproject.com/
- For Linux:
```
$ sudo apt install flatpak
$ flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo
$ flatpak install flathub com.obsproject.Studio
$ flatpak run com.obsproject.Studio
```
OR
```bash
$ sudo apt-get install obs-studio
```
OR
```bash
$ sudo snap install obs-studio
```

## OBS Studio Quickstart

### 1. Run the Auto-Configuration Wizard

If you're new to OBS or want a quick setup, use the Auto-Configuration Wizard. It automatically tests your system and finds optimal settings for streaming or recording, including resolution, bitrate, encoder, and streaming provider. Don't worry; you can always fine-tune the settings later.

The wizard appears the first time you run OBS. If you need to run it again, go to Tools -> Auto-Configuration Wizard.

![Screenshot from 2023-07-30 20-17-33](https://github.com/Diya050/OBS_Tutorial/assets/124448340/3347965d-0f06-40fa-9e65-d1ac4b0697f4)

### 2. Set up your audio devices

By default, OBS captures desktop audio and your microphone. To confirm this, check the volume meters in the mixer section of the OBS Studio window. If they don't move or you suspect the wrong device is captured, go to Settings -> Audio and manually select the appropriate devices.

For macOS users: You'll need an additional app to capture desktop audio due to macOS limitations.

![Screenshot from 2023-07-30 20-18-27](https://github.com/Diya050/OBS_Tutorial/assets/124448340/dc6f5fcb-938f-4497-89e6-87bd5d73d9ae)

### 3. Adding Sources and Scenes

The preview screen will show a black screen as OBS doesn't capture video by default. Also, one scene with name "scene" is already added in the scenes panel by default. To start capturing, add a source:

At the bottom of the window, locate 'Sources.' Click on the + button (or right-click inside the Sources box) and choose the source you want, such as:

- Display Capture: To record everything visible on a monitor.
- Game Capture (Windows only): If you're capturing a game.
- Window Capture: For non-game applications.
- Video Capture Device: For a webcam or capture card.
- And many more.

![Screenshot from 2023-07-30 20-18-46](https://github.com/Diya050/OBS_Tutorial/assets/124448340/2764fd66-686e-43e7-bd8d-0a011158865c)

Sources and scenes are powerful features of OBS Studio. Learn more about them [here](https://obsproject.com/wiki/OBS-Studio-Overview#scenes-and-sources).

For laptop users: If your game/window/display capture sources show a black screen, refer to our [troubleshooting guide](https://obsproject.com/wiki/Laptop-Troubleshooting).

### 4. Test your Stream and Recording Settings

Before going live, double-check your settings in Settings -> Output. When you're ready, click Start Recording or Start Streaming.

We recommend running a short test to ensure everything works smoothly before your actual stream or recording. If you encounter any issues or need further assistance, visit our help portal.

![Screenshot from 2023-07-30 20-19-13](https://github.com/Diya050/OBS_Tutorial/assets/124448340/fbe9479b-7251-40f6-976c-7a4d91966ed5)

Once you're satisfied, you're all set to create fantastic content! That's all there is to it!

Now you're all set to start streaming or recording with OBS Studio. Enjoy your content creation journey!

## Using Advanced Scene Switcher

### Installation

- If you are using snap you can install the following package for an OBS installation which comes bundled with the plugin:
```bash
$ sudo snap install obs-studio
```
- The plugin is also available via the Flatpak package manager for users who installed OBS via Flatpak:
```bash
$ flatpak install com.obsproject.Studio.Plugin.SceneSwitcher
```
- If you have installed OBS via other means, it is most likely necessary to install the plugin manually. To do so copy the advanced-scene-switcher.so file and into the OBS Studio plugin folder.

### Usage

- Once you have installed Advanced Scene Switcher you can access it from Tools > Advanced Scene Switcher

![Screenshot from 2023-07-30 20-27-22](https://github.com/Diya050/OBS_Tutorial/assets/124448340/06d170aa-0bb1-4287-81bd-bd0597fecde2)

- You will end up on the "General" tab of the plugin.
- In the General tab, you will find some of the global settings you may need to revisit once you get some automation set up.
   -  One thing to note here is the `Status` section, where you can choose to automatically start the switcher when you start recording, streaming, or both.
   -   There is also an option to start the switcher on startup if it was running previously.
   -   In the `Save/load settings` section, you can export/import the settings for a particular system.
   -   In `Match Behaviour` Section, you can set "what to view" when no actions are performed in a particular scene.
   -   You can also set priorities for various switching methods in `Priority` Section.
 
![Screenshot from 2023-07-30 14-10-51](https://github.com/Diya050/OBS_Tutorial/assets/124448340/a1bd3d61-da22-4387-a887-9d10fdc98bdc)

- In the Macro Tab, you can add several macros (like you did for scenes) by clicking the plus symbol on the lower left and enter a name for every new macro.
  - For each macro, you have to add the condition you want to trigger the automated scene switch by clicking the corresponding plus symbol and selecting the type of the condition we want to use by clicking the plus symbol on the lower left.
 
![Screenshot from 2023-07-30 20-13-27](https://github.com/Diya050/OBS_Tutorial/assets/124448340/4a62929e-c679-4439-a189-059bc39c7270)

  - As a last step we have to specify the action that has to be performed if the condition we specified above is true.
To do this we have to add a new action to our macro by pressing the plus button in the lower middle of the macro tab.
  - The default action that is chose is already our desired one - "Switch scene" - so we do not have to adjust the type of the action.
However we have to select the scene we want to switch to the transition type we want to use and the duration of the transition.

![Screenshot from 2023-07-30 20-13-43](https://github.com/Diya050/OBS_Tutorial/assets/124448340/ab8daba7-8400-413a-b404-142d42b439a3)

### Example:

We will make settings to switch from `web browser` to `terminal` after `1.00 minute` of time with `cut` transition.

- In General Tab, we will select Automaticall start the scene switcher when Recording or streaming.

![Screenshot from 2023-07-30 14-10-51](https://github.com/Diya050/OBS_Tutorial/assets/124448340/03820f05-b13e-43c1-b9a2-ee65736ab880)

- We will add a macro and do settings as follow:

![Screenshot from 2023-07-30 14-11-02](https://github.com/Diya050/OBS_Tutorial/assets/124448340/7c64933f-c971-4660-b8d3-af383ac4fd38)
