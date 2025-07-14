# FFmpegKit

`FFmpegKit` is a collection of tools to use `FFmpeg` in `Android`, `iOS`, `Linux`, `macOS`, `tvOS`, `Flutter` and `React Native` applications.

It includes scripts to build `FFmpeg` native libraries, a wrapper library to run `FFmpeg`/`FFprobe` commands in applications.

## Build pre-steps

Export environment variables:

```bash
export ANDROID_SDK_ROOT="/Users/USER/Android/SDK"
export ANDROID_NDK_ROOT="/Users/USER/Android/SDK/ndk/VERSION"
```

## Building native

```bash
sh android.sh
```

```bash
sh ios.sh
```

and so on.

## Finale

Integrate into your platform (native, react-native, etc).
