![Gradle](https://upload.wikimedia.org/wikipedia/commons/thumb/c/cb/Gradle_logo.png/330px-Gradle_logo.png)
# java-Gradle
###### exercise example project with java build tool Gradle
###### [Gradle OpenSource](https://github.com/gradle/gradle)

# What is Gradle ?
- Groovy를 기반으로 한 DSL(Domain Specific Language) 자동화 build tool. <details><summary>DSL ?</summary> 도메인 특화 언어(Domain-specific language)는 특정한 도메인을 적용하는데 특화된 컴퓨터 언어이다. 이는 어느 도메인에서나 적용 가능한 범용 언어(General-purpose language)와는 반대되는 개념이다. 도메인 특화 언어에는 매우 넓은 다양성이 존재한다.</details>
- xml 기반이 아닌 JVM에서 동작하며, java 언어를 지원한다.
- 'Gradle Wrapper' 를 이용하여 Gradle을 설치하지 않은 시스템에도 빌드가 가능하다.
- Maven의 pom.xml을 Gradle용으로 변환 가능하며, Maven의 중앙 저장소도 지원하기에 Library를 모두 그대로 사용이 가능하다.
- 의존 Library들을 자동으로 설치하여 가져오기 때문에 사용이 편리하다. (Externel Dependencies) (ex tomcat Library가 미리 설치되어있기 때문에 따로 설치하지 않아도 임시 서버를 킬 수가 있다.) (ex logback + slf4j 와 같은 로깅 라이브러리, test를 위한 JUnit, spring-test 라이브러리도 자동 설치)
- 
