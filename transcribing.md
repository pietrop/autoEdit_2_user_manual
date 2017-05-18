# Transcriptions

If first time using the tool go ahead and [setup the STT API system first](/setup-stt-apis.md).

### 1. Adding a video/audio {#adding-a-videoaudio}

1. Click on `new`
2. Chose the media you want to open, audio or video.
3. Fill in title and description
4. Chose Speech To T ext system you want to use \(IBM American English is the default\)
5. `Save Transcription`

![](/assets/1_getting_started.gif)

[For a list of supported media file type see ffmpeg\(which is what has been used for the file conversion under the hood\)](https://ffmpeg.org/general.html#Supported-File-Formats_002c-Codecs-or-Features)

---

The transcription will take a round **5 minutes **process regardless of the length of the media

** **![](/assets/2_processing_transcription.gif)to

---

### 2. Selecting text from a transcription {#selecting-text-from-a-transcription}

If you click on a word the video starts playing from that point.  
Make a selections of text you’d like to include in your video sequence.  
![](/assets/3_transcription_2.gif "Transcription")

---

### 3. Exporting a video sequence\(EDL\) {#exporting-a-video-sequenceedl}

Export an EDL, which is an[Edit decision list](https://en.wikipedia.org/wiki/Edit_decision_list).

![](/assets/4_export.gif "Transcription")

You can export a video sequence of selection as they appear chronologically in the video.

#### Other export options 

There are other export options such as plain text or timecode text, as well as `srt` captions.

#### Note on Paper-editing

If you want to work with more elaborate selections pulling from multiple transcriptions, deciding the order to craft it into a story script [check out the paper-editing section.](/paperediting.md)

---

### 4. Reconnect in video editing software of choice {#reconnect-in-video-editing-software-of-choice}

[Checkout this section on how to open an EDL](/opening-edl-in-video-editing-software.md) in a video editing software of choice to get a video sequence of your selections.


---
<!--Donation notice -->

Sign up to the [mailing list](http://eepurl.com/cMzwSX), follow on [twitter](http://twitter.com/autoEdit2) and/or [facebook](https://www.facebook.com/autoEdit.io/) to keep up to date with the latest releases. Say hi at <a href="mailto:pietro@autoEdit.io?Subject=Hello" target="_top">pietro@autoEdit.io</a>, always curious to hear what autoEdit is helping you with.

[autoEdit.io](www.autoEdit.io) it's free and open source. Free as in free speech as well as in free beer.  [Help support the autoEdit project to keep it that way](https://donorbox.org/c9762eef-0e08-468e-90cb-2d00643697f8?recurring=true). Support will go towards fixing bugs, adding features, provide support for users etc...

