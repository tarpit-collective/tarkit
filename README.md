# sound-tools
A collection of utilities for music & sound production on the terminal.

## tools

### psalm-puller
> A one-shot sample recorder tool

A tool for recording one-shot samples and dumping them to files in bulk. The idea is you can prime the application for recording and when it detects audio, it can start recording (maybe including some lookback to ensure a clean start) until the audio level returns to the noise floor. Once done, the sample is dumped to disk and you can prime the recorder again for more samples. Ideally, it would be useful as a tool for recording sample packs of drums and SFX.

### midi-thing
> MIDI manipulation REPL

Manipulate and transform MIDI messages as they pass through the tool. Allows for remapping channels, randomising velocity, shifting octaves and more. Since it's a REPL, you can make it do whatever you want.
