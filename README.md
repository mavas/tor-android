
## Tor Android

This is native Android `TorService` built on the Tor shared library built for
Android.  The included _libtor.so_ binaries can also be used directly as a tor
daemon.  Binaries are available on Maven Central:

```gradle
dependencies {
    implementation 'info.guardianproject:tor-android:0.4.7.11'
    implementation 'info.guardianproject:jtorctl:0.4.5.7'
}
```

## How to Build

Please see: https://raw.githubusercontent.com/guardianproject/tor-android/master/BUILD

This can be built reproducibly using the included Vagrant VM setup.  That will
run with either _libvirt_ or VirtualBox.  The provisioning is based on the
"release" job in _.gitlab-ci.yml_.
