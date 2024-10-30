# PoABOT - Power of Algorithm
## 트레이딩뷰에서 전달되는 웹훅을 처리하는 봇입니다.
 
* 지원 거래소
  * 업비트 KRW(원화) 마켓
  * 바이낸스 현물/선물 USDT,BUSD 마켓
  * 바이비트 현물/선물 USDT 마켓
  * 비트겟 현물/선물 USDT 마켓
  * 한국투자증권 한국/미국 주식 마켓
 
# <주의>
*본 프로젝트는 개인적으로 개발한 프로젝트를 오픈소스로 공유한 것으로*

*발생하는 문제에 대한 모든 책임은 본인에게 있습니다.*

jangdokang/POA - github: <a href="https://github.com/jangdokang/POA">바로가기</a>

- POA_DOCKER은 PoA 개발자 jangdokang님에게 허락을 받고 올린 Repository 입니다. ~~(저작권 문제 없음)~~


# 설정
* <a href="https://github.com/th-release/POA_DOCKER/blob/main/app/.env">env로 이동하기</a> 해당 파일로 POA 셋팅을 합니다.

# 초기화 방법
이전에 있던 POA 데이터를 초기화하는 방법은 <a href="https://github.com/th-release/POA_DOCKER/tree/main/app/pb_data">pb_data</a>에 있는 모든 파일을 삭제 후, <a href="https://github.com/th-release/POA_DOCKER/tree/main/reset_pb">reset_pb</a>에 있는 data.db를 넣어주시고, `docker compose down; docker compose up -d` 명령어를 실행해주시면 됩니다!

# How To Start?
기본적으로 설정을 모두 끝내고 도커를 설치 후, 아래 명령어를 사용해주세요!
```
docker compose up -d
```

# 종료 방법
```
docker compose down
```

# POA_DOCKER 관련 질문 및 연락
Discord: `cth.release`\
Instagram: <a href="https://instagram.com/cth.release">cth.release</a>

### 잡다한 말.
Repository의 Star와 <a href="https://github.com/th-release">cth.release</a> 팔로우는 작성자에게 힘이 됩니다.
