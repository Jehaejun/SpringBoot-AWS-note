# Chapter 1 인텔리제이로 스프링부트 시작하기



| **No candidates found for method call compile**<br/>**Could not find method compile() for arguments** |
| ------------------------------------------------------------ |
| https://stackoverflow.com/questions/23796404/could-not-find-method-compile-for-arguments-gradle <br/><br/>Note that the compile, runtime, testCompile, and testRuntime configurations introduced by the Java plugin have been deprecated since Gradle 4.10 (Aug 27, 2018),  and were finally removed in Gradle 7.0 (Apr 9, 2021). The aforementioned configurations should be replaced by implementation, runtimeOnly, testImplementation, and testRuntimeOnly, respectively.<br/><br/>Gradle 4.10 (Aug 27, 2018)<br/>compile -> implementation 대체<br/>Gradle 7.0 (Apr 9, 2021<br/>compile 삭제 |

****

| JCenter deprecation                                          |
| ------------------------------------------------------------ |
| https://stackoverflow.com/questions/23523831/gradle-build-fail-process-gradle-test-executor-1-finished-with-non-zero-exit<br/>https://blog.gradle.org/jcenter-shutdown<br/><br/>*Gradle 7.0* 은 `jcenter()`종속성을 해결하기 위해 의 사용을 더 이상 사용하지 않습니다 . *JCenter* 를 리포지토리로 계속 사용할 수 있지만 Gradle은 경고를 표시합니다. |

