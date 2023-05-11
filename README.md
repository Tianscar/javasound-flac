# Java Free Lossless Audio Codec
This is a fork of [JustFLAC](https://github.com/drogatkin/JustFLAC) and [JavaFlacEncoder](https://github.com/amplexus/java-flac-encoder).

This library contains a port of the Free Lossless Audio Codec (FLAC) decoder to Java and a FLAC encoder implemented in Java. It is designed to enable easy addition of FLAC support in Java applications.

## Add the library to your project (gradle)
1. Add the Maven Central repository (if not exist) to your build file:
```groovy
repositories {
    ...
    mavenCentral()
}
```

2. Add the dependency:
```groovy
dependencies {
    ...
    implementation 'com.tianscar.javasound:javasound-flac:1.4.0'
}
```

## Usage
[Tests and Examples](/src/test/java/org/kc7bfi/jflac/test)  
[Command-line interfaces](/src/test/java/org/kc7bfi/jflac/cli)

Note you need to download test audios [here](https://github.com/Tianscar/fbodemo1) and put them to /src/test/resources to run the test code properly!

## License
[LGPL-2.1](/LICENSE)
