# SONY_DSC-RX100M4
SONY DSC-RX100M4 high speed video considerations

![cam](https://user-images.githubusercontent.com/8225621/50221827-b2211100-0396-11e9-8284-7011a39d3337.jpg)

## Introduction
Below are some considerations for the SONY DSC-RX100M4 camera when using it for high speed video recording.
Most things can be found in the [SONY manual](https://www.sony.com/electronics/support/compact-cameras-dsc-rx-series/dsc-rx100m4#manuals)

## Reset
A clean way to start is doing a *Setting Reset* first:
(this will not delete media on the device)
- press MENU button
- goto the very last page
- choose *Setting Reset*

## 1000Hz
Now set the HFR (High Frame Rate) from 250 to 1000Hz:
- press MENU button
- goto the first tab
- goto page 2
- choose *HFR Settings*
- choose *Frame Rate*
- choose 1000fps

## Do recording
- set the top rotary switch to HFR
- press *center* button
- press MOVIE button 
- recoding of about 2 seconds will start (display shows "Buffering...")
- afterwards the display will show "Recording..." while writing movie to SD card
- when one cancels the already written part will be stored as a movie

## Viewing the recording
- press play button 
- press *center* button
- the movie will play 20x slower
- the duration shows 40 as 2x20=40

## IMPORTANT
In contrast to the manual, the ![next](https://user-images.githubusercontent.com/8225621/50165405-36b35700-02e5-11e9-8c1d-1e66684b2830.PNG) button will **not** show the next frame!
You see the duration timer going up 1 second on every press.
Also when filming my cheap LED bulb, which I know flickers at 100Hz (being on at the positive and the negative peak of the 50Hz sinus wave), I have to press the ![next](https://user-images.githubusercontent.com/8225621/50165405-36b35700-02e5-11e9-8c1d-1e66684b2830.PNG) button 5 times (meaning 5 milliseconds) instead of 10. I think this is because I'm skipping seconds in the '40 second' slow motion video and looking at a lot of on/of cycles instead of one.

## Viewing frame by frame
- get the .MP4 from the SD card (in \PRIVATE\M4ROOT\CLIP\)
- open it in with [VLC](https://www.videolan.org/)
- pause the video (space-bar)
- use 'e' key to go to next frame <BR>
Or:
- open it in with QuickTime
- use 'right' key to go to next frame <BR>
Or:
- open it in with Windows Media Player
- use 'Ctrl'+ play button to go to next frame

## Example recording
You can download my cheap LED bulb recording [here](https://raw.githubusercontent.com/JdenHartog/SONY_DSC-RX100M4/master/C0010.MP4) (right-click and choose Save as...). In contrast to the old filament light bulb, the LEDs go dark in between the 50Hz sinus min and max. This results in the light flashing at a 100Hz meaning a 10ms period, so 10 frames for a 1000fps recording. 
