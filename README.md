# 숫자 야구 게임
## 진행 방법
* 숫자 야구 게임 요구사항을 파악한다.
* 요구사항에 대한 구현을 완료한 후 자신의 github 아이디에 해당하는 브랜치에 Pull Request(이하 PR)를 통해 과제를 제출한다.

## 과제 제출 과정
* [과제 제출 방법](https://github.com/next-step/nextstep-docs/tree/master/precourse)

## 기능목록
1. 1-9까지 서로 다른 3자리 랜덤숫자 추출
2. 3자리 수 입력 받기
3. 입력 받은 수에 대해 스트라이크 규칙(같은 수와 같은 자리) 확인
    1. 자릿수별로 같은 수인지 확인
    2. 3 스트라이크면 결과 출력 후 게임 종료 처리
    3. 3 스트라이크가 아닌 경우 스트라이크 자릿수 저장       
4. 볼 규칙(다른 자리에 있는 수) 확인
    1. 스트라이크가 아닌 숫자 중 볼 규칙 확인 후 결과 출력(n 스트라이크 m 볼)
5. 스트라이크와 볼 규칙에 해당하는 숫자 모두 없는 경우 포볼 또는 낫싱 출력
6. 게임 종료 처리
    1. 값을 입력받아 그 값이 1이면 새 게임 시작
    2. 값을 입력받아 그 값이 2이면 게임 종료