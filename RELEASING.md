# How to publish a new version

1. Go to https://github.com/braekstudio/speedchecker-mnu-v2-releases/releases/new
2. **Tag**: `v` plus the version, for example `v2.0.1`.
3. **Title**: `SpeedChecker mnu v2 - 2.0.1`
4. **Description**: fill in the template below.
5. **Attach** the file `SpeedChecker mnu v2.apk`. Do not rename it.
6. Leave "Set as a pre-release" unticked, keep "Set as the latest release" ticked, then Publish.

The download page needs no change. Its button always gives the newest release.

Two things keep that working:

- The APK must have the same file name in every release (GitHub shows it as `SpeedChecker.mnu.v2.apk`).
- The release must not be a draft or a pre-release.

## Description template

```
What's new
- ...
- ...

For Android 7.0 or newer (64-bit phones). Download the APK below and open it to install.
```

## Description for the first release (v2.0.0)

```
First release of SpeedChecker mnu v2.

- Reads the RPM of a Mini 4WD motor through the phone's microphone
- Shows km/h for gears 3.5 / 3.7 / 4 / 4.2 / 5 and tires 24 / 26 / 31
- RPM and km/h converter
- Countdown timer with alarm

For Android 7.0 or newer (64-bit phones). Download the APK below and open it to install.
```
