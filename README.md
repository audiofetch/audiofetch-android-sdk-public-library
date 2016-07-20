# AudioFetch Android SDK Library

This is the AudioFetch SDK Library for public consumption.

To include and use the library:

1.  Copy the libs/afaudiolib.aar to your project's libs folder.
2.  Add the following snippet to your repositories section of the app's build.gradle

```
repositories {
	flatDir {
        dirs 'libs'
    }
}
```

3.  Add the following to the dependencies section of the app's build.gradle

```
dependencies {
	compile(name: 'afaudiolib', ext: 'aar')
}
```

See documentation and reference architecture app for more implementation details.
