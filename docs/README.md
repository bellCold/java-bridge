# *미션 - 다리 건너기*

## 😀 기능 구현 목록

### - 입출력 기능 목록

- `입력 기능 목록`
    - [x] 다리 길이 입력 기능
    - [x] 플레이어가 이동할 칸 입력 기능
    - [x] 게임 재시작/종료 입력 기능

- `출력 기능 목록`
    - [X] 게임 시작 문구 출력 기능
    - [x] 이동할 칸 안내 문구 출력 기능
    - [x] 이동 후 현재 이동한 다리 모양 출력 기능
    - [x] 이동 실패시 게임 재시작/종료 여부 출력 기능
    - [x] 최종 게임 결과 출력 기능

### - 다리 생성 기능 목록

- [x] 입력한 길이에 맞는 다리 생성 기능
- [x] 만들어진 다리를 "U", "D"로 이루어진 리스트로 변환해주는 기능

### - 다리 건너기 기능 목록

- [x] 방향 입력시 건널수 있는 다리 인지 체크한 기능
- [x] 건널 수 있다면 "O" 지도 생성
- [x] 건널 수 없다면 "X" 지도 생성 기능

### - 지도 기능

- [x] 현재 결과를 지도로 보여줄 수 있는 기능

### - 시도 횟수 카운트 기능 목록

- [x] 재시도시 횟수 +1 증가 기능

### - 시도 횟수 카운트 기능 목록

- [x] 현재 결과의 지도, 성공여부, 시도 횟수를 도출하는 기능

### - 유효성 검사 기능 목록

- `입력값 유효성 기능 목록`
    - [x] 다리 길이 입력값 유효성 검사 기능
    - [x] 이동할 칸 입력값 유효성 검사 기능
    - [x] 게임 재시작/종료 입력값 유효성 검사 기능

## 👀 기능 ***예외*** 사항

✔️`공통 예외` : 예외 발생시 "[ERROR]" 로 시작하는 문구 출력후 그 부분부터 다시 입력 받는다

- 입력 예외 사항
    - 다리의 길이는 최소 3, 최대 20 인 정수만 입력 가능
    - 빈 칸 입력시 예외 발생
    - 이동 칸은 "U"와 "D"만 입력 가능
    - 재시작/종료는 "Q"와 "R"만 입력가능

---
## ✔️ ***테스트*** 목록

- 다리 건너기 게임
  - 건너기 성공 테스트
  - 건너기 실패 테스트
  - 건너기 재시작 테스트
- 다리 건너기 지도 생성
  - 다리 생성 반영 테스트
- 재시작 여부 테스트
  - Q 또는 R 값만 입력 가능 테스트
- 0, 1을 U, D 로 바꿔주는 유틸
  - 0 -> D, 1 -> U으로 바꿔주는지 테스트
- 입력값 유효성 검사
  - bridgeSize -> 3 ~ 20 사이의 정수만 입력 가능한지 테스트
  - direction -> U, D의 방향 입력만 가능한지 유효성 검사 테스트  