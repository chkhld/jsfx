# jsfx
A free collection of JS (JesuSonic) plugins for [Reaper](https://www.reaper.fm/).

## Included effects
- [Correlation Meter](https://github.com/chkhld/jsfx/blob/master/plugins/correlation_meter.jsfx): Inspect your song's stereo phase balance and find mono-problematic areas by watching an indicator go red.
- [DC Offset](https://github.com/chkhld/jsfx/blob/master/plugins/dc_offset.jsfx): Adds constant 0 Hz content and shifts waveforms up or down, probably only useful to test DC filters.
- [Foldback Distortion](https://github.com/chkhld/jsfx/blob/master/plugins/foldback_distortion.jsfx): Folds waves between 0 and an adjustable ceiling, very harsh and nasty distortion.
- [Hard Clipper](https://github.com/chkhld/jsfx/blob/master/plugins/hard_clipper.jsfx): Simple and effective, chops away peaks above an adjustable ceiling volume, call it cold transistor distortion if you must.
- [Interpolated Noise](https://github.com/chkhld/jsfx/blob/master/plugins/interpolated_noise.jsfx): Various flavours of pleasingly natural and organically chaotic noise created with the help of various interpolation methods.
- [Phase Scope](https://github.com/chkhld/jsfx/blob/master/plugins/phase_scope.jsfx): Visualizes the stereo field of a signal, also commonly known as Goniometer, Vector Scope or Lissajous Display.
- [Signal Crusher](https://github.com/chkhld/jsfx/blob/master/plugins/signal_crusher.jsfx): Sample rate changes, reconstruction, bit reduction, bit dithering... it's all in here.
- [Soft Clipper](https://github.com/chkhld/jsfx/blob/master/plugins/soft_clipper.jsfx): Increasingly lowers signal peaks the closer they get to an adjustable ceiling volume, call it warm tube overdrive if you must.
- [Stereo Pan](https://github.com/chkhld/jsfx/blob/master/plugins/stereo_pan.jsfx): Utility that implements various standardized pan laws, as well as some custom methods by me.
- [Volume Range Trim](https://github.com/chkhld/jsfx/blob/master/plugins/volume_range_trim.jsfx): Fader to non-destrucively alter a signal's volume within a specific range (+/- 6, 12, 24, 48 dB), gives finer control when automating volume.
- [Volume Trim](https://github.com/chkhld/jsfx/blob/master/plugins/volume_trim.jsfx): Simple fader to alter a signal's volume, useful for gain-staging between plugins.

_(There may be more in the future)_

## Installation
- The important stuff is in the [plugins](https://github.com/chkhld/jsfx/blob/master/plugins/) folder, so download what you want from there, or [get the full release here](https://github.com/chkhld/jsfx/releases/).
- If you don't know what to do with these files, watch the [Reaper Blog tutorial](https://reaperblog.net/2015/06/quick-tip-how-to-install-js-plugins/) on how to install JS plugins.

## Support
This is just a fun project for me, I do this on the side to waste time or template C++ code, so don't expect too much of an effort. But if you find any bugs, or if you have any suggestions for improvements, feel free to report them in the [issue tracker](https://github.com/chkhld/jsfx/issues), I'll have a look there every now and then.

Have fun! <3
