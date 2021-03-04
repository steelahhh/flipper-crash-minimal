# flipper-crash-minimal

AGP: 7.0.0-alpha08, JDK: 11

```
FATAL EXCEPTION: FlipperConnectionThread
Process: dev.steelahhh.flipper_crash, PID: 18442
java.lang.NoClassDefFoundError: <clinit> failed for class com.facebook.flipper.android.EventBase; see exception in other thread
at com.facebook.flipper.android.FlipperThread.run(FlipperThread.java:25)
FATAL EXCEPTION: FlipperEventBaseThread
Process: dev.steelahhh.flipper_crash, PID: 18442
java.lang.UnsatisfiedLinkError: couldn't find DSO to load: libfbjni.so
SoSource 0: com.facebook.soloader.ApkSoSource[root = /data/data/dev.steelahhh.flipper_crash/lib-main flags = 1]
SoSource 1: com.facebook.soloader.DirectorySoSource[root = /data/app/~~GoFK8nwW7k_10Ft51ORTRg==/dev.steelahhh.flipper_crash-qhY6HQrK9QYOeP8W3G-y2A==/lib/arm64 flags = 0]
SoSource 2: com.facebook.soloader.DirectorySoSource[root = /vendor/lib64 flags = 2]
SoSource 3: com.facebook.soloader.DirectorySoSource[root = /system/lib64 flags = 2]
Native lib dir: /data/app/~~GoFK8nwW7k_10Ft51ORTRg==/dev.steelahhh.flipper_crash-qhY6HQrK9QYOeP8W3G-y2A==/lib/arm64
result: 0
at com.facebook.soloader.SoLoader.doLoadLibraryBySoName(SoLoader.java:918)
at com.facebook.soloader.SoLoader.loadLibraryBySoNameImpl(SoLoader.java:740)
at com.facebook.soloader.SoLoader.loadLibraryBySoName(SoLoader.java:654)
at com.facebook.soloader.SoLoader.loadLibrary(SoLoader.java:634)
at com.facebook.soloader.NativeLoaderToSoLoaderDelegate.loadLibrary(NativeLoaderToSoLoaderDelegate.java:29)
at com.facebook.soloader.nativeloader.NativeLoader.loadLibrary(NativeLoader.java:51)
at com.facebook.soloader.nativeloader.NativeLoader.loadLibrary(NativeLoader.java:30)
at com.facebook.jni.HybridData.<clinit>(HybridData.java:34)
at com.facebook.flipper.android.FlipperThread.run(FlipperThread.java:25)
```
