# Part - 1: Stream with OBS in 10 minutes
<br>

## Open Broadcaster Software

Open Broadcaster Software (OBS Studio) is a powerful, free live streaming app (and screen recorder) compatible with all the major live stream platforms. It is completely free and open-source, and it has lots of useful features to help you produce professional live streams. OBS Studio also allows you to record your video, connect to any live streaming or video conferencing platform, and use any digital camera for live streaming.

## OBS Interface:

**Preview Area:** The area where we can view what is being recorded.

**Controls:** The box in the bottom right having "Start Streaming", "Start Recording", "Start Virtual Camera", "Studio Mode", "Settings" and "Exit" is the control panel of OBS.

**CPU Usage:** It shows CPU Usage information which tells us if our computer is under load or not to prevent bad live streams.

**Scene Transitions:** To the left of the Controls window, we have a panel for scene transitions that allows us to set what kind of scene transition effect will take place when we switch between scenes.OBS also provides additional built-in scene transition effects which we can add to the Scene Transitions drop-down list.

- Swipe
- Slide
- Stinger
- Fade to Color
- Luma Wipe

**Audio Mixer:** In the middle is the window that allows us to easily see and adjust our volume levels for each of the different elements or sources in our live stream.

**Sources:** Left of the Audio Mixer, we can add all of our webcams, images, videos, websites or any other sources into our live stream.

**Scenes:** In the bottom left corner is the Scenes panel.They are video canvases that are made up of one or more visual (and audio) elements from those sources. We can switch between various scenes.

## Settings:

### General Settings:
<br>

**General:** We can set language and theme for OBS studio. Also, "open stats dialogue on startup" option if enabled will allow us to view more information about CPU usage everytime we start OBS.

**Output:** Under the Output section we can also adjust these settings:

- Show confirmation dialogue when starting streams
- Show confirmation dialogue when stopping streams
- Show confirmation dialogue when stopping recording
- Automatically record when streaming

and many more to enhance our streaming.

**Source Alignment Snapping:** Source alignment snapping refers to the ability to automatically align sources (such as images, videos, or overlays) with each other or the canvas grid to create a more organized and precise layout.

**Projectors:** Individual sources, scenes, program, preview or the built-in OBS Multiview can be projected either in fullscreen or as a window.

**Multiview:** The OBS Studio Multiview feature is an ideal solution for live video production environments where a user wants to set up multiple scenes using multiple cameras as the sources.
<br>
### Stream Settings:
<br>

This is where you can select which service you want to stream to. The primary ones you can select from are:

- Twitch
- YouTube
- Facebook Live
- Restream.io
- Twitter
- Show All… 

If you select Show All… you’ll see a comprehensive list of all the supported live streaming platforms. If we go for YouTube live stream, we nees streanm key or can also connect our account.

### Output Settings:

**Streaming Output Settings:** The two main settings you’ll want to adjust here are the video bitrate and audio bitrate.

**Video Bitrate:**
So when it comes to configuring your live stream, the default Video Bitrate is 4000 kilobits per second (kbps). To improve our live stream's video quality, increase the video bitrate, but ensure our internet speed can handle it.

**Audio Bitrate:**
We can also adjust the audio quality in the Audio Bitrate section. It is recommended to always stay above 128 here. 

The default is 160 which will give pretty good results. If the only audio in your live stream is our voice – this will be fine. If we require high quality audio such as for live streaming with music or using multiple audio tracks, we could set it anywhere from 192 right up to 320.

**Recording Output Settings:**
The OBS Screen Recorder is another awesome tool that we might want to adjust the settings for. Go to the Recording settings – here we can check the video recording quality and video recording format. We can also specify a recording path.
For recording quality, the options here are:
- Same as stream
- High Quality, Medium File Size
- Indistinguishable Quality, Large File Size
- Lossless Quality, Tremendously Large File Size

For recording format, .mp4 which is a universally recognized format is preferred.

With audio track (1-6), we can record 6 different audio tracks at a time (except in option "same as stream" for recording quality).


### Audio Settings:

Most of these settings will be fine to leave on the default, but there are a couple we might want to change.

**Channels:** Under General you can adjust the Channels setting. We’d recommend setting this to Stereo unless you specifically need to be broadcasting in Mono or 5.1 for example.
It depends on our personal preferences.

**Mic/Auxiliary Audio:** In the Audio tab under Global Audio Devices, we can adjust the Mic/Auxiliary Audio setting. This is our primary audio source. So change this from Default to whichever microphone we have connected.

Even if the default setting is using our correct microphone because of your System Settings, it is still strongly recommended manually setting it here just so we don’t have any issues down the track.

### Video Settings:

**Resolution:** Base (Canvas) Resolution refers to the resolution of the live stream in OBS. The default here is 1920 x 1080. Output (Scaled) Resolution refers to the resolution of the live stream that’s being broadcasted out to other platforms or even recorded. The default is 1280 x 720p.
Thus, the frame rate in OBS Studio doesn’t need to be the same frame rate we’re pushing out. Switch the Output (Scaled) Resolution to 1920 x 1080 to get high quality.

