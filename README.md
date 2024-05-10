# 🍟[Muk_Geine] Youtube API V3 활용 -요리 Iframe 동영상 업로드 테스트

![image](https://github.com/joomin2/Muk_Geine_html/assets/108183797/2ebdf928-4d3e-454c-b1f6-f962734e3bb9)

- 배포 URL :
- Test ID : 
- Test PW : 

<br>

## 테스트 시행착오

![image](https://github.com/joomin2/Muk_Geine_html/assets/108183797/5758d955-64d9-415d-98ef-bf493ef54b20)

# 개별 테스트 단계에서 로컬호스트로 서버를 구축하려고 시도 (구글측의 다양한 보안 이슈 .com 도메인 생성 , 400 invaild_request)
# node.js를 활용하여 Youtube api v3를 이용하려시도 (0auth2.0 계정 보안,SSL인증서 이슈 등으로 철회)
=> 현재 과정(2024/5/11)에서 가능한 무료로 해당 API를 활용하려고 노력함 
=> 간단한 Youtube API v3 KEY 만을 활용하여 html에서 유튜브 연결 성공 (Iframe 및 영상 재생 정상적으로 실행완료)

# 무료 일일 한도량 10000 제한 이슈
-> 개인 테스트 단계에서는 또 다른 계정으로 KEY값을 생성하여 테스트 완료 , API 할당량을 조절하려고 노력



## 향후 업데이트 계획

# 음식 변수 (meal_keyword)에 적용되는 값을 문자열이 아닌 유동적인 변수로 구현 -> 프로젝트 완성 단계에서 결과로 나오는 음식의 값 (ex: 짬뽕)이 바로 음식 변수에 담겨 해당 음식의 레시피 유튜브 영상이 화면에 적용되도록 구현 예정

![image](https://github.com/joomin2/Muk_Geine_html/assets/108183797/2f1a7718-9d94-4e96-8044-08b0ea7a2445)


# 모바일(애플리케이션)에서 Youtube api v3 을 구현예정 (Android Studio 활용)

=>  Web View 에서 해당 API KEY 만을 이용해서 테스트 단계에서 구현 완료 이후 모바일 개발 툴에서도 해당 유튜브API를 구현할 예정 
<br>

## 팀원 구성

<div align="center">

| **고지연** | **김민제** | **양희지** | **지창언** |
| :------: |  :------: | :------: | :------: |
| [<img src="https://avatars.githubusercontent.com/u/106502312?v=4" height=150 width=150> <br/> @yeon1615](https://github.com/yeon1615) | [<img src="https://avatars.githubusercontent.com/u/112460466?v=4" height=150 width=150> <br/> @Cheorizzang](https://github.com/Cheorizzang) | [<img src="https://avatars.githubusercontent.com/u/112460506?v=4" height=150 width=150> <br/> @heejiyang](https://github.com/heejiyang) | [<img src="https://avatars.githubusercontent.com/u/76766459?v=4" height=150 width=150> <br/> @journey-ji](https://github.com/journey-ji) |

</div>

<br>

## 1. 개발 환경

- Front : HTML, React, styled-components, Recoil
- Back-end : 제공된 API 활용
- 버전 및 이슈관리 : Github, Github Issues, Github Project
- 협업 툴 : Discord, Notion, Github Wiki
- 서비스 배포 환경 : Netlify
- 디자인 : 
<br>

## 2. 채택한 개발 기술과 브랜치 전략



### 브랜치 전략

- Git-flow 전략을 기반으로 main, develop 브랜치와 feature 보조 브랜치를 운용했습니다.
- main, develop, Feat 브랜치로 나누어 개발을 하였습니다.
    - **main** 브랜치는 배포 단계에서만 사용하는 브랜치입니다.
    - **develop** 브랜치는 개발 단계에서 git-flow의 master 역할을 하는 브랜치입니다.
    - **Feat** 브랜치는 기능 단위로 독립적인 개발 환경을 위하여 사용하고 merge 후 각 브랜치를 삭제해주었습니다.

<br>

## 3. 프로젝트 구조



## 4. 역할 분담

### 🍊고지연

-

<br>
    
### 👻김민제

- **UI**


<br>

### 😎양희지



<br>

### 🐬지창언

-
<br>

## 5. 개발 기간 및 작업 관리

### 개발 기간

- 전체 개발 기간 : 2022-12-09 ~ 2022-12-31
- UI 구현 : 2022-12-09 ~ 2022-12-16
- 기능 구현 : 2022-12-17 ~ 2022-12-31

<br>

### 작업 관리

- GitHub Projects와 Issues를 사용하여 진행 상황을 공유했습니다.
- 주간회의를 진행하며 작업 순서와 방향성에 대한 고민을 나누고 GitHub Wiki에 회의 내용을 기록했습니다.

<br>

## 6. 신경 쓴 부분

- [접근제한 설정](
- [Recoil을 통한 상태관리 및 유지]

## 7. 페이지별 기능

### [초기화면]
- 
| 초기화면 |
|----------|


<br>

### [회원가입]
- 이메일 주소와 비밀번호를 입력하면 입력창에서 바로 유효성 검사가 진행되고 통과하지 못한 경우 각 경고 문구가 입력창 하단에 표시됩니다.
- 이메일 주소의 형식이 유효하지 않거나 이미 가입된 이메일일 경우 또는 비밀번호가 6자 미만일 경우에는 각 입력창 하단에 경구 문구가 나타납니다.
- 작성이 완료된 후, 유효성 검사가 통과된 경우 다음 버튼이 활성화되며, 버튼을 클릭하면 프로필 설정 화면이 나타납니다.

| 회원가입 |
|----------|

<br>

### [프로필 설정]
-

| 프로필 설정 |
|----------|


<br>

### [로그인]

| 로그인 |
|----------|
|![login](https://user-images.githubusercontent.com/112460466/210177956-c716414e-01c2-4c1e-b1f7-6562b9b7a857.gif)|

<br>

### [로그아웃]


<br>

### [상하단 배너]
-

### [홈 피드]


<br>

### [검색]
- 사용자 이름 혹은 계정 ID로 유저를 검색할 수 있습니다.
- 검색어와 일치하는 단어는 파란색 글씨로 표시됩니다.
- 클릭 시 해당 유저의 프로필 페이지로 진입합니다.

<br>



## 8. 트러블 슈팅

- [탭메뉴 프로필 버튼 이슈](https://github.com/likelion-project-README/README/wiki/README-8.%ED%8A%B8%EB%9F%AC%EB%B8%94-%EC%8A%88%ED%8C%85_%ED%83%AD%EB%A9%94%EB%89%B4-%ED%94%84%EB%A1%9C%ED%95%84-%EB%B2%84%ED%8A%BC-%EC%9D%B4%EC%8A%88)

- [프로필 수정 이슈](https://github.com/likelion-project-README/README/wiki/README-8.%ED%8A%B8%EB%9F%AC%EB%B8%94-%EC%8A%88%ED%8C%85_%ED%94%84%EB%A1%9C%ED%95%84-%EC%88%98%EC%A0%95-%EC%9D%B4%EC%8A%88)

<br>

## 9. 개선 목표

-
    
- **23-01-17 성능 개선 내용**
    
    ![성능개선 후](https://user-images.githubusercontent.com/106502312/212872369-7ceeb2cf-d551-41d2-bfb0-01e35e9903fe.png)
    
    - 이미지 최적화
        - `<img>` 요소에 `width` , `height` 속성값을 명시해 불필요한 Reflow를 방지했습니다.
        - browser-image-compression 라이브러리를 사용해 유저가 업로드하는 이미지를 압축했습니다.
        - Intersection Observer API를 사용해 Lazy Loading 기법을 적용하여 홈 피드의 게시글 이미지가 viewport 내에 들어오는 순간 로딩되도록 변경했습니다.
    - 웹폰트 최적화
        - WOFF2 포맷을 추가하고 가장 우선적으로 적용되도록 선언했습니다.
        - 서브셋 폰트로 교체해 용량을 줄였습니다.
    
<br>

## 10. 프로젝트 후기

### 🍊 고지연

