Monitor audio cable signal to change speaker power
================

I want a thingy that listens to an audio cable and turns a power plug on and
off depending on whether music is playing. It's a box with four ports:

* Female 3.5 mm audio
* Male 3.5 mm audio
* Female power plug
* Male power plug

When sound is coming through the audio cable, power goes through; when sound
isn't coming through, power doesn't go through. This may be more easily
to implement if we approximate this as follows: When sound is comes through,
power gets turned on; when sound hasn't come through for a minute, power gets
turned off.
