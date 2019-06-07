# Uploading-Files

스프링 부트를 이용한 File Upload 공부

[코드참조](https://spring.io/guides/gs/uploading-files/)

- `java.nio.file.Path`
  - IO는 파일의 속성 정보를 읽기 위해 File 클래스를 제공
  - NIO는 좀 더 다양한 파일의 속성 정보를 제공해주는 클래스, 인터페이스를 `java.nio.file` 패키지에서 제공
  - Path는 IO의 `java.io.file` 클래스에 대응하는 NIO 인터페이스이다
  - Path 구현 객체는 `java.nio.file.Paths` 클래스의 get() 메소드를 호출하여 얻음, get()의 매개값은 파일의 경로이다. 따라서 문자열이나 URI 객체로 지정할 수 있다.
  문자열인 경우 전체 경로나 상위 디렉토리와 하위 디렉토리로 나열 가능
  - NIO는 입출력 방식이 채널 방식이고 비동기 방식을 지원한다.
