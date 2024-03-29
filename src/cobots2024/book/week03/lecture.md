# [핵심 교육 (Part 1/2)](https://www.youtube.com/watch?v=bmOn1uwOsqM&list=PLEkBnBwQmnmvCREKyRleWnG8WwsANLuY-)

## 주요 내용

1. 협동 로봇 기본 교육 소개 (Introduction to Collaborative Robot Basic Training)

   - 협동 로봇 기본 교육 및 학습 방식 안내
   - 로봇 모션 기능 및 안전 설정
   - 편의 기능 및 프로그래밍 환경 소개
   - 토크 센서, 안전, 작업 환경 설정

2. 툴 설정과 좌표계 (Tool Settings and Coordinate Systems)

   - 툴 무게 설정과 자동 계산
   - 직접 툴 무게 측정 방법
   - 툴 형상 설정의 중요성
   - 로봇 마운트와 설치 자세 설정
   - 툴 설정 적용과 사용자 좌표계

3. 좌표계와 로봇 파라미터 설정 (Coordinate Systems and Robot Parameter Settings)

   - 사용자 정의 좌표계 설정 방법
   - 월드 좌표계 설정 및 활용
   - 로봇 파라미터 설정의 중요성

4. 안전 설정과 충돌 감지 (Safety Settings and Collision Detection)

   - 조인트 각도 제한과 조정
   - 안전 신호 입출력 설정 방법
   - 안전 정지 모드와 충돌 감지
   - 안전 영역 설정 및 활용
   - 충돌 감지 설정과 안전 정지

5. 툴과 그리퍼 설정 실습 (Tool and Gripper Setup Practice)

   - 툴 무게 및 그리퍼 설정 실습
   - 그리퍼 설정 방법과 신호 할당
   - 툴 중심점 설정의 중요성
   - 작업기계 등록 및 설정 과정

6. 프로그래밍 기초 (Programming Basics)

   - 프로그램 관리와 태스크 라이터
   - 커맨드와 스킬 사용 기초
   - 상대 이동과 절대 이동의 이해

7. 모션 제어와 속도 설정 (Motion Control and Speed Settings)

   - 모션 시간 제어와 속도 설정
   - 작동 모드와 블렌딩 모드 활용
   - 비동기 모드와 반경 설정 기술

8. 로봇 모션 경로 계획과 실행 (Robot Motion Path Planning and Execution)

   - 로봇 모션 경로 계획과 실행
   - 조인트 이동과 상대 이동 실행
   - 개별 속도 설정과 속도 변화 테스트
   - 블렌딩과 스플라인 모션의 활용

9. 스플라인 모션과 학습 정리 (Spline Motion and Learning Summary)
   - 스플라인 모션 구현 방법
   - 학습 내용 정리와 다음 과정 예고

## 시간별 목차

### 4. 안전 설정과 충돌 감지

