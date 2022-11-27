# busker
[team project] busker

`Nestjs와 Graphql을 이용해 위치를 기반으로 공연위치를 지도로 제공하는 웹 서비스`

## 프로젝트 기간
2022.10.28 ~ 2022.11.22

## 주요 서비스 화면
<img width="601" alt="스크린샷 2022-11-27 오후 11 39 15" src="https://user-images.githubusercontent.com/68360133/204141043-482e642e-026f-45dc-9c31-78122c85dd6e.png">

<img width="583" alt="스크린샷 2022-11-27 오후 11 39 22" src="https://user-images.githubusercontent.com/68360133/204141066-aeedaf1c-9f8a-4194-9a76-9e964f3fb5cf.png">

## 참고자료
[팀프로젝트 발표 자료](https://drive.google.com/file/d/1KP5vDIIk4Z5PNDbXSqZDbhx9kBz-B_rg/view?usp=share_link)

## 프로젝트 기술 스택
```
JavaScript
TypeScript
React
Apollo
NEXT
RECOIL
Nest.js
node.js
redis
Graphql
TypeORM
MYSQL
Github
Docker
Notion
Slack
AWS
Kubernetes
GCP
```

## 1. 배정받은 API 목록
```
signupUser -> 회원가입
fetchUser  -> 내정보 조회 
updateUser -> 내정보 수정
deleteUser -> 회원 탈퇴
sendVerificationEmail -> 인증 이메일 전송
confirmVerificationEmail -> 인증 번호 검증 
nonLoginSendVerificationEmail -> 비로그인 인증 메일 전송
nonLoginConfirmVerificationEmail -> 비로그인 인증 번호 검증
resetPassword -> 패스워드 변경
nonLoginResetPassword -> 비로그인 패스워드 변경
artistLikeToggle -> 좋아요 기능
deleteArtistLike -> 좋아요 취소 기능
fetchArtistCount -> 아티스트를 기준으로 좋아요 수 카운팅
fetchArtist -> 내 아티스트정보 조회
fetchArtistWithoutAuth -> 아티스트 조회
createArtist -> 아티스트 등록
updateArtist -> 내 아티스트 정보 수정
fetchMapList -> 현재 시간 및 현재 위도 경도를 기준으로 범위 내의 공연 정보 조회
roleGraud -> 아티스트 권한 정책 설정

```


## 2. Environment
로컬 개발 환경
- docker 환경구성

개발서버 배포 
- Oracle cloud 인스턴스 배포 및 GCP SQL 배포

prod 배포
- GCP + Kubernetes를 이용하여 prod 배포 진행

`현재는 prod 서버가 내려가 있는 상태`

## 3. ERD

![스크린샷 2022-11-28 오전 12 00 36](https://user-images.githubusercontent.com/68360133/204142004-6006a2cb-49cf-4a01-8fa9-2d1fd5645f68.png)

## 4. API 흐름도
![busker-project drawio](https://user-images.githubusercontent.com/68360133/204142033-9106dc3e-e988-46f0-bdc9-a86122145f05.png)


## 회고
```
처음 해보는 팀프로젝트라, 기획, 구성, 기술 모든게 서툴렀던 프로젝트.
협업시, 의사소통이 엄청나게 중요하다라는 깨달음을 주었던 프로젝트입니다.
```




