# 💻 calc – OSS 기반 프로젝트

## 📁 저장소
[https://github.com/202407001/2025oss](https://github.com/202407001/2025oss)

## 👥 팀원 구성

| 이름       | 역할                            |
|------------|----------------------------------|
| 홍길동     | 팀장 – dev/b 및 main 브랜치 수정 |
| 김일원     | 팀원 – dev/a, dev/c 및 ReadMe.md 수정 |

## 📌 프로젝트 개요

본 프로젝트는 사칙연산 기능을 제공하는 콘솔 계산기를 개발하며, Git을 활용한 협업 및 충돌 해결 과정을 실습하기 위한 OSS 기반 팀 프로젝트입니다.

## 🔧 개발 브랜치 및 병합 과정

### 문제 해결 순서

1. `main` 브랜치와 `dev/a` 브랜치 병합
2. `main` 브랜치와 `dev/b` 병합 시 `calc/mul.h`에서 충돌 발생
3. `dev/b`의 내용을 수정하고 fast-forward 병합 완료
4. `dev/c` 브랜치 병합 시 충돌 발생
5. rebase를 통해 충돌 해결 후 병합
6. 정상 병합 확인 및 프로그램 실행
7. `README.md` 최종 수정

![스크린샷1](images/screenshot_1.png)
![스크린샷1](images/screenshot_2.png)
![스크린샷1](images/screenshot_3.png)
![스크린샷1](images/screenshot_4.png)
![스크린샷1](images/screenshot_5.png)
![스크린샷1](images/screenshot_6.png)
