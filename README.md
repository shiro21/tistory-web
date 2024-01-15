## Project Name
NextJS 블로그 | 기간: 2023.02.02 ~
* 날짜 ( 프로젝트 진행한 날짜 )
02.02, 02.06, 02.07, 02.08, 02.09, 02.10, 02.13, 02.14, 02.15, 02.16, 02.17, 02.20, 02.21, 02.22, 02.23, 02.24, 03.02, 03.06, 03.07, 03.10, 03.14, 03.16, 03.17

* ID : Kori

- 참고: 티스토리

## Front End Domain
https://next-blog-phm9kn2ov-shiro21.vercel.app/

## Tool
- Front-End: NextJS ( TypeScript )
- Back-End: NodeJS ( Javascript )
- Notion, 공책 ( 정리용 )

## Color
- https://encycolorpedia.kr/

Main Color: #4AA8D8 ( 밝은 파랑 )
Sub Color: #B55727 ( 반전 컬러 )

## Pages

## Login, Register
- 회원가입, 로그인 연습용
- Redux Toolkit ( 로그인 유지용 )
- dribbble 참조: https://dribbble.com/shots/19811417--Edupark-Sign-up-page

## Main
* Header
- Profile: 프로필 페이지 이동
- Login: 로그인 페이지 이동
* Side
- Home
- Tag
- Guest
- 카테고리별 글 목록 불러오기
* Contents
- 글 목록들
- 글 내용들 ( 업데이트, 삭제 가능, 댓글 가능[추가, 삭제], 좋아요 )

## Login
- login 관련 내용

## Register
- 회원가입 관련 내용

## Profile
- 카테고리 관리 ( 카테고리 추가, 삭제 )
- 링크 ( 링크 추가, 삭제 )
- 프로필 변경 ( 블로그 이름, 닉네임, 프로필 이미지 )

## Write
- 카테고리에 맞춰 글 작성 ( 제목, 태그, 내용[에디터사용], 메인 이미지 )

## Tag
- 태그 ( 중복태그가 많아질수록 글씨 크기 업그레이드 )

## Guest
- 관리자에게 글 쓰기 ( 비밀글가능 )


## 시간을 잡아먹던 내용들...
1. backend의 nodejs와 firebase연결 내용 ( Firebase Function을 이용하려면 업그레이드를 해야하는 내용 )
2. frontend의 vercel에 연동하는 내용
3. next/dynamic을 사용시 ref연결관련 내용
4. 이미지관련 내용



### npm install
npx @next/codemod next-image-to-legacy-image .

<!-- getServerSideProps를 위ㄴ -->
npm install --save @netlify/plugin-nextjs
npm install -g netlify-cli

npm install @reduxjs/toolkit react-redux
npm install --save-dev sass
npm install axios

npm install cookie
npm install @types/cookie
npm install @types/js-cookie
npm install react-cookies next-cookies
npm install @types/react-cookies

<!-- 에디터 ( SummerNote -> react-quill을 많이 사용한다고 하여 체택 ) -->
npm uninstall @types/summernote
npm install react-quill
npm uninstall quill-image-resize-module-ts
npm uninstall @looop/quill-image-resize-module-react
npm uninstall quill-image-resize-module
npm uninstall quill-image-resize

<!-- 모먼트 -->
npm install moment
npm install moment-timezone

npm install -D @types/react-draft-wysiwyg @types/draft-js @types/draftjs-to-html @types/
html-to-draftjs
npm install react-draft-wysiwyg draft-js draftjs-to-html html-to-draftjs
<!-- toast UI 업데이트 없음.. -->

<!-- styled 사용하기 -->
npm install styled-components
npm install -D babel-plugin-styled-components
npm install -D @types/styled-components


<!-- NEXT Auth ( https://next-auth.js.org/ ) -->
npm install next-auth

<!-- 폰트어썸 -->
npm install @fortawesome/fontawesome-svg-core
npm install @fortawesome/react-fontawesome
npm install @fortawesome/free-solid-svg-icons

<!-- React Cookie -->
npm install react-cookies

<!-- 차트JS -->
npm install react-chartjs-2 chart.js
<!-- 임시 데이터를 위해서 -->
npm i @faker-js/faker


<!-- Font Awesome Free -->
npm install -S @fortawesome/fontawesome-svg-core @fortawesome/react-fontawesome @fortawesome/free-regular-svg-icons @fortawesome/free-solid-svg-icons @fortawesome/free-brands-svg-icons