- [01:02:51](https://www.youtube.com/watch?v=bmOn1uwOsqM&t=3534s) 🛡️ 안전 영역 설정

  - 안전 영역 설정 방법과 중요성
  - 공간 제한 및 특정 영역 형성 과정
  - 영역 진입 여부를 확인할 수 있는 신호 활성화

- [01:04:48](https://www.youtube.com/watch?v=bmOn1uwOsqM&t=6288s) ⚠️ 충돌 감지 설정

  - 충돌 민감도 설정 및 충돌 감지를 통한 안전 정지
  - 특정 영역 내에서의 충돌 민감도 조절
  - 충돌 감지에 따른 로봇의 안전한 작동 보장

- [01:11:12](https://www.youtube.com/watch?v=bmOn1uwOsqM&t=6672s) 🛠️ 툴 무게 및 그리퍼 설정
  - 툴 무게 측정과 그리퍼 설정의 실습
  - 장착된 툴의 무게와 중심점 설정 과정
  - ND 팩터 및 서드파티 아이템 설정을 통한 효율적인 로봇 제어

이 섹션에서는 로봇의 안전 영역 설정, 충돌 감지 설정, 그리고 툴 무게 및 그리퍼 설정에 대해 설명합니다. 안전 영역 설정을 통해 로봇이 작동하는 공간의 안전성을 확보하고, 충돌 민감도 설정을 통해 로봇의 안전한 작동을 보장합니다. 또한, 툴 무게 측정과 그리퍼 설정을 통해 로봇의 작업 효율성과 정밀성을 향상시키는 방법에 대해 다룹니다.

### 5. 툴과 그리퍼 설정 실습

- [01:17:08](https://www.youtube.com/watch?v=bmOn1uwOsqM&t=4628s) 🤖 그리퍼 설정 방법

  - 전기 그리퍼 설정 및 신호 할당
  - 선택한 그리퍼에 따른 기능과 설정 차이 이해
  - 포트 번호 선택 및 컨트롤러의 선택 확인 필요성

- [01:21:45](https://www.youtube.com/watch?v=bmOn1uwOsqM&t=4905s) 🛠️ 툴 중심 위치 설정

  - 툴 중심 위치 자동 계산 및 수동 설정
  - 작업 효율성과 정밀도 향상을 위한 중요 설정 과정
  - 등록된 툴의 중심 위치 활성화 및 적용 확인

- [01:29:41](https://www.youtube.com/watch?v=bmOn1uwOsqM&t=5381s) 🏭 작업기계 등록 및 설정
  - 가공 기계와의 통신을 위한 설정 과정
  - 통신 명령어와 신호 매핑을 통한 작업 기계 제어
  - 작업 효율성 및 안전성 향상을 위한 설정 중요성

이 섹션에서는 로봇에 연결된 그리퍼 설정 방법, 툴 중심 위치 설정 과정, 그리고 작업기계 등록 및 설정 방법에 대해 설명합니다. 이를 통해 로봇의 작업 효율성과 정밀도를 높이며, 안전하고 효과적인 작업 환경을 조성하는 방법에 대해 다룹니다.

### 6. 프로그래밍 기초

- [01:42:07](https://www.youtube.com/watch?v=bmOn1uwOsqM&t=6127s) 🔄 프로그램 관리 및 태스크 라이터 활용

  - 프로그램 작성, 저장, 내보내기 등 관리 기능
  - 태스크 라이터를 이용한 신규 프로그램 작성 방법
  - 저장된 파일 불러오기 및 USB를 통한 프로그램 가져오기

- [01:59:06](https://www.youtube.com/watch?v=bmOn1uwOsqM&t=7146s) 📚 커맨드 및 스킬 사용 기본

  - 커맨드와 스킬 사용의 기본적인 내용 소개
  - 다양한 커맨드와 스킬 활용 방법에 대한 설명
  - 프로그래밍 시 고려해야 할 점과 유의사항

- [02:06:33](https://www.youtube.com/watch?v=bmOn1uwOsqM&t=7593s) 🛠️ 상대 이동과 절대 이동의 구분 및 적용
  - 상대 이동과 절대 이동의 차이 및 적용 사례
  - 이동 명령어(Move J, Move L)의 특성 및 활용
  - 로봇 프로그래밍에서의 이동 경로 예측과 효율적 이동 전략

이 섹션들에서는 로봇 프로그래밍과 관리에 필요한 다양한 기능과 사용 방법을 다룹니다. 프로그램 관리 및 태스크 라이터 활용 방법을 통해 신규 프로그램의 작성부터 관리, 내보내기까지의 과정을 배우고, 커맨드 및 스킬 사용 기본을 통해 다양한 작업 실행에 필요한 커맨드와 스킬을 이해합니다. 또한, 상대 이동과 절대 이동의 구분 및 적용을 통해 로봇의 효율적인 이동 경로를 계획하고 예측하는 방법을 학습합니다.

### 7. 모션 제어와 속도 설정

- [02:08:26](https://www.youtube.com/watch?v=bmOn1uwOsqM&t=7706s) ⏳ 모션 시간 제어 및 속도 설정

  - 특정 시간 동안 모션을 제어하는 방법과 속도 설정의 중요성
  - 리니어 및 각속도 설정을 통한 세밀한 모션 제어 가능

- [02:10:26](https://www.youtube.com/watch?v=bmOn1uwOsqM&t=7826s) 🔄 작동 모드와 블렌딩 모드

  - 출발 및 정지를 반복하지 않고 부드럽게 연결하는 모션 제어
  - 작동 모드와 블렌딩 모드를 활용한 효율적인 모션 계획

- [02:12:32](https://www.youtube.com/watch?v=bmOn1uwOsqM&t=7952s) ⚙️ 비동기 모드와 반경 설정
  - 비동기 모드를 통한 모션 명령어의 동시 실행
  - 반경 설정으로 모션의 부드러운 연결 및 이동 경로 최적화

이 섹션들은 로봇의 모션 제어와 관련된 다양한 기술과 설정을 다룹니다. 모션 시간 제어 및 속도 설정을 통해 원하는 모션을 정확한 시간 동안 실행할 수 있으며, 리니어 및 각속도 설정으로 세밀한 모션 제어가 가능합니다. 작동 모드와 블렌딩 모드를 활용하여 로봇의 모션을 부드럽게 연결하며, 비동기 모드와 반경 설정을 통해 모션의 효율성과 최적화를 극대화할 수 있습니다.

- [02:20:01](https://www.youtube.com/watch?v=bmOn1uwOsqM&t=7201s) 🔄 로봇 모션 경로 계획 및 실행

  - MOVL과 MOVJ 명령어를 사용하여 로봇 모션 경로를 계획 및 실행하는 방법
  - MOVL은 직선 경로, MOVJ는 점을 경유하는 곡선 형태의 모션 실행

- [02:22:43](https://www.youtube.com/watch?v=bmOn1uwOsqM&t=7363s) ⚙️ 조인트 별 이동 및 상대 이동의 실행

  - 조인트 별 이동 명령어를 사용하여 로봇의 특정 조인트를 원하는 각도로 이동
  - 상대 이동 명령어를 사용하여 로봇의 위치를 기준 위치 대비 상대적으로 이동

- [02:28:01](https://www.youtube.com/watch?v=bmOn1uwOsqM&t=7681s) 🏃 개별 속도 설정 및 속도 변화 테스트

  - 개별 모션 명령어에 대한 속도 설정을 통해 로봇 모션의 속도 변화 테스트
  - 다양한 속도로 설정하여 모션 실행 시 속도 차이 관찰 및 테스트

- [02:30:11](https://www.youtube.com/watch?v=bmOn1uwOsqM&t=7811s) 🔄 블렌딩 모드와 스플라인 모션
  - 블렌딩 모드를 사용하여 모션 사이의 부드러운 연결과 효율적인 경로 계획
  - 스플라인 모션을 사용하여 여러 명령어를 연속적으로 실행하며 경유지를 통한 부드러운 경로 생성

이 섹션들은 로봇의 조인트 별 이동, 상대 이동, 속도 설정, 블렌딩 모드 사용 및 스플라인 모션 실행 등에 대한 다양한 기술과 설정 방법을 다룹니다. 이를 통해 로봇의 모션 경로를 효과적으로 계획하고 실행할 수 있으며, 속도 조절과 부드러운 모션 연결을 통해 효율적인 로봇 운영을 실현할 수 있습니다.

### 8. 로봇 모션 경로 계획과 실행

- [02:20:01](https://www.youtube.com/watch?v=bmOn1uwOsqM&t=7201s) 🔄 로봇 모션 경로 계획 및 실행

  - MOVL과 MOVJ 명령어를 사용하여 로봇 모션 경로를 계획 및 실행하는 방법
  - MOVL은 직선 경로, MOVJ는 점을 경유하는 곡선 형태의 모션 실행

- [02:22:43](https://www.youtube.com/watch?v=bmOn1uwOsqM&t=7363s) ⚙️ 조인트 별 이동 및 상대 이동의 실행

  - 조인트 별 이동 명령어를 사용하여 로봇의 특정 조인트를 원하는 각도로 이동
  - 상대 이동 명령어를 사용하여 로봇의 위치를 기준 위치 대비 상대적으로 이동

- [02:28:01](https://www.youtube.com/watch?v=bmOn1uwOsqM&t=7681s) 🏃 개별 속도 설정 및 속도 변화 테스트

  - 개별 모션 명령어에 대한 속도 설정을 통해 로봇 모션의 속도 변화 테스트
  - 다양한 속도로 설정하여 모션 실행 시 속도 차이 관찰 및 테스트

- [02:30:11](https://www.youtube.com/watch?v=bmOn1uwOsqM&t=7811s) 🔄 블렌딩 모드와 스플라인 모션
  - 블렌딩 모드를 사용하여 모션 사이의 부드러운 연결과 효율적인 경로 계획
  - 스플라인 모션을 사용하여 여러 명령어를 연속적으로 실행하며 경유지를 통한 부드러운 경로 생성

이 섹션들은 로봇의 조인트 별 이동, 상대 이동, 속도 설정, 블렌딩 모드 사용 및 스플라인 모션 실행 등에 대한 다양한 기술과 설정 방법을 다룹니다. 이를 통해 로봇의 모션 경로를 효과적으로 계획하고 실행할 수 있으며, 속도 조절과 부드러운 모션 연결을 통해 효율적인 로봇 운영을 실현할 수 있습니다.

### 9. 스플라인 모션과 학습 정리

- [02:32:42](https://www.youtube.com/watch?v=bmOn1uwOsqM&t=9162s) 🔄 스플라인 모션 구현

  - SDA 명령어를 이용하여 스플라인 모션 구현
  - 코드와 포즈 저장을 통한 세그먼트 특정 및 스플라인 경로 실행 확인

- [02:35:20](https://www.youtube.com/watch?v=bmOn1uwOsqM&t=9320s) 📚 오늘 배운 내용 요약 및 내일 과정 예고
  - MOVJ, MOVL 및 SDA 명령어를 통한 다양한 모션 경로 계획 및 실행
  - 로봇의 기능과 프로그램 환경, 테스크 라이터 및 필드에서의 안전 설정과 관리 방법

이 섹션들은 로봇 프로그래밍의 핵심 요소인 스플라인 모션 구현 방법과 오늘 배운 내용의 요약 및 내일 과정에 대한 예고를 다룹니다. 로봇의 다양한 모션 경로 계획과 실행, 프로그램 환경 설정 및 관리 방법에 대한 이해를 돕습니다.
