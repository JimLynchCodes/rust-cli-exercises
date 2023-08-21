# Audio Stutter
Create a cli tool that takes a sound file and adds a cool stutter effect to it!

<br/>

## Backstory
Suppose you are a music producer or audio engineer, and you want to be able to offer cool audio effects to the artist vocals or sounds.

You decide to build a cli tool that takes an audio file and outputs the file with the stutter effect applied!

<br/>

## The Exercise
Write a cli tool that reads an input audio file, applies the stutter effect, and writes and output file.

The input file path can be hardcoded, and you can decide what audio filetype(s) the cli tool accepts.

The stutter effect is defined by copying the beginning portion of the audio clip some number of times, which should be configurable with two optional flags.

1) _duration_, --duration or -d, should accept a u32 integer parameter representing the number of milliseconds from the beginning of the clip that should be copied, with a default value of ( 1000 ). 

2) _repeats_, --repeats or -r, should accept a u32 integer parameter representing the number of times the stutter clip should be copied, with a default value of ( 2 ). 

<br/>

## Tests
It's up to you to decide how to unit test this code.

Have at least one integration test that verifies the created output file matches some known-to-be-good example output file when passed the same input audio file.

<br/>

## Skills Practiced

- Reading and writing audio files

- Manipulating audio buffers

<br/>

## Bonus
- Rather than a cli tool, try deploying this as a VST plugin for DAW applications like Logic Pro and Pro Tools!

- Add an additional argument for starting the stutter clip from a point within the clip rather than always from the beginning.