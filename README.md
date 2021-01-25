# Github-Action-IPTIME-WOL

## 1. 목적
매일 UTC 00:00(KTC 09:00)시에 [IPTIME][iptimelink] 공유기를 통해 Wake On Lan을 실행하고  
그 결과를 이슈에 저장하는 [Github-Action][githubactionlink] 코드입니다.


## 2. 의존성
    IPTIME_BASIC  : IPTIME 공유기의 '관리자 계정:계정 비밀번호'의 값을 Base64로 인코딩한값입니다.
    IPTIME_DOMAIN : IPTIME 공유기의 외부 도메인입니다.
    IPTIME_MAC    : IPTIME 공유기를 통하여 WOL을 실행할 컴퓨터의 MAC 주소입니다.
    

## 3. 이슈
[Github-Action][githubactionlink]이 가동하는데 50분 이상이 걸려 1시간을 땡겨
UTC 23:00(KTC 08:00)시에 실행하도록 코드 

[iptimelink]: https://iptime.com/iptime/
[githubactionlink]: https://github.com/features/actions
