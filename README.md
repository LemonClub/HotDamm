# 남은 작업
## 단어 선택


## 클라이언트
### 1. 회원가입
  * [ID](#ID)
  * [PW](#PW)
  * [기타 연동](#연동)
  * [나이대](#나이대)
  * [핀(관심 태그)](#태그)
  * [이름 설정](#이름)
  * [프로필 사진 설정](#프사)

### 2. 메인 (타임라인)
  * [타임라인](#타임라인)
  * [타임라인 새로고침](#새로고침)
  * [타임라인 태그 필터링](#필터링)
  * [광고](#광고)
  * [댓글](#댓글)
  * [클립(좋아요)](#따봉)
  * [공유](#공유)
  * [검색](#검색)

### 3. 프로필
  * [채팅](#채팅)
  * [팔로우](#팔로우)
  * [신고](#신고)
  * [밴](#밴)
  * [이전에 올렸던 글](#이전글)

### 4. 글
  * [포스트(댓글)](#댓글)
  * [클립(따봉)](#따봉)
  * [공유](#공유)
  * [글 방식 (블로그식 or something else..)](#글방식)
  * [원 포스트 올 플랫폼](#원포스트올플랫폼)

### 5. 그룹
  * [제목](#제목)
  * [핀](#태그)
  * [가입](#가입)
  * [수평식 권한 구조](#수평권한)
  * [하향식 권한 구조](#하향권한)

## 서버
### 1. DB
### 2. 채팅서버
---

## ID <a id="ID">
ID를 입력 받을 수 있어야함

ID는 이메일과 기타 부가적인 연동 서비스로도 가능해야함

---

## PW <a id="PW">
PW를 입력 받을 수 있어야함

필요에 따라 PW조건 부가 가능

연동시에는 연동 데이터로 해결할 것

---

## 기타 연동 <a id="연동">
여러가지 서비스로 회원가입이 가능해야함

예상 연동 서비스 목록 : FaceBook, Google, [LemonAde](http://lemontree.dothome.co.kr/lemonade/)

---

## 나이대 <a id="나이대">
나이대가 선택 가능해야함 (Ex. 10대, 20대, 30대...)

아직 나이대의 Max를 정하지 못했음 추후 정할 것

+ 17.05.22 추가
OO이상 OO이하 로 설정이 가능함 (Ex. 19세 이상 24세 이하)

---

## 관심 태그 <a id="태그">
초기 설정으로, 신규 유저가 관심있는 태그를 설정 가능해햐 함

만약 자신이 원하는 태그가 없다면 회원가입 도중에 설정가능해야 함

---

## 이름 설정 <a id="이름">
유저의 이름 설정이 가능해야 함

---

## 프로필 사진 설정 <a id="프사">
유저의 프로필 사진 설정이 가능해야 함

만약 미설정시, 기본 프로필 사진으로 등록

---

## 타임라인 <a id="타임라인">
※ 페이스북의 타임라인 참고

타임라인의 프레임을 구성해야 함

어느 태그에 소속 되었는지 나타나야 함

글 작성자 정보가 나타나야 함 (이름, 프로필 사진)

글 내용이 너무 많을 경우는 ...더보기 등으로 설정할 것

가끔식 광고 노출이 되어야 함

---

## 타임라인 새로고침 <a id="새로고침">
타임라인을 새로고침하면 새로운 내용으로 갱신 되어야 함

---

## 타임라인 태그 필터링 <a id="필터링">
원하는 태그 별로 타임라인이 필터링 되어야 함

원하는 태그를 고르면 그 외 태그에 대한 내용은 모두 필터링

---

## 광고 <a id="광고">
유저가 관심있는 태그와 관련된 광고를 보여줌

광고를 어떻게 끌어올지는 미정

광고의 형태 미정 (동영상 or 게시글 형식등등)

---

## 댓글 <a id="댓글">
댓글 작성이 가능해야 함

댓글 작성자 정보가 나타나야 함 (이름, 프로필 사진)

댓글에 이미지, 이모티콘의 여부는 미정

댓글 작성 위치 미정 (Ex. [글 내부](#글방식) or 타임라인에서 바로)

---

## 따봉 <a id="따봉">
따봉에 대한 이름을 아직 정하지 못하였음 (추후 변경)

관심있는 태그를 구별하기 위하여 존재 ([광고](#광고)에 사용)

---

## 공유 <a id="공유">
A그룹 -> B그룹으로 공유가 가능해야함

인앱 -> 외부 앱으로 공유가 가능해야함

게시글 권한이 존재할 때 공유에 대한 부분은 아직 미정

---

## 검색 <a id="검색">
앱에 대한 모든 내용에 대하여 검색이 가능해야 함

검색 결과는 탭 별로 분류하여 따로 따로 결과를 보여줌

탭은 인물, 그룹, 글 내용으로 분류

검색 내용 추가로 검색시 원래 검색 내용 + 추가 검색 내용이 되게 구현

몇 개 단위로 결과를 가져올지는 미정

---

## 팔로우 <a id="팔로우">
지정한 인물을 미리보기 함

미리 보기 : 타임라인에 최대한 상위에 노출

최대한의 범위는 아직 미정

팔로우 리스트에 등록 되어야 함

---

## 채팅 <a id="채팅">
지정한 인물과 채팅이 가능해야 함

---

## 신고 <a id="신고">
지정한 인물에 대한 신고가 가능해야 함

신고 분류 미정

신고 후 절차 미정

---

## 밴 <a id="밴">
지정한 인물을 차단함

---

## 이전에 올렸던 글 <a id="이전글">
지정한 유저의 이전 글 보기가 가능 해야 함

---

## 글 방식 (블로그식 or something else..) <a id="글방식">
2017/04/14 - 현재 미정
2017/07/27 - 블로그식 확정

---
## 원 포스트 올 플랫폼 <a id="원포스트올플랫폼">
연동한 타 SNS 플랫폼에 글 작성 형태에 맞게 자동으로 작성 및 수정이 가능함

일명 One Post All Platform

연동 플랫폼 (2017/07/27 기준) : Facebook, Nave Blog, Jekyll 블로그  

---

## 제목 <a id="제목">
그룹의 제목을 설정 가능해야 함
그룹의 제목은 중복불가
그룹 생성 후, 그룹명 변경 여부는 아직 정해지지 않음

---

## 핀 <a id="그룹핀">
그룹의 핀을 설정할 수 있음

핀의 최대 갯수는 2017/04/14기준 5개임

---

## 가입 <a id="가입">
그룹 연령조건에 해당해야 가입이 가능함
그룹 인원제한 가능

---

## 수평식 권한 구조 <a id="수평권한">
한 안건을 통과 시킬 때 투표가 진행됨

Ex.) A유저 그룹 퇴출 등

유저 참여에 관한것을 안건에 포함시킬지에 대한 여부는 미정

---

## 하향식 권한 구조 <a id="하향권한">
피라미드식으로 관리됨

Ex.) 관리자 -> 하위 관리자 등등...

유저 참여시 관리자들이 결정

---


# 공모전 <a id="contest">
- 글로벌 소프트웨어 공모전 (~7.31 참가 신청)
> http://www.globalswcontest.com/main.php

- 주니어 소프트웨어 창작대회 (~6.18 참가 신청)
> https://www.juniorswcup.com/contest/about

- IP Meister Program (~6.9 참가 신청)
> http://www.ip-edu.net/ipedu2012/front/ipedu/bbs/bbsDt.do?method=view&bbs_mngno=36&bbsd_mngno=15092&ju_mn=7&bu_mn=1

- Be the CEOs 제 14회 특성화고교생 사장되기 창업대회
> http://www.civo.net/board/view/code/civoboard_01/codeNo/1212

- 넥슨 아이디어 챌린지 (-6.16 참가 신청)
> https://www.nexon-ic.com/sub3.asp
