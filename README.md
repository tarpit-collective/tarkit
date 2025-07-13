# tarkit
A selection of useful tools.

## overview

## tools

### tabdropper
> TB-303 pattern generator

### psalmpuller
> A one-shot sample recorder tool

A tool for recording one-shot samples and dumping them to files in bulk. The idea is you can prime the application for recording and when it detects audio, it can start recording (maybe including some lookback to ensure a clean start) until the audio level returns to the noise floor. Once done, the sample is dumped to disk and you can prime the recorder again for more samples. Ideally, it would be useful as a tool for recording sample packs of drums and SFX.

### midi-thing
> MIDI manipulation REPL

Manipulate and transform MIDI messages as they pass through the tool. Allows for remapping channels, randomising velocity, shifting octaves and more. Since it's a REPL, you can make it do whatever you want.

### spag
> Automatically route MIDI connections given a list of devices and their ports.

Optimises a network of devices to use the least amount of connections possible.
