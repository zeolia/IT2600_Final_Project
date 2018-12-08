## Optimizing Audio Recording Quality
### Aaryn E Johns
---
##### This is a brief overview of the factors that come into considering when looking to achieve the highest quality audio recording possible when also considering storage space.

###### Meant for those working in audio often. e.g. Podcasters, musicians, audio engineers, filmmakers, radio hosts, et al.

---

##### For those that frequently work with audio, recording quality has a major influence on the end quality of the audio produced. Running into waveform clipping, key sounds not being picked up by the recording device, background noise, popping, etc. can all have negative effects on how a piece of audio is heard and interpreted.

Soundwaves captured through a digital recording device translate into bits of 1's and 0's in sequence.  This captured digital sound is characterized by sample rate and bit depth.

### Sample Rate

A sample is a value or set of values at a point in time. In the case of converting from physical soundwaves to digital waveforms, a sample is a representation of sound produced at different snapshots in time. The more snapshots you have, the more accurate the playback is.

For example, say that a physical soundwave is abcdefghijklmnopqrstuvwxyz, with each letter 'playing' after each other in succession. A low sample rate may only return aeimquy. This playback would be choppy and hardly representative of the entire sound intended to be conveyed. A higher sample rate may return acegikmoqsuwy, in which case the gist is closer to being understood, but is still not ideal. However, a higher sample rate will return the full abcdefghijklmnopqrstuvwxyz and communicate fully all sounds made and necessary. 

It's also important to consider the range of human hearing. The frequency range humans can hear is 20-20,000 Hz. Most people can’t hear the extremes of the range, but that range is often quoted as the hearing range of humans on average. To ensure that the full spectrum of human hearing is covered, sounds are typically sampled at 44.1 kHz, 48 kHz, 88.2 kHz, or 96 kHz. 44.1 kHz is more than twice that of human hearing, to ensure that all frequencies are captured. Any more than 44.1 kHz is going to result in an objectively higher quality waveform, but with subjective increase in quality to human ears. 

### Bit Depth

The quality of the audio depends on both the sample rate and the bit depth, however. Bit depth is the number of bits, or 1's and 0's, that make up the information in each sample. Using higher bit depths during studio recording accommodates and results in greater dynamic ranges. If a signal's dynamic range is lower than that the bit depth made room for, then the recording has what's called headroom. The higher the bit depth, the more headroom that's available. This headroom reduces the risk of waveform clipping without recording errors at lower volumes. Increasing both the sample rate and the bit depth is going to result in a file whose playback is closer to the physical soundwave that produced it in the first place.

### Storage Needs

Now, with more samples being recorded every second with more detail to those samples by the bit rate, the amount of information being gathered for every second of audio is increased. Balancing quality of audio to storage available is an important decision to make.

For an hour of mono audio recorded at 44.1 kHz with 16 bit depth,

44100 samples/second * 16 bits/sample * 3600 sec/hr = 2540160000 bits = 317520000 bytes = 302.8107 megabytes

If recording in stereo, that number double to 605.6213 megabytes.

If you're storing hours of audio at high sample/bit rates, the amount of storage you'll need goes up significantly. Make sure that you have ample storage for all audio files as well as the metadata that is often tied to those files.

### Compression

Audio compression can be an aid in dealing with storage space. There's lossy and lossless compression. The acceptable trade-off between loss of audio quality and transmission or storage size depends upon the application. For example, one 640 MB compact disc (CD) holds approximately one hour of uncompressed high fidelity music, less than 2 hours of music compressed losslessly, or 7 hours of music compressed in the MP3 format at a medium bit rate. A digital sound recorder can typically store around 200 hours of clearly intelligible speech in 640 MB.

Lossy compression typically achieves far greater compression than lossless compression (data of 5 percent to 20 percent of the original stream, rather than 50 percent to 60 percent), by discarding less-critical data. Most lossy compression reduces perceptual redundancy by first identifying perceptually irrelevant sounds, that is, sounds that are very hard to hear. Typical examples include high frequencies or sounds that occur at the same time as louder sounds. Those sounds are coded with decreased accuracy or not at all. Due to the nature of lossy algorithms, audio quality suffers when a file is decompressed and recompressed. This makes lossy compression unsuitable for storing the intermediate results in professional audio engineering applications, such as sound editing and multitrack recording. However, they are very popular with end users (particularly MP3) as a megabyte can store about a minute's worth of music at adequate quality.

Lossless audio compression produces a representation of digital data that decompress to an exact digital duplicate of the original audio stream. Using lossless reduces file size by 50-60%. This method is unable to attain high compression ratios due to the complexity of waveforms and the rapid changes in sound forms.

If storage space is a challenge, lossy may be necessary. But if quality is your goal, aim for lossless compression techniques.

### File formats

#### Uncompressed

* WAV
* AIFF
* AU 
* Raw header-less PCM

Uncompressed file formats are the highest quality waveforms that can be stored, at the expense of storage space. Since WAV and AIFF are widely supported and can store LPCM, they are suitable file formats for storing and archiving an original recording.

#### Lossless compressed

* FLAC
* Monkey's Audio (filename extension .ape)
* WavPack (filename extension .wv)
* TTA
* ATRAC Advanced Lossless, ALAC (filename extension .m4a)
* MPEG-4 SLS
* MPEG-4 ALS
* MPEG-4 DST
* Windows Media Audio Lossless (WMA Lossless)
* Shorten (SHN)

A lossless compressed format stores data in less space without losing any information. The original, uncompressed data can be recreated from the compressed version.

Uncompressed audio formats encode both sound and silence with the same number of bits per unit of time. Encoding an uncompressed minute of absolute silence produces a file of the same size as encoding an uncompressed minute of music. In a lossless compressed format, however, the music would occupy a smaller file than an uncompressed format and the silence would take up almost no space at all.

#### Lossy compressed

*  Opus
* MP3
* Vorbis
* Musepack
* AAC
* ATRAC
* Windows Media Audio Lossy (WMA lossy)

This method results in a reduction in audio quality, but a variety of techniques are used, mainly by exploiting psychoacoustics, to remove the parts of the sound that have the least effect on perceived quality, and to minimize the amount of audible noise added during the process. The popular MP3 format is probably the best-known example, but the AAC format found on the iTunes Music Store is also common. Most formats offer a range of degrees of compression, generally measured in bit rate. The lower the rate, the smaller the file and the more significant the quality loss.

---

For each individual creator, a balance of sample rate, bit depth, file format, and choice of whether/how to compress audio will result in differences of quality based on the product aimed to be created. Whether you're solely recording the human voice, which requires less accurate sampling/bit depth in order to be understood, or a symphony orchestra, where each nuance of sound influences the entire duration of audio, deciding what settings and techniques you use will make your recording unique and possibly even recognizable.

---
###### 2018, Aaryn Johns, they/them pronouns only
