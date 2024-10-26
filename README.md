# java-racingcar-precourse
## 초간단 자동차 경주 게임을 구현한다.

-[x] 각 자동차에 이름을 부여할 수 있다.
-[x] 자동차 이름은 5자를 초과할 수 없다.
-[x] 자동차 이름은 공백을 포함할 수 없다.
-[x] 자동차 이름은 쉼표(,)를 기준으로 구분한다.
-[x] 시도할 횟수를 입력할 수 있어야 한다.
-[x] 잘못된 입력을 받으면 IllegalArgumentException을 발생시켜야한다.
-[x] 자동차는 전진 또는 멈출 수 있다.
-[x] 전진하는 자동차를 출력할 때 자동차 이름을 같이 출력한다.
-[ ] 전진하는 조건은 0에서 9 사이에서 무작위 값을 구한 후 무작위 값이 4 이상일 경우이다.
-[ ] 자동차의 상태를 화면에 출력한다.
-[ ] 자동차 경주 게임을 완료한 후 누가 우승했는지를 알려준다.
-[ ] 우승자는 한 명 이상일 수 있다.


## 프로그래밍 요구 사항 1
- JDK 21 버전에서 실행 가능해야 한다.
- 프로그램 실행의 시작점은 Application의 main()이다.
- build.gradle 파일은 변경할 수 없으며, 제공된 라이브러리 이외의 외부 라이브러리는 사용하지 않는다.
- 프로그램 종료 시 System.exit()를 호출하지 않는다.
- 프로그래밍 요구 사항에서 달리 명시하지 않는 한 파일, 패키지 등의 이름을 바꾸거나 이동하지 않는다.
- 자바 코드 컨벤션을 지키면서 프로그래밍한다.
- 기본적으로 Java Style Guide를 원칙으로 한다.


## 프로그래밍 요구 사항 2
- indent(인덴트, 들여쓰기) depth를 3이 넘지 않도록 구현한다. 2까지만 허용한다.
    - 예를 들어 while문 안에 if문이 있으면 들여쓰기는 2이다.
    - 힌트: indent(인덴트, 들여쓰기) depth를 줄이는 좋은 방법은 함수(또는 메서드)를 분리하면 된다.
- 3항 연산자를 쓰지 않는다.
- 함수(또는 메서드)가 한 가지 일만 하도록 최대한 작게 만들어라.
- JUnit 5와 AssertJ를 이용하여 정리한 기능 목록이 정상적으로 작동하는지 테스트 코드로 확인한다.
    - 테스트 도구 사용법이 익숙하지 않다면 아래 문서를 참고하여 학습한 후 테스트를 구현한다.


## 라이브러리
- camp.nextstep.edu.missionutils에서 제공하는 Randoms 및 Console API를 사용하여 구현해야 한다.
    - Random 값 추출은 camp.nextstep.edu.missionutils.Randoms의 pickNumberInRange()를 활용한다.
    - 사용자가 입력하는 값은 camp.nextstep.edu.missionutils.Console의 readLine()을 활용한다.
