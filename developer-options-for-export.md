# Developer options for export - draft

Both in transcription view and in paper-edit view, there is the option for developers users to export a `json`. Either of the transcription or of the paper-edit. 

This is because autoEdit could be used as a starting point to build interactives that have some component that is "transcription powered". 

## Example
For example, I once went to a POV hackaton, and finished 2 hours before the deadline thanks to this. 


- [github repo](https://github.com/pietrop/BattleSounds)
- [presentation](https://docs.google.com/presentation/d/19TB4CpkCDqMJQvhmZF3I9AN7IQ0VsIA8nsfpdHkfDss/)
- [interactive](http://pietropassarelli.com/BattleSounds/)
- [Notes on tech used](https://github.com/pietrop/BattleSounds/blob/master/notes.md)


The idea is that you can get the transcription (or paper-edit) `json` from autoEdit, as well as the converted webm video. [Combined with some client side tempting and a js  logic](https://github.com/pietrop/BattleSounds/blob/master/docs/index.html#L171) can quickly make an "hyper-transcript".
