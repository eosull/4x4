# 4x4
Generative music making patch. Developed as part of an MA in Art &amp; Technology in University of Limerick in 2021. Research was conducted on generative and algorithmic approaches to music composition. These patches and the music that was composed using them are the product of that research.

## General
There is 1 patch in this repository, the results of which can be heard here:

- [Listen](https://eoin-osullivan.bandcamp.com/album/4x4)

This work was created by first inputting a series of notes which were used to teach markov chains. These markov chains then outputted a melody based on the initial series of notes. This melody was sent (in the form of MIDI messages) to Logic Pro X where it was synthesised by software instruments and recorded. In order to use the patch yourself, download the patch, open it in Max, input your own melody and start the patch. You will need to route the outputted MIDI notes somewhere to be synthesised in order to hear results. I used Logic Pro X but this can also be done within the max patch using an object such as [noteout](https://docs.cycling74.com/max5/refpages/max-ref/noteout.html). Further instructions and information are contained within the patches/sub-patches.

## Credits
This project utilises the [ml.* library](https://www.benjamindaysmith.com/ml-machine-learning-toolkit-in-max) to implement algorithmic processes such as markov chains.
