# Code Citations

## License: MIT
https://github.com/RikkaApps/Shizuku-API/tree/01e08879d58a5cb11a333535c6ddce9f7b7c88ff/build.gradle

```
}

plugins {
    id 'com.android.application' version '8.0.2' apply false
    id 'com.android.library' version '8.0.2' apply false
    id 'org.jetbrains.kotlin.jvm' version '1.8.0' apply false
    alias libs.plugins.refine apply false
}
```


## License: MIT
https://github.com/skyskym30/Shizuku/tree/5fd74c83d9dcc8bc218f81370702641acd568801/build.gradle

```
' apply false
    id 'org.jetbrains.kotlin.jvm' version '1.8.0' apply false
    alias libs.plugins.refine apply false
}

allprojects {
    tasks.withType(Javadoc) {
        options.addStringOption('Xdoclint:none', '-quiet'
```


## License: unknown
https://github.com/RikkaW/flatbuffers-prefab/tree/276233079f3f220951698560263d39311f4e1af8/build.gradle

```
{
                            developer {
                                name = POM_DEVELOPER_NAME
                                url = POM_DEVELOPER_URL
                            }
                        }
                        scm {
                            connection = POM_SCM_CONNECTION
                            url = POM_SCM_URL
                        }
                    }
                }
            }
            repositories {
                maven {
                    name 'ossrh'
                    url 'https://s01.oss.sonatype.org/service/local/staging/deploy/maven2/
```


## License: unknown
https://github.com/vvb2060/BoringSSL_Android/tree/de8735c53875023ff25cd518a20c8ffdeaa44691/boringssl/build.gradle

```
}

        signing {
            def signingKey = findProperty("signingKey")
            def signingPassword = findProperty("signingPassword")
            def secretKeyRingFile = findProperty("signing.secretKeyRingFile")

            if (secretKeyRingFile != null && file(secretKeyRingFile).exists()) {
                sign publishing.publications
            }
```


## License: unknown
https://github.com/RohitVerma882/boringssl-prefab/tree/36778328e58e603030aa54130a5e0cf6b1b94edd/boringssl/build.gradle

```
signingPassword = findProperty("signingPassword")
            def secretKeyRingFile = findProperty("signing.secretKeyRingFile")

            if (secretKeyRingFile != null && file(secretKeyRingFile).exists()) {
                sign publishing.publications
            } else if (signingKey != null) {
                useInMemoryPgpKeys(signingKey,
```

