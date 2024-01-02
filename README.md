# BismuthServer💖
Custom Bismuth server jar built with Mixins! Built based on [VanillaMixins](https://github.com/Nessiesson/VanillaMixins) by [@Nessiesson](https://github.com/Nessiesson), using the Forge Team ForgeGradle server tweaker source code. Credits to all of the Forge(Gradle) Team for providing this amazing platform and Mumfrey for providing the Mixin library.

Further credits go to the the Carpetmod team (such as Xcom6000, gnembonMC, 2No2Name, et.,al.) who have provided some of the code used in this mod.

Not sure why I can't open issues on your repo but I received this error
```
* What went wrong:
A problem occurred configuring root project 'bismuth-server'.
> Could not resolve all files for configuration ':classpath'.
   > Could not resolve net.ornithemc:ploceus:1.3-SNAPSHOT.
     Required by:
         project : > ploceus:ploceus.gradle.plugin:1.3-SNAPSHOT:20231226.200101-22
      > No matching variant of net.ornithemc:ploceus:1.3-SNAPSHOT:20231226.200101-22 was found. The consumer was configured to find a library for use during runtime, compatible with Java 8, packaged as a jar, and its dependencies declared externally, as well as attribute 'org.gradle.plugin.api-version' with value '8.2' but:
          - Variant 'apiElements' capability net.ornithemc:ploceus:1.3-SNAPSHOT declares a library, packaged as a jar, and its dependencies declared externally:
              - Incompatible because this component declares a component for use during compile-time, compatible with Java 17 and the consumer needed a component for use during runtime, compatible with Java 8
              - Other compatible attribute:
                  - Doesn't say anything about org.gradle.plugin.api-version (required '8.2')
          - Variant 'runtimeElements' capability net.ornithemc:ploceus:1.3-SNAPSHOT declares a library for use during runtime, packaged as a jar, and its dependencies declared externally:
              - Incompatible because this component declares a component, compatible with Java 17 and the consumer needed a component, compatible with Java 8
              - Other compatible attribute:
                  - Doesn't say anything about org.gradle.plugin.api-version (required '8.2')
          - Variant 'sourcesElements' capability net.ornithemc:ploceus:1.3-SNAPSHOT declares a component for use during runtime, and its dependencies declared externally:
              - Incompatible because this component declares documentation and the consumer needed a library
              - Other compatible attributes:
                  - Doesn't say anything about its target Java version (required compatibility with Java 8)
                  - Doesn't say anything about its elements (required them packaged as a jar)
                  - Doesn't say anything about org.gradle.plugin.api-version (required '8.2')
```
