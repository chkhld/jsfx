# chokehold JSFX
This page is an index of all my currently published JSFX plugins, including screenshots and short descriptions.<br>
[<< Back to ReadMe](./README.md)
<br>
<br>

## Categories
[Clipper](#clipper)<br>
[Distortion](#distortion)<br>
[Dynamics](#dynamics)<br>
[Equalizer](#equalizer)<br>
[Filter](#filter)<br>
[FX](#fx)<br>
[Generator](#generator)<br>
[Instrument FX](#instrument-fx)<br>
[Lo-Fi](#lo-fi)<br>
[Metering](#metering)<br>
[MIDI](#midi)<br>
[Noise](#noise)<br>
[Stereo](#stereo)<br>
[Utility](#utility)<br>

&nbsp;

<a name="clipper"></a>
## Clipper
| Screenshot | Plugin | Description |
| ---------- | ------ | ----------- |
| <a name="hard-clipper"></a>[![hard_clipper](./assets/thumbnails/hard_clipper.jpg)](./assets/screenshots/hard_clipper.png) | [Hard Clipper](./Clipper/hard_clipper.jsfx) | Simple and effective, chops away peaks above an adjustable ceiling volume, call it cold transistor distortion if you must. |
| <a name="knee-clipper"></a>[![knee_clipper](./assets/thumbnails/knee_clipper.jpg)](./assets/screenshots/knee_clipper.png) | [Knee Clipper](./Clipper/knee_clipper.jsfx) | A clipper neither purely hard nor purely soft, and yet a unification of both. |
| <a name="sine-clipper"></a>[![sine_clipper](./assets/thumbnails/sine_clipper.jpg)](./assets/screenshots/sine_clipper.png) | [Sine Clipper](./Clipper/sine_clipper.jsfx) | A clipper that uses the smoothness of the sine wave to tame loud signal peaks. |
| <a name="soft-clipper"></a>[![soft_clipper](./assets/thumbnails/soft_clipper.jpg)](./assets/screenshots/soft_clipper.png) | [Soft Clipper](./Clipper/soft_clipper.jsfx) | Increasingly lowers signal peaks the closer they get to an adjustable ceiling volume, call it warm tube overdrive if you must. Has up to 16x oversampling, DC blocker and optional final (non oversampled) hard clipping stage for true 0 dBfs output. |
| <a name="staging-clipper"></a>[![staging_clipper](./assets/thumbnails/staging_clipper.jpg)](./assets/screenshots/staging_clipper.png) | [Staging Clipper](./Clipper/staging_clipper.jsfx) | A clipper that automatically compensates for the ceiling, useful for leveling. |
<br>

<a name="distortion"></a>
## Distortion
| Screenshot | Plugin | Description |
| ---------- | ------ | ----------- |
| <a name="foldback-distortion"></a>[![foldback_distortion](./assets/thumbnails/foldback_distortion.jpg)](./assets/screenshots/foldback_distortion.png) | [Foldback Distortion](./Distortion/foldback_distortion.jsfx) | Folds waves between 0 and an adjustable ceiling, very harsh and nasty distortion. |
<br>

<a name="dynamics"></a>
## Dynamics
| Screenshot | Plugin | Description |
| ---------- | ------ | ----------- |
| <a name="bus-comp"></a>[![bus_comp](./assets/thumbnails/bus_comp.jpg)](./assets/screenshots/bus_comp.png) | [Bus Comp](./Dynamics/bus_comp.jsfx) | Submix bus oriented compressor with automatic/program-dependent release, fadeable stereo linking, Mid/Side mode, external sidechain input with high pass filter, instability noise, dynamic saturation, optional output hard clipping and dry/wet mix for parallel compression. |
| <a name="consolidator"></a>[![consolidator](./assets/thumbnails/consolidator.jpg)](./assets/screenshots/consolidator.png) | [Consolidator](./Dynamics/consolidator.jsfx) | A set of 3 compressors with sidechain filter and stereo linking chained in a row, each with its own character. Has a dry/wet mix parameter for instant parallel/NY compression and Mid/Side mode. |
| <a name="gate-expander"></a>[![gate_expander](./assets/thumbnails/gate_expander.jpg)](./assets/screenshots/gate_expander.png) | [Gate/Expander](./Dynamics/gate_expander.jsfx) | Several channel routings, external sidechain, sidechain filter, fadeable stereo linking, hysteresis, and it can be switched between gate (fades to silence) and expander (fades to defined volume) modes. |
| <a name="track-comp"></a>[![track_comp](./assets/thumbnails/track_comp.jpg)](./assets/screenshots/track_comp.png) | [Track Comp](./Dynamics/track_comp.jsfx) | A low-CPU and ultra-flexible compressor, with everything from peak/RMS detection over feed-forward/-back modes, stereo linking and channel setups to automatic gain compensation and dynamic saturation. |
<br>

<a name="equalizer"></a>
## Equalizer
| Screenshot | Plugin | Description |
| ---------- | ------ | ----------- |
| <a name="eq-560"></a>[![eq_560](./assets/thumbnails/eq_560.jpg)](./assets/screenshots/eq_560.png) | [EQ 560](./Equalizer/eq_560.jsfx) | Classic American 10-band graphic console equalizer. Limited flexibility, fast and streamlined workflow. Uses 2x oversampling for accurate high frequency filter curves, adds some character. |
<br>

<a name="filter"></a>
## Filter
| Screenshot | Plugin | Description |
| ---------- | ------ | ----------- |
| <a name="dc-filter"></a> No UI | [DC Filter](./Filter/dc_filter.jsfx) | Multi-channel capable and extremely narrow DC offset removal filter. |
<br>

<a name="fx"></a>
## FX
| Screenshot | Plugin | Description |
| ---------- | ------ | ----------- |
| <a name="filthy-delay"></a>[![filthy_delay](./assets/thumbnails/filthy_delay.jpg)](./assets/screenshots/filthy_delay.png) | [Filthy Delay](./FX/filthy_delay.jsfx) | Stereo delay with multiple routings (currently: stereo, inverted, ping-pong, mono), plus optional filters, boostable saturation and downsampling degradation in the feedback path. |
| <a name="ring-mod"></a>[![ring_mod](./assets/thumbnails/ring_mod.jpg)](./assets/screenshots/ring_mod.png) | [Ring Mod](./FX/ring_mod.jsfx) | Multiplies the input signal with a carrier signal, which can lead to all sorts of warbly modulation and distortion effects. |
<br>

<a name="generator"></a>
## Generator
| Screenshot | Plugin | Description |
| ---------- | ------ | ----------- |
| <a name="test-signals"></a>[![test_signals](./assets/thumbnails/test_signals.jpg)](./assets/screenshots/test_signals.png) | [Test Signals](./Generator/test_signals.jsfx) | A collection of 13 different test tone and noise generators in one plugin, 14 if you count silence. Can have a different generator on each channel, can output both or just one channel, can sum both channels. |
<br>

<a name="instrument-fx"></a>
## Instrument FX
| Screenshot | Plugin | Description |
| ---------- | ------ | ----------- |
| <a name="amp-sim"></a>[![amp_sim](./assets/thumbnails/amp_sim.jpg)](./assets/screenshots/amp_sim.png) | [Amp Sim](./Instrument%20FX/amp_sim.jsfx) | Guitar and bass amplifier with up to 16x oversampling, mono/stereo routings, pre/post/triggered noise gate, booster pedal function, interactive inter-stage EQ bands, dynamic Depth and Presence bands, and maximizer. |
| <a name="bass-squeezer"></a>[![bass_squeezer](./assets/thumbnails/bass_squeezer.jpg)](./assets/screenshots/bass_squeezer.png) | [Bass Squeezer](./Instrument%20FX/bass_squeezer.jsfx) | Split-band compression and filtered distortion for that instant bathtub bass sound. |
| <a name="cabinet-sim"></a>[![cabinet_sim](./assets/thumbnails/cabinet_sim.jpg)](./assets/screenshots/cabinet_sim.png) | [Cabinet Sim](./Instrument%20FX/cabinet_sim.jsfx) | Simple cabinet sim with 5 burnt-in impulse responses, 4 for guitar and 1 for bass. Can **not** load IRs from file. |
| <a name="chug-thug"></a>[![chug_thug](./assets/thumbnails/chug_thug.jpg)](./assets/screenshots/chug_thug.png) | [Chug Thug](./Instrument%20FX/chug_thug.jsfx) | Simplified split-band processor to tame the low end of distorted guitars when palm muting. |
| <a name="mic-combiner"></a>[![mic_combiner](./assets/thumbnails/mic_combiner.jpg)](./assets/screenshots/mic_combiner.png) | [Mic Combiner](./Instrument%20FX/mic_combiner.jsfx) | Utility to facilitate the process of merging two mono microphone signals into one. Processes each microphone signal individually, allows to set a balance/mix between both microphones, and sums them to mono. Can adjust timing between signals. |
<br>

<a name="lo-fi"></a>
## Lo-Fi
| Screenshot | Plugin | Description |
| ---------- | ------ | ----------- |
| <a name="signal-crusher"></a>[![signal_crusher](./assets/thumbnails/signal_crusher.jpg)](./assets/screenshots/signal_crusher.png) | [Signal Crusher](./Lo-Fi/signal_crusher.jsfx) | Sample rate changes, lost sample reconstruction, bit truncation, bit dithering... it's all in here. |
| <a name="telephone"></a>[![telephone](./assets/thumbnails/telephone.jpg)](./assets/screenshots/telephone.png) | [Telephone](./Lo-Fi/telephone.jsfx) | Makes vocals sound like they're coming through a phone receiver, also worth slamming on drums. |
<br>

<a name="metering"></a>
## Metering
| Screenshot | Plugin | Description |
| ---------- | ------ | ----------- |
| <a name="correlation-meter"></a>[![correlation_meter](./assets/thumbnails/correlation_meter.jpg)](./assets/screenshots/correlation_meter.png) | [Correlation Meter](./Metering/correlation_meter.jsfx) | Inspect your song's stereo phase balance and find mono-problematic areas by watching an indicator go red. |
| <a name="phase-scope"></a>[![phase_scope](./assets/thumbnails/phase_scope.jpg)](./assets/screenshots/phase_scope.png) | [Phase Scope](./Metering/phase_scope.jsfx) | Visualizes the stereo field of a signal, also commonly known as Goniometer, Vector Scope or Lissajous. Selectable visualization colour and optional freeze-on-pause function. |
| <a name="stereo-checker"></a>[![stereo_checker](./assets/thumbnails/stereo_checker.jpg)](./assets/screenshots/stereo_checker.png) | [Stereo Checker](./Metering/stereo_checker.jsfx) | Displays the inter-channel relation of a two-channel input signal. |
| <a name="wave-scope"></a>[![wave_scope](./assets/thumbnails/wave_scope.jpg)](./assets/screenshots/wave_scope.png) | [Wave Scope](./Metering/wave_scope.jsfx) | Waveform display that can visualize various mono/stereo channel streams as Decibels, signed or absolute samples. With fadeable colours and freeze-on-pause function. |
<br>

<a name="midi"></a>
## MIDI
| Screenshot | Plugin | Description |
| ---------- | ------ | ----------- |
| <a name="midi-chord-trigger"></a>[![midi_chord_trigger](./assets/thumbnails/midi_chord_trigger.jpg)](./assets/screenshots/midi_chord_trigger.png) | [MIDI Chord Trigger](./MIDI/midi_chord_trigger.jsfx) | Press one MIDI key to play a chord. Has 12 pre-selectable chord slots, uses one MIDI octave to switch them, uses one MIDI octave to switch in which MIDI octave the chord will be played, uses one MIDI octave to pick a root note and actually play the chord. Great help for background piano and orchestral ensembles. |
<br>

<a name="noise"></a>
## Noise
| Screenshot | Plugin | Description |
| ---------- | ------ | ----------- |
| <a name="interpolated-noise"></a>[![interpolated_noise](./assets/thumbnails/interpolated_noise.jpg)](./assets/screenshots/interpolated_noise.png) | [Interpolated Noise](./Noise/interpolated_noise.jsfx) | Various flavours of pleasingly natural and organically chaotic noise created with the help of various interpolation methods. |
| <a name="reference-noise"></a>[![reference_noise](./assets/thumbnails/reference_noise.jpg)](./assets/screenshots/reference_noise.png) | [Reference Noise](./Noise/reference_noise.jsfx) | Provides various noise profiles, filtered or plain, to use as target reference for spectral/visual mixing. |
<br>

<a name="stereo"></a>
## Stereo
| Screenshot | Plugin | Description |
| ---------- | ------ | ----------- |
| <a name="m-s-fader"></a>[![m-s_fader](./assets/thumbnails/m-s_fader.jpg)](./assets/screenshots/m-s_fader.png) | [M-S Fader](./Stereo/m-s_fader.jsfx) | Converts a stereo source to a Mid/Side signal and then fades between 100% Mid and 100% Side signal, or a mix of both. Great to remove the center signal, or to focus in on it. |
| <a name="stereo-bleed-remover"></a>[![stereo_bleed_remover](./assets/thumbnails/stereo_bleed_remover.jpg)](./assets/screenshots/stereo_bleed_remover.png) | [Stereo Bleed Remover](./Stereo/stereo_bleed_remover.jsfx) | An attempt at removing unwanted bleed between channels in a stereo signal. |
| <a name="stereo-pan"></a>[![stereo_pan](./assets/thumbnails/stereo_pan.jpg)](./assets/screenshots/stereo_pan.png) | [Stereo Pan](./Stereo/stereo_pan.jsfx) | Utility that implements various standardized pan laws, as well as some custom methods by me. |
<br>

<a name="utility"></a>
## Utility
| Screenshot | Plugin | Description |
| ---------- | ------ | ----------- |
| <a name="dc-offset"></a>[![dc_offset](./assets/thumbnails/dc_offset.jpg)](./assets/screenshots/dc_offset.png) | [DC Offset](./Utility/dc_offset.jsfx) | Adds constant 0 Hz content to all channels of a signal and shifts waveforms up or down, probably only useful to test DC filters. |
| <a name="impulse-generator"></a>[![impulse_generator](./assets/thumbnails/impulse_generator.jpg)](./assets/screenshots/impulse_generator.png) | [Impulse Generator](./Utility/impulse_generator.jsfx) | Generates a 1-sample impulse when triggered, for use when sampling devices to IRs. |
| <a name="volume-range-trim"></a>[![volume_range_trim](./assets/thumbnails/volume_range_trim.jpg)](./assets/screenshots/volume_range_trim.png) | [Volume Range Trim](./Utility/volume_range_trim.jsfx) | Fader to non-destructively alter a signal's volume within a specific range (+/- 6, 12, 24, 48 dB), gives finer control when automating volume. Auto-adapts to track's channel count. |
| <a name="volume-trim"></a>[![volume_trim](./assets/thumbnails/volume_trim.jpg)](./assets/screenshots/volume_trim.png) | [Volume Trim](./Utility/volume_trim.jsfx) | Simple fader to alter a signal's volume, useful for gain-staging between plugins. Auto-adapts to track's channel count. |
<br>

_(There may be more in the future)_
