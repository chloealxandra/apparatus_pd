# apparatus_pd
PD patches, sketches, sound design for performance

sampler.pd is an example of how to sample, and pitch bend a file using a slider for pitch bend as well as a slider for volume

playbackfromdisk.pd is an example of how to play back a file from disk (you can not alter this sample asides from volume) - great for large files running in situations with smaller RAM

fmout.pd is a FM Synth abstraction using the envgen GUI object form ggee library

main.pd is an inprogress file for rehearsal play back which includes abstractions - they use notein and ctlin objects to link to a midi controller:
  3chord.pd, synth1.pd, synth2.pd, copysynth1.pd are all simple multiple oscillator synth abstractions
  fmabs.pd is a simple FM synth abstration for use with an external patch

  vosim: http://bagger288.com/goldenmaster/vosim-synthesis-for-the-masses/
  patch is controlled both by durational settings and extended / altered in tone by external sounds through input mic (adc)

  pitch shifter takes adc and outputs transposed pitch shift (half steps) to dac from examples, posting as i use this tool often.

