# libVLC-Player

Simple libVLC Player

Use this endpoint for testing

```sh
rtsp://wowzaec2demo.streamlock.net/vod/mp4:BigBuckBunny_115k.mov
```

Compile only VLC (version 2.5.14)

```sh
    allprojects {
        repositories {
            maven { url 'https://jitpack.io' }
        }
    }
    dependencies {
        compile 'com.github.duartepatriani.libVLC-Player:libvlc:1.0'
    }
```

References:

https://github.com/disono/libVLC-Player by [@disono](https://github.com/disono)
