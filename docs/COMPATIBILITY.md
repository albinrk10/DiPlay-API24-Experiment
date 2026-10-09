# Compatibility

> **Experimental fork branch: Android 7.0 / API 24.** This branch lowers the main mobile app's minimum Android API. The contributor reports that the app connected and worked in one aftermarket head unit; its system information screen displayed Android 12, so that test does not confirm compatibility with genuine Android 7.0 hardware. Hardware and firmware compatibility remain experimental.

| Area | Current scope |
| --- | --- |
| Head unit | Main mobile APK declares minimum API 24 (Android 7.0). A successful launch on API 24 does not guarantee CarPlay connection or compatibility with every vendor-modified Android build. |
| Reported vehicle test | Contributor reports wired/wireless CarPlay working on one aftermarket head unit. The unit reported Android 12, CPU 8239, CAR AUDIO J7.3.7 and MCU 4.0; actual Android API level was not independently verified. |
| Android 7.0 test | Not verified on a device confirmed to run Android 7.0 / API 24. |
| Phone | Standard, non-jailbroken iPhone with CarPlay enabled; device/iOS compatibility varies. |
| Other cars | No certified model or firmware support list; results from one head unit do not establish general support. |
| Scope | API 24 compatibility changes target the main mobile app and shared libraries. The separate automotive sample retains its own platform requirements. |

This branch is an unofficial experiment based on DiPlay. It is not an Apple-certified CarPlay accessory or a guarantee of compatibility. See [README](../README.md) for build and project information.
