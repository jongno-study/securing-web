## 사전 개념

- **Authentication**: 인증
- **Authorization**: 권한 부여
- **Principal**: 보안 주체(ex. ID)
- **Credential**: 인증 정보(ex. PASSWORD)

## Spring Security Java Configuration 구성

애플리케이션의 모든 보안을 담당하는 Servlet Filter를 만들어 준다.

## springSecurityFilterChain 등록

`AbstractSecurityWebApplicationInitializer` 활용

## HttpSecurity

`WebSecurityConfigurerAdapter`에서 `configure(HttpSecurity http)` 구현

- http-basic: 인증 헤더(https://developer.mozilla.org/ko/docs/Web/HTTP/Authentication)
- form-login: form 태그

## 참고

[spring guide - securing-web](https://spring.io/guides/gs/securing-web/)

[spring security reference translation](https://github.com/ksug/spring-security-reference-translation)

[spring security reference](https://docs.spring.io/spring-security/site/docs/5.0.0.RELEASE/reference/htmlsingle/)

[spring security architecture](https://spring.io/guides/topicals/spring-security-architecture/)

[spring security tutorial](http://www.baeldung.com/security-spring)