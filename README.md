# jsfx
A free collection of JS (JesuSonic) plugins for use in [Reaper](https://www.reaper.fm/).

## Included effects
- [DC Offset](https://github.com/chkhld/jsfx/blob/master/plugins/dc_offset): Adds constant 0 Hz content and shifts waveforms up or down, probably only useful to test DC filters.
- [Foldback Distortion](https://github.com/chkhld/jsfx/blob/master/plugins/foldback_distortion): Folds waves between 0 and an adjustable ceiling, very harsh and nasty distortion.
- [Hard Clipper](https://github.com/chkhld/jsfx/blob/master/plugins/hard_clipper): Simple and effective, chops away peaks above an adjustable ceiling volume, call it cold transistor distortion if you must.
- [Interpolated Noise](https://github.com/chkhld/jsfx/blob/master/plugins/interpolated_noise): Various flavours of pleasingly natural and organically chaotic noise created by interpolation.
- [Soft Clipper](https://github.com/chkhld/jsfx/blob/master/plugins/soft_clipper): Increasingly lowers signal peaks the closer they get to an adjustable ceiling volume, call it warm tube overdrive if you must.
- [Volume Range Trim](https://github.com/chkhld/jsfx/blob/master/plugins/volume_range_trim): Fader to non-destrucively alter a signal's volume within a specific range (+/- 6, 12, 24, 48 dB) for more controlled automation.
- [Volume Trim](https://github.com/chkhld/jsfx/blob/master/plugins/volume_trim): Simple fader to non-destructively alter a signal's volume between -48 dB and +48 dB, useful for gain-staging between plugins.

_(There may be more in the future)_

## Installation
- The important stuff is in the [plugins](https://github.com/chkhld/jsfx/blob/master/plugins/) folder, so download the files from there first.
- Watch the [Reaper Blog tutorial](https://reaperblog.net/2015/06/quick-tip-how-to-install-js-plugins/) on how to install JS plugins.

## Support
This is just a fun project for me, I do this on the side to waste time, so don't expect too much of an effort. They're pretty basic processors anyway, shouldn't require a lot of maintenance.

If you find any bugs, or if you have any suggestions for improvements, feel free to report them in the [issue tracker](https://github.com/chkhld/jsfx/issues), I'll have a look there every now and then.

Have fun!
