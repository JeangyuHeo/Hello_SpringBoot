## 간편하게 Spring boot로 프로젝트 만들자!

1. Spring boot [스타트 페이지](https://start.spring.io/)에 접속한다.

<img width="1209" alt="image" src="https://user-images.githubusercontent.com/88299729/194226947-a40cbc2d-5232-481d-ac25-fc2c1d06d948.png">

2. 프로젝트에 사용될 기술을 선택한 후에 'Generate'로 프로젝트를 생성한다.

* 프로젝트 형식 (Maven, Gradle)
* 언어 (Java, Kotlin, Groovy)
* 버전 (괄호가 있으면 정식 배포된 버전이 아닌 개발 중인 버전이다.)
* 프로젝트 명
  * Group: 회사 명
  * Artifact: 프로젝트 명

3. 생성된 프로젝트 파일 압축을 푼다.

4. IntelliJ를 실행시키고 'Open'을 선택한다.

5. 프로젝트 폴더 안에 'build.gradle' 파일을 선택한다.

6. src > main > java > 회사 명 > 프로젝트 명 > HelloSpringApplication을 실행시켜 'White label Error Page'가 뜨면 성공적으로 프로젝트를 생성한 것이다.

<br>

## 기본 프로젝트 구조

#### 1. src

* **main**
  * Java: 프로그램 소스 코드
  * 코드를 제외한 프로그램 실행에 필요한 파일들
    * e.x. 설정 파일, 이미지 파일 etc
* **test**
  * 테스트 코드와 관련된 소스 파일

<br>

#### 2. build.gradle

처음에 설정한 html을 만드는 템플릿 엔진