# AudioFetch Android SDK Library

This is the AudioFetch SDK Library for public consumption.

To include and use the library:

1.  Copy the libs/afaudiolib.aar to your project's libs folder.
2.  Add the following snippet to your repositories section of the app's build.gradle

```
repositories {
    mavenCentral()
    flatDir {
        dirs 'libs'
    }
}
```

3.  Add the following to the dependencies section of the app's build.gradle

```
dependencies {
    // audiofetch android SDK lib
    compile(name: 'afaudiolib', ext: 'aar')

    // required by above AudioFetch SDK lib
    compile 'com.android.support:support-annotations:23.+'
    compile 'com.squareup:otto:1.3.8'
    compile 'com.google.guava:guava:19.0'
}
```

See [documentation](AudioFetchSDKDocumentation_rev_1_0.pdf) and [javadoc documentation](https://github.com/audiofetch/audiofetch-android-sdk-public-library/tree/master/docs) and the [reference architecture app](https://github.com/audiofetch/audiofetch-android-sdk-sample) for more implementation details.
