# 자동차 경주 게임
## 진행 방법
* 자동차 경주 게임 요구사항을 파악한다.
* 요구사항에 대한 구현을 완료한 후 자신의 github 아이디에 해당하는 브랜치에 Pull Request(이하 PR)를 통해 코드 리뷰 요청을 한다.
* 코드 리뷰 피드백에 대한 개선 작업을 하고 다시 PUSH한다.
* 모든 피드백을 완료하면 다음 단계를 도전하고 앞의 과정을 반복한다.

## 온라인 코드 리뷰 과정
* [텍스트와 이미지로 살펴보는 온라인 코드 리뷰 과정](https://github.com/next-step/nextstep-docs/tree/master/codereview)

## 요구사항
* 주어진 횟수 동안 n대의 자동차는 전진 또는 멈출 수 있다.
* 사용자는 몇 대의 자동차로 몇 번의 이동을 할 것인지를 입력할 수 있어야 한다.
* 전진하는 조건은 0에서 9 사이에서 random 값을 구한 후 random 값이 4이상일 경우이다.
* 자동차의 상태를 화면에 출력한다. 어느 시점에 출력할 것인지에 대한 제약은 없다.
* 모든 로직에 단위테스트를 구현한다(중요) - InputView, ResultView
* 자바 컨벤션을 지킨다
* else 예약어 쓰지 않는다 

## Commit 메세지
1. feat (feature)
2. fix (bug fix)
3. docs (documentation)
4. style (formatting, missing semi colons, …)
5. refactor
6. test (when adding missing tests)
7. chore (maintain)

## 필요한 기능 - 클래스
1. 자동차 클래스
2. 게임 실행할 메인 클래스
3. InputView (정보 입력)
4. ResultView (정보 출력)
5. 자동차 기능 클래스

## 필요한 기능 - 함수
1. 자동차 이동함수
2. 이동거리 구하는 함수
3. 출력 함수
4. 전진 멈춤 판단 함수
5. 자동차 대수, 이동 횟수 입력 함수
