# 크롤링된 (아프리카tv) 채팅내역 열람 대쉬보드

## 프로젝트 목적 및 배경
- 데이터를 이용한 대시보기 제작해보기
- Css-in-Js, Hooks 기술 적용하기

## 기술스택
- React.js (view, controller 구상)
- Redux (전역 state 관리)
- Hooks (state 컨트롤)
- Css-in-Js (js로 css 제작)
- jest (테스트)
## 기능
- 로그인
- 회원가입
- 권한
	- 일반사용자
		- 크롤링된 채팅방 목록 조회
			- 크롤링된 채팅 조회
				- 'ID'에 해당하는 채팅내역 검색 출력
				- 'text'가 포함된 채팅내역 검색 출력
				- 채팅 유저 id 목록 출력
		- 크롤링 요청
	- 관리자
		- 일반사용자 목록 조회
			- 일반사용자 제거
---