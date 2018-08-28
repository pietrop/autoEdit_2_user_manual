# Setup: STT APIs

There are three options for speech to text APIs that you can use with this system.

Check them out individually for extra setup instruction.

1. [IBM Watson STT](setup-stt-apis-ibm.md)
2. [Speechmatics](setup-stt-apis-speechmatics.md)
3. [Gentle STT](setup-stt-apis-gentle.md) \(Open Source, needs a separate app for setup\)
4. Pocketsphinx \(Open Source, integrate inside of autoEdit, no extra setup needed\)
5. [Rev - Transcriptions service](setup-stt-apis-rev.md)

## Overview {#overview}

### IBM Watson STT Service {#ibm-watson-stt-service}

#### Pros:

* 16 hours a month included in service. 0.02 cent a minute after that [see pricing](https://console.ng.bluemix.net/catalog/services/speech-to-text).
* Speed. In autoEdit, always takes 5 minutes to transcribe any duration of audio or video.
* Generally pretty accurate \(my opinion, judge for yourself\)
* Supports a number of languages [see here](https://console.ng.bluemix.net/catalog/services/speech-to-text). Including distinction between British and American English.

#### Cons:

* Need to provide card details for pay as you go fee.
* is in the cloud so no offline support.

[Check out for extra setup instructions for IBM](setup-stt-apis-ibm.md).

### Speechmatics STT Service {#ibm-watson-stt-service}

* 1 hour free credit with new account 
* Easy to setup credentials 
* Generally pretty accurate \(my opinion, judge for yourself\)
* [28 languages, see full list](https://www.speechmatics.com/language-support/) Including support for "accent agnostic global english".

### Gentle Open Source STT {#gentle-open-source-stt}

#### Pros:

* Free as in free speech as well as in free beer.
* Working locally on your machine. No internet connection needed because of that, good for sensitive material.
* Open source [github repo](https://lowerquality.com/gentle) and [I made a node module to work with the API](https://github.com/OpenNewsLabs/gentle_stt_node) .

#### Cons:

* Not as accurate as IBM one \(in my opinion, but decide for yourself\).
* Only support US english STT.
* In autoEdit, at the moment not as fast as IBM one, takes a little longer then the length of the media. \(eg 27 min takes 30 min to transcribe\).

[Check out for extra setup instructions for Gentle](https://github.com/pietrop/autoEdit_2_user_manual/tree/d5c8cea5ec4e2a1cee11515e8a838d832407badc/setup-stt-apis-gentle.md).

### Pocketsphinx Open Source STT {#pocketsphinx-open-source-stt}

#### Pros:

* Free as in free speech as well as in free beer.
* working locally on your machine. no internet connection needed because of that, good for sensitive material.
* [Open source module in autoEdit ](https://github.com/OpenNewsLabs/autoEdit_2)originally extracted from [Videogrep](https://github.com/antiboredom/videogrep) project.

  .

#### Cons:

* Not as accurate as IBM or Gentle.
* Only support US english STT.
* in autoEdit, at the moment not as fast as IBM one, takes a little longer then the length of the media. \(eg 27 min takes 30 min to transcribe\).

Pocketsphinx does not require extra setup to use.

### Rev Transcription service {#rev-transcription-service}

#### Pros:

* [Transcription service from real humans](https://www.rev.com/transcription)
* In theory more accurate then automated transcriptions
* word level timestamps 

#### Cons:

* Price more expensive then automated transcriptions
* Turnaround slower then automated transcriptions.

\_\_

{% hint style="info" %}
Sign up to the [mailing list](http://eepurl.com/cMzwSX), follow on [twitter](http://twitter.com/autoEdit2) and/or [facebook](https://www.facebook.com/autoEdit.io/) to keep up to date with the latest releases. Say hi at [pietro@autoEdit.io](mailto:pietro@autoEdit.io?Subject=Hello), always curious to hear what autoEdit is helping you with.
{% endhint %}

{% hint style="info" %}
[autoEdit.io](http://www.autoEdit.io) it's free and open source. Free as in free speech as well as in free beer. [Help support the autoEdit project to keep it that way](https://donorbox.org/c9762eef-0e08-468e-90cb-2d00643697f8?recurring=true). Support will go towards fixing bugs, adding features, provide support for users etc...
{% endhint %}



