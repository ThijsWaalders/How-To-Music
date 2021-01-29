# Integrating Maschine with Ableton
Receive and send MIDI and audio. From maschine to ableton, from ableton into maschine and the audio from maschine into each abletons midi track.
(note: this way you can only record the midi signal, so there is audio coming in the midi track, but you can't record it.)
1. In Maschine **route the groups audio** like this:
    - Note that EXT 1 is also used for the MASTER channel, so if you're getting issues you should check this out.
    1. GROUP A = EXT 1*
    2. GROUP B = EXT 2
    3. GROUP C = EXT 3
2. In Ableton **create a new midi track SHIFT+T**
    1. Insert a Instrument/External Instrument to every track you want to use for maschine (use the Maschine VST's track as the first, so GROUP B as EXT 2)
        * Set MIDI To **Maschine 1** (this sends the midi recorded in ableton to maschine)
        * Set Audio from **1/2 Maschine** (this is the audio from point 1.)
* **Be sure to turn off +ROUTING in Maschine when you load a kit with the browser**

### If you want to send midi (working with computer/mouse) to Maschine WITHOUTH USING MASCHINE
1. In Maschine **set for every sound it's own MIDI channel input** (you can only do this 16 times) 1, 2, 3 and set **Source: HOST and Thru: off or Thru: on **but disable record in ableton**