# How To Automate Maschine in Ableton Live

Maschine is a pain in the ass if your talking about _automation_. You can't draw a simple line like you can in a DAW.
So here is my way how to create real automation envelopes in Ableton Live.
I hope to figure out how to do this in FL Studio, if you know how please let me know @ henk418@gmail.com

After I've created a project in Maschine, I will save it with the BPM in the title. After that I'll load Ableton Live in **Arrangement view** and then:

1. **Load the Maschine** vst _in a Midi Track_, load your project and set the BPM in Ableton corresponding to your projects bpm
2. **Unfold Device Parameters** (in the Maschine vst device title bar you'll see a play button) and hit **Configure**
3. Now _go to Maschine vst_ and go to the sound/instrument you want to automate, **unfold the automation tab** (sort of an eject icon in the center on the left)
   1. Rename the parameters name in the **Pages tab** (right click _under_ the knob and rename
   2. Set the automation to **HOST** under the **Automation tab**, then **click on enable** (under the parameter you want to automate)
4. Now use the mouse or map it to a midi controller to change the parameter inside Ableton Live
5. **Check if the Automation arm button is on** (next to the + icon right from the transport control) and **Record** (it's not necessarily to turn on _Rec Arm_

**Done!**

Now it is time to:

6. Edit, Mix, Master, Upload!
7. If you only want to use a few automations, record them in the Maschine vst midi track.
8. Or go crazy and record them on multiple midi tracks, but then you have to set those midi output ports and probably some input ports in the maschine (I will add it when I've done it).