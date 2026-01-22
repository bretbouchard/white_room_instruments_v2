# White Room Instruments

Parent repository containing all White Room instrument plugins as git submodules.

## Instruments

This repository contains the following instruments as git submodules:

| Instrument | Repository | Description |
|------------|-----------|-------------|
| [Kane](./kane) | [kane-instrument](https://github.com/bretbouchard/kane-instrument) | Virtual Analog synthesizer |
| [Aether](./aether) | [aether-instrument](https://github.com/bretbouchard/aether-instrument) | Physical modeling atmosphere generator |
| [String](./string) | [string-instrument](https://github.com/bretbouchard/string-instrument) | Physical modeling string instrument |
| [NexSynth](./nex_synth) | [nex-synth-instrument](https://github.com/bretbouchard/nex-synth-instrument) | FM synthesis synthesizer |
| [Breath](./breath) | [breath-instrument](https://github.com/bretbouchard/breath-instrument) | Expressive monophonic breath instrument |
| [Motion](./motion) | [motion-instrument](https://github.com/bretbouchard/motion-instrument) | Motion-controlled instrument |
| [Nature](./nature) | [nature-instrument](https://github.com/bretbouchard/nature-instrument) | Nature sound generator |
| [LocalGal](./localgal) | [local-gal-instrument](https://github.com/bretbouchard/local-gal-instrument) | Local galactic instrument |
| [SamSampler](./sam_sampler) | [sam-sampler-instrument](https://github.com/bretbouchard/sam-sampler-instrument) | Sample playback instrument |
| [DrumMachine](./drum_machine) | [drum-machine-instrument](https://github.com/bretbouchard/drum-machine-instrument) | Drum machine |
| [Giants](./giants) | [giants-instrument](https://github.com/bretbouchard/giants-instrument) | Giant instrument collection |

## Cloning

To clone this repository with all submodules:

```bash
git clone --recurse-submodules https://github.com/bretbouchard/white_room_instruments.git
```

If you've already cloned without submodules:

```bash
git submodule update --init --recursive
```

## Integration with juce_backend

This repository is designed to be integrated into the juce_backend as a submodule:

```bash
cd /path/to/juce_backend
git submodule add https://github.com/bretbouchard/white_room_instruments.git instruments
git submodule update --init --recursive
```

## Plugin Formats

All instruments include complete plugin format support:

- ✅ AUv3 (Audio Unit v3 for macOS/iOS)
- ✅ VST3 (cross-platform)
- ✅ AU (Audio Unit v2 legacy)
- ✅ CLAP (modern cross-platform)
- ✅ Standalone (desktop application)
- ✅ DSP (headless implementation)
- ⚠️ LV2 (Linux) - placeholder

## Preset Format

All instruments use the **UPFS v1.0** (Universal Preset Format Specification) JSON format for presets.

## License

PROPRIETARY - All rights reserved

See individual instrument LICENSE files for details.

---

**White Room Instruments** - Professional audio instruments for creative music production.
