# 과제2

1 top

시스템 프로세스 상태를 실시간으로 보여주는 명령어

![top명령어](https://github.com/213014wooju/213014wooju/assets/171469341/0e8f3367-c74c-47a1-9dc5-3cd2891c1d31)

2 ps

현재 실행중인 프로세스를 보여주는 명령어

![ps](https://github.com/213014wooju/213014wooju/assets/171469341/bb9f93cd-38f6-410b-b91a-6adcd3e551ed)

다양한 옵션들

* -A, -e : 모든 프로세스를 출력
* a : 다른 사용자의 프로세서도 출력
* -l : 자세하게 출력
* -u : 각 프로세서의 사용자 이름과 시작 시간 출력
* -j, -s, -v : job,signal,virtual memory 형태
* -m : memory 정보 출력
* -r : 현재 실행중인 프로세서만 출
* -x : 실행시킨 터미널이 없는 프로세서 출력

3 jobs

백그라운드에서 실행중인 작업을 보여주는 명령어

![jobs](https://github.com/213014wooju/213014wooju/assets/171469341/c57da1e7-d40f-42b0-ad45-d25d03048d64)

4 kill

프로세스를 종료시키는 명령어 / 일반적으로 프로세스 ID를 지정하여 종료시킴
  
![kill](https://github.com/213014wooju/213014wooju/assets/171469341/76dd5514-9115-4854-a855-aef28f41e45e)

다양한 옵션들 (신호 종류)

* -1 : HUP / 프로세스 종료 없이 구성 파일 리로드
* -2 : INT / 키보드 인터럽트
* -3 : QUIT / 키보드 종료 및 덤프 생성
* -9 : KILL / 즉각적인 강제적 종
* -15 : TEAM / 정상적인 종료
* -18 : CONT / 중지된 프로세스 다시 시작
* -19 : STOP / 프로세스 동작 중지
* -20 : TSTP / 프로세스 동작 중지

