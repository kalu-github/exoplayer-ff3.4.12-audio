#
#### step1
```
a => cd config
b => rm module.sh
c => ln -s module-lite.sh module.sh
d => cd ../
```

#
#### step2
```
a => ./init-android-ffmpeg
```

#
#### step3
```
a => cd android/contrib
b => compile-ffmpeg.sh clean
c => compile-ffmpeg.sh all
```

#
#### step3
```
External libraries providing hardware acceleration:

Libraries:
avcodec                 avutil                  swresample

Programs:

Enabled decoders:
alac                    amrwb                   mp3                     pcm_alaw                vorbis
amrnb                   flac                    opus                    pcm_mulaw

Enabled encoders:

Enabled hwaccels:

Enabled parsers:

Enabled demuxers:

Enabled muxers:

Enabled protocols:

Enabled filters:

Enabled bsfs:
null

Enabled indevs:

Enabled outdevs:
```