**Frame Rate:** You can adjust the frame rate by adjusting the setting called Common FPS Values.It defaults to 60 but we recommend setting it to 30. 60 FPS has a higher recording bitrate and takes up more storage. But if you want your viewers to experience no lag while watching gameplay videos and other high-quality content, this is the best option.

### Hotkeys Settings:

Hotkeys are keyboard shortcuts we can set up to control OBS Studio.

Some functions we can assign hotkeys to include:

- Start streaming
- Stop streaming
- Pause recording
- Split recording file
- Start virtual camera
- Show source toolbar
- Many more! 

This definitely isn’t necessary but it’s a great way to streamline our workflow so that we can control and configure everything really easily while we’re live streaming.

### Accessibility: 

This is a newer feature in OBS that helps people who may have a disability or eyesight issues.
You can select colors throughout the interface to better suit your needs.

### Advanced Settings:

- There are lots of advanced settings you can play around with in this section.
- One that we highly recommend selecting is Automatically Reconnect. This means if your internet connection drops out for any reason, OBS Studio will automatically attempt to reconnect and restart your stream.
- We can also specify names to be given to our recordings here.
- We can even set time for stream delay if required.

## Studio Mode:

When Studio mode is enabled, If you click a Scene, it will appear in the left window but won’t be visible to our viewers (essentially queuing it up). When we’re ready to bring that Scene on screen, press Transition and then our viewers will be able to see it.

To disable Studio Mode at any time, just click the Studio Mode button again in the Controls panel. In Studio Mode, we can easily switch between the different scenes we’ve set up. This is a more advanced feature.

## How to Use OBS Studio Scenes

As we mentioned earlier, Scenes are a useful feature that allow you to configure groups of assets or elements to use in your live stream. After creating a Scene, you can add assets & elements in the Source panel that you want to be assigned to that Scene.

We’ll run through how to create scenes, how to add sources and some examples of different Scenes you might like to create.
How To Create Scenes In OBS Studio

In the Scenes panel you’ll see there’s a default scene already created called Scene. This is because there always has to be at least one Scene.

You can rename it by right clicking and going to Rename. It’s a good idea to name this something that clearly tells you what the Scene is e.g. Main Camera.
Rename setting shown after right clicking a Scene in OBS StudioRight Click a Scene and rename it according to your workflow

## How To Add Sources In OBS

To adjust the source for the Scene, make sure the Scene is selected and press the + button in the Sources panel.

There are lots of different sources to choose from but say you wanted to add an extra video source, you would select Video Capture Device.
Plus (+) icon used to add Sources in OBS StudioAdd your cameras or images by clicking the plus (+) symbol under Sources

You can rename it, then you can select which video source you want to add by going to the Device drop down menu.

Under Preset you can choose from a range of options. We usually select High which is the highest quality option available (1920 x 1080p).
Pop-up Window where you can choose and set up which device to use as a source in OBS StudioChoose the device you want to use for your Main Camera Scene

But as we mentioned, you’re not only limited to adding video sources. If you press the + button you could also select Image, for example. Then you can select an image from your computer, press Open and then Okay.

The image will appear full screen in your Preview Area. To turn that source on or off you can press the Eye icon beside that source.

## Examples Of Scenes In OBS Studio

Now let’s run through some examples of the different Scenes you might want to create.

### Creating A Presentation Scene

Let’s add a new Scene and call it Presentation.

With that Scene selected, go to the + button in the Source panel. We’re going to add three images to use as presentation slides. So we’ll select Image and upload those images to OBS one at a time.
Adding an image as a Source in OBS StudioAdding Image as a Source can let you create a Presentation Scene

`PRO TIP:` You can change the order of any Sources by clicking and dragging them.

Now at any time we click on the Presentation Scene to access those images/presentation. Or we can switch back to the main camera by clicking on the Main Camera Scene.
3 Images added as Source for a Presentation SceneSimply drag the Sources to arrange them in the order you prefer

### Creating A Screen Share Scene

Hit + in the Scene panel to create a new Scene. We’ll name it Screen Share.
Display Capture option under Sources interface in OBS StudioShare your screen by creating a Scene and adding your Display as a Source

Then press + in the Source panel and select Display Capture. You’ll need to give it a name and then you’ll be taken to a new window.

Under Display select the screen you want to share.

`PRO TIP:` If your screen share doesn’t fit the screen you can resize it by clicking and dragging the corners.
Resizing a Source in Preview by dragging the corners in OBS StudioAdjust and fit your Source in your Preview by clicking and dragging the corners

### Creating A Picture-In-Picture Screen Share Scene

Follow the steps in the previous section to create a screen share scene or you can duplicate your existing screen share scene.

With that Scene selected, press the + button in the Source panel to add another source. Select Video Capture Device and under Device select the camera you want to use.
Video Capture Device option under Add Sources in OBS StudioAdd Video Capture Device as a Source to create a Picture-in-Picture Scene

Hit OK and you’ll see a box with that camera source on your Preview Area. You can resize this box by dragging the corners and you can click & drag it to change the position.

