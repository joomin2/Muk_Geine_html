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


