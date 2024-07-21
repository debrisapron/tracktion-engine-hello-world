# Tracktion Engine Hello World

I wanted a dead-simple, minimalist example of a [JUCE app](https://github.com/juce-framework/JUCE) with [Tracktion Engine](https://github.com/Tracktion/tracktion_engine) and couldn't find one, so I made one.

UPDATE 2024-07-21: Now uses TE v3.0! May be a bit wobbly as it's quite new. Use tag v2.1.0 if you want the previous version.

## DISCLAIMER

- I barely know what I'm doing, use at your own risk
- I've only tested on MacOS/Apple Silicon (but user @BaraMGB [got it working on Linux](https://github.com/debrisapron/tracktion-engine-hello-world/pull/1) 🙏)
- You need licenses to use [JUCE](https://juce.com/get-juce/) and [Tracktion Engine](https://engine.tracktion.com/)

## Prerequisites

- git duh
- [CMake](https://github.com/juce-framework/JUCE/tree/master?tab=readme-ov-file#cmake)
- [Other JUCE dependencies](https://github.com/juce-framework/JUCE/tree/master?tab=readme-ov-file#minimum-system-requirements)
- Windows users: I have no idea

## Instructions

```
git clone --recurse-submodules https://github.com/debrisapron/tracktion-engine-hello-world.git

cd tracktion-engine-hello-world

./build-and-run.sh
```

You will probably get a bunch of warnings, but if you're lucky then after a bunch of number-crunching you should hear a looping C major arpeggio. Hit ctrl-C to make it stop! Now make a DAW!
