# Installing

There are three options for speech to text APIs that you can use with this system.

1. IBM Watson STT
2. Gentle STT \(Open Source, needs a separate up for setup\)
3. Pocketsphinx \(Open Source, integrate inside of autoEdit, no extra setup needed\)

### Overview {#overview}

---

#### IBM Watson STT Service {#ibm-watson-stt-service}

##### Pros:

* 16 hours a month included in service. 0.02 cent a minute after that [see pricing](https://console.ng.bluemix.net/catalog/services/speech-to-text).

* Speed. In autoEdit, always takes 5 minutes to transcribe any duration of audio or video.

* Generally pretty accurate \(my opinion, judge for yourself\)

* Supports a number of languages [see here](https://console.ng.bluemix.net/catalog/services/speech-to-text). Including distinction between British and American English.

##### Cons:

* Need to provide card details for pay as you go fee.
* is in the cloud so no offline support.

---

#### Gentle Open Source STT {#gentle-open-source-stt}

##### Pros:

* Free as in free speech as well as in free beer.

* working locally on your machine. no internet connection needed because of that, good for sensitive material.

* Open source [github repo](https://lowerquality.com/gentle) and [I made a node module to work with the API](https://github.com/OpenNewsLabs/gentle_stt_node)
  .

##### Cons:

* Not as accurate as IBM one \(in my opinion, but decide for yourself\).
* Only support US english STT.
* In autoEdit, at the moment not as fast as IBM one, takes a little longer then the length of the media. \(eg 27 min takes 30 min to transcribe\).

---

#### Pocketsphinx Open Source STT

##### Pros:

* Free as in free speech as well as in free beer.

* working locally on your machine. no internet connection needed because of that, good for sensitive material.

* [Open source module in autoEdit ](https://github.com/OpenNewsLabs/autoEdit_2)originally extracted from [Videogrep](https://github.com/antiboredom/videogrep) project.
  .

##### Cons:

* Not as accurate as IBM or Gentle.
* Only support US english STT.
* in autoEdit, at the moment not as fast as IBM one, takes a little longer then the length of the media. \(eg 27 min takes 30 min to transcribe\).

---



