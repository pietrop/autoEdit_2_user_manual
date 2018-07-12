# Setup: Transcription APIs - Rev

#### GET Rev  API Keys {#get-rev-api-keys}

See [here to get API keys for Rev transcription t service](https://www.rev.com/api/quick-start/moving-to-production)

<!--
if you are a developer there is also an option to get sandbox credentials to try out with their demo content. However unfortunately, for some reason, their demo transcription does not match the corresponding video file, and does not have word accurate timestamps. -->


#### Add the API keys to the app at startup {#add-the-api-keys-to-the-app-at-startup}

When you first launch the app by double clicking on it you are taken to the credentials page. Where you can add Rev transcription service username and password API keys.

![Rev credentials](/assets/credentials-rev-.png)

Click on `Save Credentials`

Click on `Save Credentials` and that’s it. You are ready to go.

Visit the credentials page to review or change the API keys.

##### Using Rev in autoEdit
1. When choosing Rev, as a transcription option, you'll be prompted to add the order number for the transcription.

2. You also need to add the original file you'd like to reconnect with the transcription. 

This allows to get informations about the original media, [so that when you export an EDL from autoEdit](/paperediting.md), [you can reconnect to the right source footage in your video editing software of choice](/opening-edl-in-video-editing-software.md).

##### Rev Order number, media files and transcriptions

If you have submit multiple media per one order.

If there are multiple transcriptions associated with one order, autoEdit, in current implementation, will only retrieve the first one.

The workaround is to keep one media file per order, for now.


##### Rev and autoEdit

Note that autoEdit, for simplicity in the current implementation, does not let you submit an order to Rev through the app. You'd have to submit your transcriptions orders through the Rev website, and then use the order number to add it to autoEdit, when Rev notifies you that the transcription is ready.

---
Now you are ready to chose Rev as an option [when adding a new transcription](/transcribing.md). Checkout the[ transcribing section of the user manual](/transcribing.md) to see how to do that.

---
<!--Donation notice -->

Sign up to the [mailing list](http://eepurl.com/cMzwSX), follow on [twitter](http://twitter.com/autoEdit2) and/or [facebook](https://www.facebook.com/autoEdit.io/) to keep up to date with the latest releases. Say hi at <a href="mailto:pietro@autoEdit.io?Subject=Hello" target="_top">pietro@autoEdit.io</a>, always curious to hear what autoEdit is helping you with.

[autoEdit.io](www.autoEdit.io) it's free and open source. Free as in free speech as well as in free beer.  [Help support the autoEdit project to keep it that way](https://donorbox.org/c9762eef-0e08-468e-90cb-2d00643697f8?recurring=true). Support will go towards fixing bugs, adding features, provide support for users etc...
