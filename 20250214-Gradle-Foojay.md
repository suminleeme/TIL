# 20250214-Gradle-전역 jdk 설정
- https://docs.gradle.org/current/userguide/toolchains.html#sec:provisioning
- gradle 문서에서 보면 setting.gradle에 foojay (Foojay, (Friends of OpenJDK)) 플러그인을 설정하면, 루트 build.gralde에 설정한 jdk버전이 없을 시 다운로드 하게 할 수 있음
- foojay란
  * 무료 OpenJDK 빌드를 제공하는 Java 플랫폼
  * Gradle은 Foojay를 통해 필요한 JDK가 없으면 자동으로 다운로드하고 적용
