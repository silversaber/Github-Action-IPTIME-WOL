# Gtihub-Action-IPTIME-WOL

외부에서 정해진 스케쥴에 IPTIME 공유기에 Wake On Lan을 실행하는 코드입니다.
프로젝트의 secert키로 저장한 값은 아래와 같습니다.

- IPTIME_BASIC : IPTIME 공유기 '관리자 계정:계정 비밀번호'의 값을 Base64 인코딩한값입니다.
- IPTIME_DOMAIN : IPTIME 공유기의 외부 도메인입니다.
- IPTIME_MAC : IPTIME 공유기를 통하여 WOL을 실행할 컴퓨터의 MAC 주소입니다.
