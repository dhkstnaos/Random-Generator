# random-generator
랜덤 닉네임 생성기

## Maven pom.xml
Add JitPact repo
```
<repositories>
		<repository>
		    <id>jitpack.io</id>
		    <url>https://jitpack.io</url>
		</repository>
</repositories>
```
Add dependency
```
<dependency>
	    <groupId>com.github.dhkstnaos</groupId>
	    <artifactId>random-generator</artifactId>
	    <version>v0.0.1</version>
</dependency>
```

## Gradle build.gradle
Add JitPact repo
```
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
}
```
Add dependency
```
dependencies {
	    implementation 'com.github.dhkstnaos:random-generator:v0.0.1'
}
```

## HOW TO USE
```java
RandomGenerator.getCharterNickname("말파이트");
---------------------------------------------
Result = 뜨거운 말파이트
```
