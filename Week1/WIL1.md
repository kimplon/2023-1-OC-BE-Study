1. MVC 패턴이란?

MVC: Model, View, Controller의 앞글자를 딴 약자입나다. 
MVC 패턴은 디자인 패턴 중 하나입니다. 
디자인 패턴이란 프로그램이나 어떤 특정한 것을 개발할 때 발생했던 문제점들을 정리해서 상황에 따라 간편하게 적용하여 쓸 수 있는 것을 정리하여 특정한 "규약"을 통해 쉽게 사용할 수 있는 형태로 만든 개념을 말합니다. 
쉽게 말하자면 "좀 더 쉽고 편리하게" 사용할 수 있게 만든 특정한 방법들을 디자인 패턴이라고 합니다.

2. API와 서버

API는 Application Programming Interface의 약어로, 
API는 서버와 클라이언트 사이에 상호작용을 할 수 있도록 하는 다리 역할을 하는 존재입니다.
응용 프로그램에서 서로 다른 시스템 간의 통신을 가능하게 하는 소프트웨어 인터페이스입니다.
API는 다른 시스템에서 요청한 데이터를 받아들이고 처리한 후 응답을 반환합니다.
예를 들어, Facebook의 API는 다른 애플리케이션에서 Facebook 데이터를 요청할 수 있도록 하며,
Google Maps API는 지도 데이터를 다른 웹 사이트에서 사용할 수 있도록 합니다.

서버는 컴퓨터 시스템 또는 응용 프로그램의 일부로서, 클라이언트에서 요청한 정보나 서비스를 제공하는 컴퓨터 프로그램입니다. 서버는 클라이언트가 요청한 데이터나 서비스를 처리하고, 결과를 반환하는 역할을 합니다.
예를 들어, 웹 서버는 웹 페이지를 클라이언트에게 제공하고, 메일 서버는 전자 메일을 처리하고,
데이터베이스 서버는 데이터를 저장하고 검색합니다.

API와 서버는 서로 다른 역할을 수행하지만, 서로 긴밀하게 연결되어 있습니다. API를 사용하여 클라이언트 애플리케이션이 서버에서 데이터를 요청하고, 서버는 이러한 요청을 받아 처리한 후 결과를 반환합니다. 
따라서 API와 서버는 현대적인 소프트웨어 개발에서 중요한 역할을 합니다.

3. RESTful이란?

RESTful은 일반적으로 REST라는 아키텍처를 구현하는 웹 서비스를 나타내기 위해 사용되는 용어이다.
‘REST API’를 제공하는 웹 서비스를 ‘RESTful’하다고 할 수 있다.

RESTful 아키텍처에서 웹 서비스는
각각 고유한 URI(Uniform Resource Identifier)로 식별되는 리소스 모음으로 처리됩니다.
클라이언트는 GET, POST, PUT, DELETE 등의 표준 HTTP 메서드 집합을 사용하여
이러한 리소스와 상호 작용할 수 있습니다.
그런 다음 서버는 일반적으로 JSON 또는 XML 형식으로 리소스를 표시하여 응답합니다.

RESTful 웹 서비스는 상태 비저장, 캐시 가능성, 균일한 인터페이스, 계층형 시스템 및 클라이언트-서버 아키텍처를 포함한 일련의 원칙을 따릅니다.
이러한 원칙을 따름으로써 RESTful 서비스는 확장 가능하고 안정적이며 다른 웹 서비스와 쉽게 통합될 수 있습니다.
전반적으로, RESTful은 유연하고 확장 가능하며 사용하기 쉬운 웹 서비스를 설계하고 구현하는 방법입니다.

RESTful 하지 못한 경우
Ex1) CRUD 기능을 모두 POST로만 처리하는 API
Ex2) route에 resource, id 외의 정보가 들어가는 경우(/students/updateName) 등이 있습니다.