Now that you’ve got a range of different Scenes, you can move between them quickly & easily  just by clicking on your desired Scene in the Scenes panel.
Picture-in-Picture set up in OBS Studio Scenes Similar to the other sources, you can adjust your Picture-in-Picture by dragging the corners

## OBS Studio Effects

There are ways to customize your video and audio even further.

Select your Scene and then select the video source you want to adjust in the Source panel.

Then hit the Filters button just below the Preview Area. A new window will appear.
Filters settings button on top of the Sources interface in OBS StudioAdd filters to your streams or recordings by clicking this Filters button

The top option here says Audio/Video Filters but they’re mainly audio filters. If you press the + button you’ll see a range of options such as:
- Compressor
- Expander
- Gain
- Noise Suppression
- Video Delay (this one is really useful if your video & audio are out of sync)

Plus (+) symbol inside Filters window with a number of options for Audio FiltersAdd Audio Filters with these options by clicking the plus (+) icon

Below that you’ll see Effect Filters. Press the + button and you can customize a number of things including:

- LUTs
- Chroma Key (if you’re filming on a green screen)
- Color Correction
- Luma Key
- Many more

Video Effects under Filters settings in OBS StudioSimilar to Audio Filters, hit the plus (+) sign too add effects or even use Chroma Key

Let’s take a look at what you can do with the Color Correction filter. Hit Color Correction and you’ll need to give the filter a name (it’s fine to leave this as Color Correction).

Here you can adjust things like the contrast, brightness, saturation, hue and opacity.
Color Correction Effects under OBS Studio Filters settingsPlay around different settings in Filters like Color Correction

## How To Crop Video Sources

Another tool you can access in the Filters section is Crop. Let’s say you wanted to crop the picture-in-picture that you added to your screen share earlier.

Select the relevant Scene and Source, then hit Filters. Under Effect Filters go to Crop/Pad and hit OK.

Then you can adjust the setting for Left, Right, Top and Bottom until you reach your optimal crop.
Crop/Pad Effects option in Filters settings in OBS StudioAdjust the size of your Picture-in-Picture using Crop/Pad filter
OBS Studio Graphics

There are a number of elements you can add to your live stream to make it more engaging and professional.

## How To Add Text In OBS Studio

To add text to your live stream, select the Scene that you want to add text to and then press the + button in the Sources section.

Select Text, give the Source a name and hit OK.
Text (FreeType 2) Source Option to add texts in OBS Studio ScenePut texts in your stream or recording by adding Text as a Source

Then type in the text you want to appear on screen. You can adjust the font and if you scroll down you’ll see some more settings such as:
- Color
- Outline
- Drop shadow
- Text width

Once you’ve made those customizations, hit OK.
Font setting menu where you can change the font and size of the text added in OBS StudioTexts can be customized by changing the font, size, and color

## How To Add A Logo In OBS

Let’s say you’d like to add your logo alongside the text in your live stream. Hit the + button in the Sources panel and go to Image. Again, give it a name and then select the image you want to add.

You can scale the image by dragging the corners and you can move it around by clicking & dragging.

Don’t forget you can turn off any sources by clicking the Eye icon.
Primal Video logo on the top right corner and Tom Rawlins text on the bottom right corner added in an OBS Studio SceneAdd a logo just by adding an image to your Scene and adjust it to your liking

## Going Live In OBS Studio

Now that you’ve got everything set up, it’s time to go live!

In the Controls panel in the bottom right corner, select the Start Streaming button.
'Start Streaming' button in the Controls interface on the bottom right corner of OBS StudioSimply hit ‘Start Streaming’ to go live

A pop up box will appear that says: You need to set up a broadcast before you can start streaming.

Click the Manage Broadcast button and go to Select Existing Broadcast in the top menu.

Since we previously connected our YouTube channel, it’s all ready to go. You just need to click the broadcast and press Select broadcast and start streaming.
Broadcast setup screen with 'Select broadcast and start streaming' button in OBS StudioAfter selecting the account you’re streaming to, hit ‘Select broadcast and start streaming’

And now you’re live! In the bottom right corner you can see how long you’ve been live streaming for, the CPU usage and how much data you’re using.

Now if you open your YouTube Studio, this is where you’ll be able to view and respond to any comments.
View of YouTube Studio when you go live where you can see a preview and some analytics dataView and respond to your viewers once you’re live on YouTube

## Going Live With Studio Mode

As we mentioned earlier, you can also live stream in Studio Mode with OBS. This is a more advanced feature, so those live streaming pros out there might like to try this feature.

To do this, click Studio Mode in the Controls panel. You’ll then have a second window next to the Preview Area.
Studio Mode setting under OBS Studio Controls interface that you can use to switch between different ScenesIn Studio Mode, easily switch between the different scenes you’ve set up

If you click a Scene, it will appear in the left window but won’t be visible to your viewers (essentially queuing it up). When you’re ready to bring that Scene on screen, press Transition and then your viewers will be able to see it.

To disable Studio Mode at any time, just click the Studio Mode button again in the Controls panel.

Now you know exactly how to live stream with OBS Studio.
