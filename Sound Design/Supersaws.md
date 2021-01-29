# How to create a Supersaw (without layering)

Hey all, I feel like there are tons of supersaw tutorials out there but few of them touch on how to make it past the "detune your saw waves" stage to make it sound nice, so I figured I'd type up a little tutorial on how to make [this](https://soundcloud.com/holy-city/supersaw-w-fx/s-XuNSc) kind of sound in a single Massive patch, with a little effects later.

(I think another layer and some more work would sound nice, but I wanted to do it in a single synth as a challenge)

Starting with the [default](http://i.imgur.com/VOofJe3.png) patch,

turn on the other two oscillators and detune them like so. You can do more if you want, I left it at +/- 10 cents. We're sticking with the basic saw/square I wavetable all the way to saw because that's all we really need to do. Other wavetables that work for this kind of sound are the Rough Math II all the way to the right (a bit brighter than normal saws) and the saw/sync oscillator that's fun to get more brightness out of.

[Here are the oscillator settings](http://i.imgur.com/dnCq47R.png)

Back to this sound, you can hear it starting to get a little noisy on top and muddy on bottom. It's also totally centered and the notes are fighting for space. To clear that up, I used keytracking. You can click the yellow square in the bottom right hand corner labeled "KTr" and use it like any modulator.

In this case, I used keytracking on the pan control, the "level" of the amplitude envelope, and the cutoff of a lowpass filter. The idea is to filter the low notes more than the high notes to keep it from getting noisy, to pan it so the low notes are further to the left than the high notes (to create an image), and to provide a foundation for the sound. Sound is a pyramid, the lower notes must be a strong foundation for the higher notes to cut through. Normally you accomplish this through layering, but we only have one synth in this instance.

[These are the keytracking settings.](http://i.imgur.com/ZFryGbl.png)

After that's done, time to make it a super-duper saw with unison. Massive works more efficiently if the number of unison voices is divisible by 4 (according to the manual), so I chose 8 voices. By holding control while adjusting the detune you can fine tune it, same goes for the pan control.

[Here are my voicing settings.](http://i.imgur.com/kK6SC0r.png)

Now the last thing to do in the patch is to fine tune the core tone. People always forget about the EQ section of Massive. Use it! I cut some of the lower mids and added a high shelf boost, to make the overall patch a little brighter and less cluttered.

[Here's what that looked like.](http://i.imgur.com/ZFryGbl.png)

Now onto processing, which is where people keep a lot of their secrets... but there isn't really any secret trick to this part. The core tone is there, so the goal is to carve out the stuff you don't want and accentuate what you do.

[Here's my signal chain.](http://i.imgur.com/L9VYDrj.png) The order goes EQ->OTT->IVGI->Post EQ.

The first EQ cuts the mids, again. This brings out the upper mids and gets rid of mud. OTT is a freeware plugin from XFer (credit to [/u/steve_duda](https://www.reddit.com/u/steve_duda), I love this thing). It's a multiband compressor that squashes the mids and I feel brings out the best in a supersaw. No idea what it's really doing, but awesome. ([Link](http://xferrecords.com/freeware/) to OTT).

Next is a freeware distortion/saturator called IVGI. It's an analog modeling unit that adds some girth and brightness to the highs. It's not doing much in this chain, just adding a little subtlety.

Afterwards is an EQ to tame back what OTT and IVGI brought out.

Lastly is the FX send. I used just some simple reverb and delay. The trick is sidechaining it to the super saw, which makes it swell back into the next note. Other trance guys will do reverse reverb swells or really heavy sidechaining, but it's the same concept (this is less work).

[Here's the FX send.](http://i.imgur.com/WuLxZXG.png)

Hope that was helpful, criticisms are more than welcome!

## Resource

[On Supersaws (without layering @ Reddit.com)](https://www.reddit.com/r/edmproduction/comments/1xhcj6/on_supersaws_without_layering/)