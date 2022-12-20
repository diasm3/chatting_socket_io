# 심심해서 만든 Front & Backend(12월 18일 ~ 1월 18일까지)

# 가제 : 찬반 논쟁 채팅방

# TODO
[ ] 1. 소셜 로그인 passport -> 어드민 계정을 나눠야함 (채팅 및 게시물 삭제 권한)

[ ] 2. PWA 설정 -> 데탑은 너무 큼

[ ] 3. ERD 작성 및 게시판 만들기 -> 구성을 조금 생각해봐야함  

[ ] 4. 채팅 socketio -> sendbird를 참조 ... 하지만 간단한 채팅

[ ] 5. NESTJS test 코드 작성 

[ ] 6. docker hub CI/CD

[ ] 7. kubernetes deploy

[ ] 8. auto scaling test  - https://youtu.be/QWweMlerTZY, https://omnious.ai/ko-kr/resources/keda-sqs-k8s-autoscaling/

[ ] 9. artillery 트래픽 테스트



## 완료된 항목
1. 기본 react, nestjs 셋팅 완료
2. typeorm 설정완료
3. socket io 기본 셋팅 완료
4. docker compose 설정 완료
5. swagger 셋팅 완료
6. winston 셋팅 완료

## how to install

1. 리눅스나 윈도우에 git, docker, docker compose 설치
2. git 클론해서 다운받는다

```bash
$ git clone https://github.com/diasm3/chatting_socket_io.git
$ cd chatting_socket_io
```

3. docker compose 한다 (version 2.2.3)

```bash
$ sudo docker compose up -d
```


## front spec
1. react
2. react query
3. redux 사용 예정
4. socket.io 
5. chakraUi


## Backend spec
1. nestjs
2. typeorm
3. mariadb
4. redis
5. socketio


## docker compose
1. react
2. nestjs
3. redis
4. mariadb


## CICD
1. git action

## 배포
1. 어디다 할까.... AWS?
2. Nas?
