# psalm-puller
A one-shot sample recorder tool

### Concept
A tool for recording one-shot samples and dumping them to files in bulk. The idea is you can prime the application for recording and when it detects audio, it can start recording (maybe including some lookback to ensure a clean start) until the audio level returns to the noise floor. Once done, the sample is dumped to disk and you can prime the recorder again for more samples. Ideally, it would be useful as a tool for recording sample packs of drums and SFX.
