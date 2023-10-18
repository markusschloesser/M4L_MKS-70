# A M4L (max for Live) device for the MKS-70 and JX10
A Max for Live device for the Roland MKS-70 and JX-10 with Vecoven mod

Prerequisites:
1. MKS-70 or JX10
2. Vecoven Mod v4.x (3.x will only work for Patch Parameters, but not for Tone)
3. Ableton Live Suite 11 (only one tested, MIGHT work with Live 10)

With this m4l device you can control and edit all (!) parameters of the Roland MKS-70 and JX10 from Ableton Live.
This is done separately for UPPER and LOWER, that's why the device is soooo fucking wide, there's shitloads of parameters, apologies.
I might at some point do a popup version, but would need to learn this first 😇.

The device is currently unidirectional (M4L device > MKS70), which means 2 things:
1. The values of the controls will not have a correct representation of the actual values on the synth, UNLESS you change each parameter one on the m4l device.
2. Values will jump to the value you'll click.

There's no patch/preset storage on the device (yet). So if you change something and like it, store it ON the MKS70/JX10 itself. 

This is currently the first public release (internal version 21), so there might be bugs! If you find one, please tell me! (open an "Issue" here on GitHub).

Future plans:
1. make it birectional with patch parsing, so that the shown values represent the actual values.
2. make it prettier and maybe do a popup version

Why did I build the device?
Because even though there are fantastic CTRLR panels out there (see 4, Prior Art), I cannot get those to work with Ableton Live as a VST, only stand-alone, and with that I cannot use hardware controllers.

Why is it Sysex based and not CC?
Because the Vecoven mod uses NRPN for the parameters and Ableton Live is imho not that good with NRPN, especially when it comes to automation.

PS: It might work with the JX8P with Vecoven mod (don't know, let me know)


Thank you so much to Fred Vecoven for providing the updated firmware in the first place and for helping me with the maddening (original) sysex implementation of the device!

How does it look like?
![mks70](https://github.com/markusschloesser/M4L_MKS-70/assets/59286549/de083e57-0b8c-412d-aafb-97e4aa84d185)

Prior Art / Further information:
1. http://llamamusic.com/super-jx/superjx.html HUGE resource
2. http://www.vecoven.com/superjx/superjx.html All this wouldn't be possible without Fred's mod, if you have a MKS70 or JX10, you should absolutely get the mod
3. https://gearspace.com/board/electronic-music-instruments-and-electronic-music-production/817800-roland-mks-70-upgrade-modification-beta-testers-wanted.html THE forum thread about the mod. You probably don't need to start in 2013 (page 1)
4. https://ctrlr.org/49160/  or https://roet32.wixsite.com/ctrlr/roland-superjx The CTRLR panel for Vecoven 4, by Possemo
