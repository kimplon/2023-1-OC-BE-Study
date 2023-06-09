1. 컨트롤러, 서비스, 리포지토리의 역할
컨트롤러
컨트롤러는 사용자의 요청을 처리하고 사용자 인터페이스와 비즈니스 로직 간의 데이터 흐름을 조정하는 역할을 한다.  일반적으로 사용자로부터 입력을 받고, 검증 및 인증을 수행한다. 필요한 비즈니스 로직을 수행하기 위해 적절한 서비스를 요청한다. 또한 이 과정에서 발생하는 오류나 예외사항도 처리한다. 

서비스
서비스는 비즈니스 로직(모델)과 컨트롤러 간의 인터페이스를 제공한다. 
응용프로그램의 핵심 논리를 캡슐화하고 일반적으로 응용프로그램의 대부분을 처리한다. 서비스는 데이터 처리, 조작, 인증 및 권한 부여까지 다양한 작업을 담당한다. 종종 저장소와 통신하여 데이터를 읽거나 쓴다. 

레포지토리
응용 프로그램의 데이터 저장 및 검색을 관리하는 역할을 한다. 애플리케이션의 데이터와 비즈니스 로직 사이 추상화 계층을 제공하므로 애플리케이션의 다른 구성 요소에서 데이터에 쉽게 접근하고 수정할 수 있다. 레포지토리는 일반적으로 DB 쿼리 또는 파일 입출력과 같은 데이터 접근 논리를 캡슐화하고 서비스 및 컨트롤러가 데이터와 상호 작용할 수 있도록 하는 API를 제공한다. 

결론은 컨트롤러, 서비스 및 레포지토리는 MVC 아키텍쳐에서 각각 중요한 역할을 수행한다.

2. TDD란? 왜 하는가?
TDD는 Test-Driven Development의 약자이다. 개발자가 테스트를 작성하고, 테스트를 실행하여 실패를 확인한 후 코드를 작성하여 통과시킨 후 다음 테스트를 위해 프로세스를 반복한다. 

TDD의 목표는 코드가 품질, 유지관리 가능성 및 정확성에 중점을 두고 개발되도록 하는 것이다.

전반적으로 TDD는 코드 품질을 개선하고, 생산성을 높이며, 디버깅 시간을 단축하고, 팀원 간의 협업을 촉진하는 데 도움이 될 수 있는 소프트웨어 개발에 대한 유익한 접근 방식이기 때문에 TDD를 사용한다.