# Github-Action-IPTIME-WOL

## 1. 목적

---

매일 UTC 00:00(KTC 09:00)시에 [IPTIME][iptimelink] 공유기를 통해 Wake On Lan을 실행하고  
그 결과를 이슈에 저장하는 [Github-Action][githubactionlink] 코드입니다.

## 2. 의존성

---

본 프로젝트에서 사용된 모듈은 이하와 같습니다.

> 1.  [1466587594/get-current-time@v2][1466587594/get-current-time@v2link]
> 2.  [indiesdev/curl@v1][indiesdev/curl@v1link]
> 3.  [haya14busa/action-cond@v1][haya14busa/action-cond@v1link]
> 4.  [nashmaniac/create-issue-action@v1.1][nashmaniac/create-issue-action@v1.1link]

### 프로젝트 실행에 필요한 각 변수들은 secert키로 저장하였으며 아래와 같습니다.

    IPTIME_BASIC  : IPTIME 공유기의 '관리자 계정:계정 비밀번호'의 값을 Base64로 인코딩한값입니다.
    IPTIME_DOMAIN : IPTIME 공유기의 외부 도메인입니다.
    IPTIME_MAC    : IPTIME 공유기를 통하여 WOL을 실행할 컴퓨터의 MAC 주소입니다.

[iptimelink]: https://iptime.com/iptime/
[githubactionlink]: https://github.com/features/actions
[1466587594/get-current-time@v2link]: https://github.com/1466587594/get-current-time
[indiesdev/curl@v1link]: https://github.com/marketplace/actions/curl-axiosjs
[haya14busa/action-cond@v1link]: https://github.com/haya14busa/action-cond
[nashmaniac/create-issue-action@v1.1link]: https://github.com/nashmaniac/create-issue-action
