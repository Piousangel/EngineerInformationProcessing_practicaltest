# 개인적으로 드릴 말씀이 있습니다.


1. 1권
- [x] 프로그래밍 언어 활용
- [x] 요구사항 확인
- [x] 데이터 입출력 구현
- [x] 통합 구현
- [x] 서버 프로그램 구현

1. 2권
- [x] 화면 설계
- [x] 어플리케이션 테스트 관리
- [x] SQL 응용
- [x] 소프트웨어 개발 보안 구축
- [x] 응용 SW 기초 기술 활용
- [ ] 제품 소프트웨어 패키징

+ 요구사항 확인 : 0~1 문제 출제
+ 화면설계     : 0~1 문제 출제
+ 데이터 입출력 구현 : 1~2문제 출제
###  __SQL응용     : 3~4문제 출제__
###  __프로그래밍 활용   : 4~5문제 출제__
+ 통합 구현    : 1~3문제 출제
+ 서버프로그램 구현  : 1~2문제 출제
+ 애플리케이션 테스트 관리 : 거의 2문제 출제
+ 소프트웨어 개발 보안 구축 : 1~2문제 출제
+ 응용 SW기술 활용 : 3~4문제 출제
+ ~~제품소프트웨어 패키징 0~1문제 인데 그냥 안볼꺼임~~
+ ~~인터페이스구현~~ 안볼꺼임

git add *
git commit -m "이슈 해결"

커밋 이후 수정사항이 발생했을 경우
git add *
git commit -m "수정 및 벨리데이션 추가" --amend를 통해 커밋 메세지를 수정할 수 있습니다.

- git pull과 fetch의 차이점
- pull 과 fetch 의 차이점은 merge 작업을 하느냐 안하느냐로 나뉘어지며.
- pull 은 fetch + merge 작업이라고 생각하시면 됩니다.
- git reflog 명령을 통해 이전 버전으로 돌아갈 수있습니다



![스크린샷 2022-05-27 오후 1 20 59](https://user-images.githubusercontent.com/55525574/170628478-95633afc-9334-4c37-9b74-a88201d89ab0.png)
ex) git reset

- 바로 이전 단계로 인덱스와 워킹트리를 버리고 리셋
$git reset HEAD^ --hard

- 바로 두번째 전 단계로 인덱스와 워킹트리를 버리고 리셋
$git reset HEAD~2 --hard

- 특정 리비전의 기록으로 인덱스는 버리고 워킹트리를 보존하여 리셋
$git reset 991ee8c --mixed


<img width="805" alt="스크린샷 2021-11-26 오후 7 22 51" src="https://user-images.githubusercontent.com/55525574/143567184-120d7e65-a5b2-49b2-9e38-476a482ff252.png">
