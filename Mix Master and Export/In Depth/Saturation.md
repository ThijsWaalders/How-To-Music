# Saturation

## What is Saturation?
Saturation is like an analog distortion: When an analog audio signal is driven too loud (above 0dB) and the audio start to distort and break up, it usually sounds really nice and pleasing. Unlike digital distortion or clipping when it hits 0dB and starts cracking. (Analog can go over 0dB unlike digital that can't go above 0dB.)\
There is loads of different characters to this saturation like **Harmonics** **Distortion** **Fluttering** **Compression**.
So Saturation makes the sound more full / warmer / thicker.

### Examples
1. **Visualize and hear what Saturation does**.\
   Put in a synth/oscillator with a pure sine wave. After that a Saturation FX plug-in and at last a Spectrum Analyzer.\
   Put the Saturation all the way down and check the Spectrum Analyzer, you should see one single peak/tone.\
   Then turn up the Saturation and watch the Spectrum Analyzer. As you can see there are a lot of Harmonics added by the Saturation FX (the more saturation, the more harmonics _until the distortion occurs_).
2. **Saturate a drumkit**
    Get a sound, put on a Saturation (tube for example) and _control the gain in and out_ the plug-in.
    - Why you need to **gain stage** properly: When your input is too low, nothing is going to happen. When your output is too high _distortion_ happens immediately.
        - Check out the [Gain Staging](https://www.youtube.com/watch?v=pinNLBnBRe8) video from In The Mix if you want to know more details about this:
        1. **Do not clip the mix bus**: get rid of the clipping on you mix/master track/bus, so start at the source/beginning (Turn down the gain in you vst, then the fader of that track and then the master).
        2. Make sure **your vst's volume is at the right volume**. (Most plug-ins don't respond linearly, if your plug-in does **_feeding -18dB won't hurt them (So...?!?!)_**. You should use the guideline to be usually around -18dBfs RMS / VU around 0. This will reduce the chances of unwanted distortion and ensure that they are working in the sweet spot. If you're using a plug-in to turn up the gain make sure you're not building too much volume, so the volume stays the same when you by-pass the plugin (**err?**) .
        3. **Optimize Fader Position**\
            Put a gain unit at the end (and at the beginning of your FX chain) and lower the gain so you get more resolution out of your fader.\
        This is good when using a DAW, don't use these 3 points when using Analog only because you will induce a lot of noise.
3. **Saturate a track**
   The tricky bit is the right amount of the right type and amount of Saturation to the right source.
   - Experiment with different types of saturation for each source.
   - Just add a Saturation without EQ or Compression and hear how it looks like you did add EQ and Compression.
   - Use it a little (15/20%) on Atmosphere/Pad sounds can really enhance your track.

### Resources
[Mixing With Saturation - Why You Need It](https://www.youtube.com/watch?v=6sVUYESg_Os)\
[Gain Staging - The 3 Rules You Need To Know - In The Mix](https://www.youtube.com/watch?v=pinNLBnBRe8)