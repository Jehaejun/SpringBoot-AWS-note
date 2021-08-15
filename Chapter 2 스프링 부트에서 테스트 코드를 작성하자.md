# Chapter 2 스프링 부트에서 테스트 코드를 작성하자



| variable amount not initialized in the default constructor   |
| ------------------------------------------------------------ |
| https://deeplify.dev/back-end/spring/lombok-required-args-constructor-initialize-error |

Gradle 5.x 미만

```
dependencies {
  implementation 'org.projectlombok:lombok'
}
```

Gradle 5.x 이상

```
dependencies {
  compileOnly 'org.projectlombok:lombok'
  annotationProcessor 'org.projectlombok:lombok'
}
```

